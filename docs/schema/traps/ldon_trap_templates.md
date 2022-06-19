# ldon_trap_templates

!!! info
	This page was last generated 2022.06.18

## Relationship Diagram

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgbGRvbl90cmFwX3RlbXBsYXRlcyB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIHNtYWxsaW50dW5zaWduZWQgc3BlbGxfaWRcbiAgICB9XG4gICAgbGRvbl90cmFwX2VudHJpZXMge1xuICAgICAgICBpbnR1bnNpZ25lZCB0cmFwX2lkXG4gICAgfVxuICAgIHNwZWxsc19uZXcge1xuICAgICAgICBpbnQgaWRcbiAgICAgICAgdmFyY2hhciB0ZWxlcG9ydF96b25lXG4gICAgICAgIGludCBkZXNjbnVtXG4gICAgICAgIGludCBlZmZlY3RkZXNjbnVtXG4gICAgICAgIGludCBlZmZlY3RkZXNjbnVtMlxuICAgICAgICBpbnQgdHlwZWRlc2NudW1cbiAgICB9XG4gICAgbGRvbl90cmFwX3RlbXBsYXRlcyB8fC0tb3sgbGRvbl90cmFwX2VudHJpZXMgOiBIYXMtTWFueVxuICAgIGxkb25fdHJhcF90ZW1wbGF0ZXMgfHwtLW97IHNwZWxsc19uZXcgOiBPbmUtdG8tT25lXG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9){target=diagram-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgbGRvbl90cmFwX3RlbXBsYXRlcyB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIHNtYWxsaW50dW5zaWduZWQgc3BlbGxfaWRcbiAgICB9XG4gICAgbGRvbl90cmFwX2VudHJpZXMge1xuICAgICAgICBpbnR1bnNpZ25lZCB0cmFwX2lkXG4gICAgfVxuICAgIHNwZWxsc19uZXcge1xuICAgICAgICBpbnQgaWRcbiAgICAgICAgdmFyY2hhciB0ZWxlcG9ydF96b25lXG4gICAgICAgIGludCBkZXNjbnVtXG4gICAgICAgIGludCBlZmZlY3RkZXNjbnVtXG4gICAgICAgIGludCBlZmZlY3RkZXNjbnVtMlxuICAgICAgICBpbnQgdHlwZWRlc2NudW1cbiAgICB9XG4gICAgbGRvbl90cmFwX3RlbXBsYXRlcyB8fC0tb3sgbGRvbl90cmFwX2VudHJpZXMgOiBIYXMtTWFueVxuICAgIGxkb25fdHJhcF90ZW1wbGF0ZXMgfHwtLW97IHNwZWxsc19uZXcgOiBPbmUtdG8tT25lXG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgbGRvbl90cmFwX3RlbXBsYXRlcyB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIHNtYWxsaW50dW5zaWduZWQgc3BlbGxfaWRcbiAgICB9XG4gICAgbGRvbl90cmFwX2VudHJpZXMge1xuICAgICAgICBpbnR1bnNpZ25lZCB0cmFwX2lkXG4gICAgfVxuICAgIHNwZWxsc19uZXcge1xuICAgICAgICBpbnQgaWRcbiAgICAgICAgdmFyY2hhciB0ZWxlcG9ydF96b25lXG4gICAgICAgIGludCBkZXNjbnVtXG4gICAgICAgIGludCBlZmZlY3RkZXNjbnVtXG4gICAgICAgIGludCBlZmZlY3RkZXNjbnVtMlxuICAgICAgICBpbnQgdHlwZWRlc2NudW1cbiAgICB9XG4gICAgbGRvbl90cmFwX3RlbXBsYXRlcyB8fC0tb3sgbGRvbl90cmFwX2VudHJpZXMgOiBIYXMtTWFueVxuICAgIGxkb25fdHJhcF90ZW1wbGF0ZXMgfHwtLW97IHNwZWxsc19uZXcgOiBPbmUtdG8tT25lXG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9){target=diagram}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| Has-Many | id | [ldon_trap_entries](../../schema/traps/ldon_trap_entries.md) | trap_id |
| One-to-One | spell_id | [spells_new](../../schema/spells/spells_new.md) | id |

## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| id | int | Unique LDoN Trap Template Identifier |
| type | tinyint | [Trap Type](../../../../server/zones/trap-types) |
| spell_id | smallint | [Spell Identifier](../../schema/spells/spells_new.md) |
| skill | smallint | [Skill](../../../../server/player/skills) |
| locked | tinyint | Locked: 0 = False, 1 = True |

