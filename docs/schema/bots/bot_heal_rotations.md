# bot_heal_rotations

!!! info
	This page was last generated 2022.06.18

## Relationship Diagram

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYm90X2hlYWxfcm90YXRpb25zIHtcbiAgICAgICAgaW50dW5zaWduZWQgYm90X2lkXG4gICAgICAgIGludHVuc2lnbmVkIGhlYWxfcm90YXRpb25faW5kZXhcbiAgICB9XG4gICAgYm90X2RhdGEge1xuICAgICAgICBpbnR1bnNpZ25lZCBib3RfaWRcbiAgICAgICAgaW50dW5zaWduZWQgc3BlbGxzX2lkXG4gICAgICAgIGludHVuc2lnbmVkIG93bmVyX2lkXG4gICAgICAgIHNtYWxsaW50IHpvbmVfaWRcbiAgICB9XG4gICAgYm90X2hlYWxfcm90YXRpb25fbWVtYmVycyB7XG4gICAgICAgIGludHVuc2lnbmVkIGhlYWxfcm90YXRpb25faW5kZXhcbiAgICAgICAgaW50dW5zaWduZWQgYm90X2lkXG4gICAgfVxuICAgIGJvdF9oZWFsX3JvdGF0aW9uX3RhcmdldHMge1xuICAgICAgICBpbnR1bnNpZ25lZCBoZWFsX3JvdGF0aW9uX2luZGV4XG4gICAgfVxuICAgIGJvdF9oZWFsX3JvdGF0aW9ucyB8fC0tb3sgYm90X2RhdGEgOiBPbmUtdG8tT25lXG4gICAgYm90X2hlYWxfcm90YXRpb25zIHx8LS1veyBib3RfaGVhbF9yb3RhdGlvbl9tZW1iZXJzIDogSGFzLU1hbnlcbiAgICBib3RfaGVhbF9yb3RhdGlvbnMgfHwtLW97IGJvdF9oZWFsX3JvdGF0aW9uX3RhcmdldHMgOiBIYXMtTWFueVxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==){target=diagram-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYm90X2hlYWxfcm90YXRpb25zIHtcbiAgICAgICAgaW50dW5zaWduZWQgYm90X2lkXG4gICAgICAgIGludHVuc2lnbmVkIGhlYWxfcm90YXRpb25faW5kZXhcbiAgICB9XG4gICAgYm90X2RhdGEge1xuICAgICAgICBpbnR1bnNpZ25lZCBib3RfaWRcbiAgICAgICAgaW50dW5zaWduZWQgc3BlbGxzX2lkXG4gICAgICAgIGludHVuc2lnbmVkIG93bmVyX2lkXG4gICAgICAgIHNtYWxsaW50IHpvbmVfaWRcbiAgICB9XG4gICAgYm90X2hlYWxfcm90YXRpb25fbWVtYmVycyB7XG4gICAgICAgIGludHVuc2lnbmVkIGhlYWxfcm90YXRpb25faW5kZXhcbiAgICAgICAgaW50dW5zaWduZWQgYm90X2lkXG4gICAgfVxuICAgIGJvdF9oZWFsX3JvdGF0aW9uX3RhcmdldHMge1xuICAgICAgICBpbnR1bnNpZ25lZCBoZWFsX3JvdGF0aW9uX2luZGV4XG4gICAgfVxuICAgIGJvdF9oZWFsX3JvdGF0aW9ucyB8fC0tb3sgYm90X2RhdGEgOiBPbmUtdG8tT25lXG4gICAgYm90X2hlYWxfcm90YXRpb25zIHx8LS1veyBib3RfaGVhbF9yb3RhdGlvbl9tZW1iZXJzIDogSGFzLU1hbnlcbiAgICBib3RfaGVhbF9yb3RhdGlvbnMgfHwtLW97IGJvdF9oZWFsX3JvdGF0aW9uX3RhcmdldHMgOiBIYXMtTWFueVxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYm90X2hlYWxfcm90YXRpb25zIHtcbiAgICAgICAgaW50dW5zaWduZWQgYm90X2lkXG4gICAgICAgIGludHVuc2lnbmVkIGhlYWxfcm90YXRpb25faW5kZXhcbiAgICB9XG4gICAgYm90X2RhdGEge1xuICAgICAgICBpbnR1bnNpZ25lZCBib3RfaWRcbiAgICAgICAgaW50dW5zaWduZWQgc3BlbGxzX2lkXG4gICAgICAgIGludHVuc2lnbmVkIG93bmVyX2lkXG4gICAgICAgIHNtYWxsaW50IHpvbmVfaWRcbiAgICB9XG4gICAgYm90X2hlYWxfcm90YXRpb25fbWVtYmVycyB7XG4gICAgICAgIGludHVuc2lnbmVkIGhlYWxfcm90YXRpb25faW5kZXhcbiAgICAgICAgaW50dW5zaWduZWQgYm90X2lkXG4gICAgfVxuICAgIGJvdF9oZWFsX3JvdGF0aW9uX3RhcmdldHMge1xuICAgICAgICBpbnR1bnNpZ25lZCBoZWFsX3JvdGF0aW9uX2luZGV4XG4gICAgfVxuICAgIGJvdF9oZWFsX3JvdGF0aW9ucyB8fC0tb3sgYm90X2RhdGEgOiBPbmUtdG8tT25lXG4gICAgYm90X2hlYWxfcm90YXRpb25zIHx8LS1veyBib3RfaGVhbF9yb3RhdGlvbl9tZW1iZXJzIDogSGFzLU1hbnlcbiAgICBib3RfaGVhbF9yb3RhdGlvbnMgfHwtLW97IGJvdF9oZWFsX3JvdGF0aW9uX3RhcmdldHMgOiBIYXMtTWFueVxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==){target=diagram}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | bot_id | [bot_data](../../schema/bots/bot_data.md) | bot_id |
| Has-Many | heal_rotation_index | [bot_heal_rotation_members](../../schema/bots/bot_heal_rotation_members.md) | heal_rotation_index |
| Has-Many | heal_rotation_index | [bot_heal_rotation_targets](../../schema/bots/bot_heal_rotation_targets.md) | heal_rotation_index |

## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| heal_rotation_index | int | Unique Heal Rotation Identifier |
| bot_id | int | [Bot Identifier](bot_data.md) |
| interval | int | Interval |
| fast_heals | int | Fast Heals |
| adaptive_targeting | int | Adaptive Targeting |
| casting_override | int | Casting Override |
| safe_hp_base | float | Safe Health Base |
| safe_hp_cloth | float | Safe Health Cloth |
| safe_hp_leather | float | Safe Health Leather |
| safe_hp_chain | float | Safe Health Chain |
| safe_hp_plate | float | Safe Health Plate |
| critical_hp_base | float | Critical Health Base |
| critical_hp_cloth | float | Critical Health Cloth |
| critical_hp_leather | float | Critical Health Leather |
| critical_hp_chain | float | Critical Health Chain |
| critical_hp_plate | float | Critical Health Plate |

