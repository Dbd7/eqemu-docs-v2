# tasksets

!!! info
	This page was last generated 2022.06.18

## Relationship Diagram

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgdGFza3NldHMge1xuICAgICAgICBpbnR1bnNpZ25lZCB0YXNraWRcbiAgICB9XG4gICAgdGFza3Mge1xuICAgICAgICBpbnR1bnNpZ25lZCBpZFxuICAgICAgICB0aW55aW50IHR5cGVcbiAgICB9XG4gICAgdGFza3NldHMgfHwtLW97IHRhc2tzIDogT25lLXRvLU9uZVxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==){target=diagram-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgdGFza3NldHMge1xuICAgICAgICBpbnR1bnNpZ25lZCB0YXNraWRcbiAgICB9XG4gICAgdGFza3Mge1xuICAgICAgICBpbnR1bnNpZ25lZCBpZFxuICAgICAgICB0aW55aW50IHR5cGVcbiAgICB9XG4gICAgdGFza3NldHMgfHwtLW97IHRhc2tzIDogT25lLXRvLU9uZVxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgdGFza3NldHMge1xuICAgICAgICBpbnR1bnNpZ25lZCB0YXNraWRcbiAgICB9XG4gICAgdGFza3Mge1xuICAgICAgICBpbnR1bnNpZ25lZCBpZFxuICAgICAgICB0aW55aW50IHR5cGVcbiAgICB9XG4gICAgdGFza3NldHMgfHwtLW97IHRhc2tzIDogT25lLXRvLU9uZVxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==){target=diagram}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | taskid | [tasks](../../schema/tasks/tasks.md) | id |

## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| id | int | Unique Task Set Entry Identifier |
| taskid | int | [Task Identifier](tasks.md) |

