# dynamic_zones

!!! info
	This page was last generated 2022.06.18

## Relationship Diagram

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgZHluYW1pY196b25lcyB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIGludHVuc2lnbmVkIGNvbXBhc3Nfem9uZV9pZFxuICAgICAgICBpbnQgaW5zdGFuY2VfaWRcbiAgICAgICAgaW50dW5zaWduZWQgc2FmZV9yZXR1cm5fem9uZV9pZFxuICAgIH1cbiAgICB6b25lIHtcbiAgICAgICAgaW50IHpvbmVpZG51bWJlclxuICAgICAgICB0aW55aW50dW5zaWduZWQgdmVyc2lvblxuICAgICAgICB2YXJjaGFyIHNob3J0X25hbWVcbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc19kaXNhYmxlZFxuICAgIH1cbiAgICBkeW5hbWljX3pvbmVfbWVtYmVycyB7XG4gICAgICAgIGludHVuc2lnbmVkIGNoYXJhY3Rlcl9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBkeW5hbWljX3pvbmVfaWRcbiAgICB9XG4gICAgaW5zdGFuY2VfbGlzdCB7XG4gICAgICAgIGludCBpZFxuICAgICAgICBpbnR1bnNpZ25lZCB6b25lXG4gICAgICAgIHRpbnlpbnR1bnNpZ25lZCB2ZXJzaW9uXG4gICAgfVxuICAgIHpvbmUge1xuICAgICAgICBpbnQgem9uZWlkbnVtYmVyXG4gICAgICAgIHRpbnlpbnR1bnNpZ25lZCB2ZXJzaW9uXG4gICAgICAgIHZhcmNoYXIgc2hvcnRfbmFtZVxuICAgICAgICB2YXJjaGFyIGNvbnRlbnRfZmxhZ3NcbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzX2Rpc2FibGVkXG4gICAgfVxuICAgIGR5bmFtaWNfem9uZXMgfHwtLW97IHpvbmUgOiBPbmUtdG8tT25lXG4gICAgZHluYW1pY196b25lcyB8fC0tb3sgZHluYW1pY196b25lX21lbWJlcnMgOiBIYXMtTWFueVxuICAgIGR5bmFtaWNfem9uZXMgfHwtLW97IGluc3RhbmNlX2xpc3QgOiBPbmUtdG8tT25lXG4gICAgZHluYW1pY196b25lcyB8fC0tb3sgem9uZSA6IE9uZS10by1PbmVcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagram-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgZHluYW1pY196b25lcyB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIGludHVuc2lnbmVkIGNvbXBhc3Nfem9uZV9pZFxuICAgICAgICBpbnQgaW5zdGFuY2VfaWRcbiAgICAgICAgaW50dW5zaWduZWQgc2FmZV9yZXR1cm5fem9uZV9pZFxuICAgIH1cbiAgICB6b25lIHtcbiAgICAgICAgaW50IHpvbmVpZG51bWJlclxuICAgICAgICB0aW55aW50dW5zaWduZWQgdmVyc2lvblxuICAgICAgICB2YXJjaGFyIHNob3J0X25hbWVcbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc19kaXNhYmxlZFxuICAgIH1cbiAgICBkeW5hbWljX3pvbmVfbWVtYmVycyB7XG4gICAgICAgIGludHVuc2lnbmVkIGNoYXJhY3Rlcl9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBkeW5hbWljX3pvbmVfaWRcbiAgICB9XG4gICAgaW5zdGFuY2VfbGlzdCB7XG4gICAgICAgIGludCBpZFxuICAgICAgICBpbnR1bnNpZ25lZCB6b25lXG4gICAgICAgIHRpbnlpbnR1bnNpZ25lZCB2ZXJzaW9uXG4gICAgfVxuICAgIHpvbmUge1xuICAgICAgICBpbnQgem9uZWlkbnVtYmVyXG4gICAgICAgIHRpbnlpbnR1bnNpZ25lZCB2ZXJzaW9uXG4gICAgICAgIHZhcmNoYXIgc2hvcnRfbmFtZVxuICAgICAgICB2YXJjaGFyIGNvbnRlbnRfZmxhZ3NcbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzX2Rpc2FibGVkXG4gICAgfVxuICAgIGR5bmFtaWNfem9uZXMgfHwtLW97IHpvbmUgOiBPbmUtdG8tT25lXG4gICAgZHluYW1pY196b25lcyB8fC0tb3sgZHluYW1pY196b25lX21lbWJlcnMgOiBIYXMtTWFueVxuICAgIGR5bmFtaWNfem9uZXMgfHwtLW97IGluc3RhbmNlX2xpc3QgOiBPbmUtdG8tT25lXG4gICAgZHluYW1pY196b25lcyB8fC0tb3sgem9uZSA6IE9uZS10by1PbmVcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgZHluYW1pY196b25lcyB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIGludHVuc2lnbmVkIGNvbXBhc3Nfem9uZV9pZFxuICAgICAgICBpbnQgaW5zdGFuY2VfaWRcbiAgICAgICAgaW50dW5zaWduZWQgc2FmZV9yZXR1cm5fem9uZV9pZFxuICAgIH1cbiAgICB6b25lIHtcbiAgICAgICAgaW50IHpvbmVpZG51bWJlclxuICAgICAgICB0aW55aW50dW5zaWduZWQgdmVyc2lvblxuICAgICAgICB2YXJjaGFyIHNob3J0X25hbWVcbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc19kaXNhYmxlZFxuICAgIH1cbiAgICBkeW5hbWljX3pvbmVfbWVtYmVycyB7XG4gICAgICAgIGludHVuc2lnbmVkIGNoYXJhY3Rlcl9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBkeW5hbWljX3pvbmVfaWRcbiAgICB9XG4gICAgaW5zdGFuY2VfbGlzdCB7XG4gICAgICAgIGludCBpZFxuICAgICAgICBpbnR1bnNpZ25lZCB6b25lXG4gICAgICAgIHRpbnlpbnR1bnNpZ25lZCB2ZXJzaW9uXG4gICAgfVxuICAgIHpvbmUge1xuICAgICAgICBpbnQgem9uZWlkbnVtYmVyXG4gICAgICAgIHRpbnlpbnR1bnNpZ25lZCB2ZXJzaW9uXG4gICAgICAgIHZhcmNoYXIgc2hvcnRfbmFtZVxuICAgICAgICB2YXJjaGFyIGNvbnRlbnRfZmxhZ3NcbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzX2Rpc2FibGVkXG4gICAgfVxuICAgIGR5bmFtaWNfem9uZXMgfHwtLW97IHpvbmUgOiBPbmUtdG8tT25lXG4gICAgZHluYW1pY196b25lcyB8fC0tb3sgZHluYW1pY196b25lX21lbWJlcnMgOiBIYXMtTWFueVxuICAgIGR5bmFtaWNfem9uZXMgfHwtLW97IGluc3RhbmNlX2xpc3QgOiBPbmUtdG8tT25lXG4gICAgZHluYW1pY196b25lcyB8fC0tb3sgem9uZSA6IE9uZS10by1PbmVcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagram}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | compass_zone_id | [zone](../../schema/zone/zone.md) | zoneidnumber |
| Has-Many | id | [dynamic_zone_members](../../schema/dynamic-zones/dynamic_zone_members.md) | dynamic_zone_id |
| One-to-One | instance_id | [instance_list](../../schema/instances/instance_list.md) | id |
| One-to-One | safe_return_zone_id | [zone](../../schema/zone/zone.md) | zoneidnumber |

## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| id | int | Unique Dynamic Zone Identifier |
| instance_id | int | [Instance Identifier](../../schema/instances/instance_list.md) |
| type | tinyint | Type |
| uuid | varchar | UUID |
| name | varchar | Name |
| leader_id | int | [Leader Character Identifier](../../schema/characters/character_data.md) |
| min_players | int | Minimum Players |
| max_players | int | Maximum Players |
| compass_zone_id | int | [Compass Zone Identifier](../../../../server/zones/zone-list) |
| compass_x | float | Compass X Coordinate |
| compass_y | float | Compass Y Coordinate |
| compass_z | float | Compass Z Coordinate |
| safe_return_zone_id | int | [Safe Return Zone Identifier](../../../../server/zones/zone-list) |
| safe_return_x | float | Safe Return X Coordinate |
| safe_return_y | float | Safe Return Y Coordinate |
| safe_return_z | float | Safe Return Z Coordinate |
| safe_return_heading | float | Safe Return Heading Coordinate |
| zone_in_x | float | Zone In X Coordinate |
| zone_in_y | float | Zone In Y Coordinate |
| zone_in_z | float | Zone In Z Coordinate |
| zone_in_heading | float | Zone In Heading Coordinate |
| has_zone_in | tinyint | Has Zone In: 0 = False, 1 = True |

