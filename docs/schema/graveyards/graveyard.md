# graveyard

!!! info
	This page was last generated 2022.06.18

## Relationship Diagram

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgZ3JhdmV5YXJkIHtcbiAgICAgICAgaW50IHpvbmVfaWRcbiAgICB9XG4gICAgem9uZSB7XG4gICAgICAgIGludCB6b25laWRudW1iZXJcbiAgICAgICAgdGlueWludHVuc2lnbmVkIHZlcnNpb25cbiAgICAgICAgdmFyY2hhciBzaG9ydF9uYW1lXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc1xuICAgICAgICB2YXJjaGFyIGNvbnRlbnRfZmxhZ3NfZGlzYWJsZWRcbiAgICB9XG4gICAgZ3JhdmV5YXJkIHx8LS1veyB6b25lIDogT25lLXRvLU9uZVxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==){target=diagram-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgZ3JhdmV5YXJkIHtcbiAgICAgICAgaW50IHpvbmVfaWRcbiAgICB9XG4gICAgem9uZSB7XG4gICAgICAgIGludCB6b25laWRudW1iZXJcbiAgICAgICAgdGlueWludHVuc2lnbmVkIHZlcnNpb25cbiAgICAgICAgdmFyY2hhciBzaG9ydF9uYW1lXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc1xuICAgICAgICB2YXJjaGFyIGNvbnRlbnRfZmxhZ3NfZGlzYWJsZWRcbiAgICB9XG4gICAgZ3JhdmV5YXJkIHx8LS1veyB6b25lIDogT25lLXRvLU9uZVxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgZ3JhdmV5YXJkIHtcbiAgICAgICAgaW50IHpvbmVfaWRcbiAgICB9XG4gICAgem9uZSB7XG4gICAgICAgIGludCB6b25laWRudW1iZXJcbiAgICAgICAgdGlueWludHVuc2lnbmVkIHZlcnNpb25cbiAgICAgICAgdmFyY2hhciBzaG9ydF9uYW1lXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc1xuICAgICAgICB2YXJjaGFyIGNvbnRlbnRfZmxhZ3NfZGlzYWJsZWRcbiAgICB9XG4gICAgZ3JhdmV5YXJkIHx8LS1veyB6b25lIDogT25lLXRvLU9uZVxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==){target=diagram}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | zone_id | [zone](../../schema/zone/zone.md) | zoneidnumber |

## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| id | int | Unique Graveyard Identifier |
| zone_id | int | [Zone Identifier](../../../../server/zones/zone-list) |
| x | float | X Coordinate |
| y | float | Y Coordinate |
| z | float | Z Coordinate |
| heading | float | Heading Coordinate |

