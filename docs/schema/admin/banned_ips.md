# banned_ips

!!! info
	This page was last generated 2022.06.18

## Relationship Diagram

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYmFubmVkX2lwcyB7XG4gICAgICAgIHZhcmNoYXIgaXBfYWRkcmVzc1xuICAgIH1cbiAgICBhY2NvdW50X2lwIHtcbiAgICAgICAgdmFyY2hhciBpcFxuICAgICAgICBpbnQgYWNjaWRcbiAgICB9XG4gICAgYmFubmVkX2lwcyB8fC0tb3sgYWNjb3VudF9pcCA6IEhhcy1NYW55XG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9){target=diagram-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYmFubmVkX2lwcyB7XG4gICAgICAgIHZhcmNoYXIgaXBfYWRkcmVzc1xuICAgIH1cbiAgICBhY2NvdW50X2lwIHtcbiAgICAgICAgdmFyY2hhciBpcFxuICAgICAgICBpbnQgYWNjaWRcbiAgICB9XG4gICAgYmFubmVkX2lwcyB8fC0tb3sgYWNjb3VudF9pcCA6IEhhcy1NYW55XG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYmFubmVkX2lwcyB7XG4gICAgICAgIHZhcmNoYXIgaXBfYWRkcmVzc1xuICAgIH1cbiAgICBhY2NvdW50X2lwIHtcbiAgICAgICAgdmFyY2hhciBpcFxuICAgICAgICBpbnQgYWNjaWRcbiAgICB9XG4gICAgYmFubmVkX2lwcyB8fC0tb3sgYWNjb3VudF9pcCA6IEhhcy1NYW55XG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9){target=diagram}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| Has-Many | ip_address | [account_ip](../../schema/account/account_ip.md) | ip |

## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| ip_address | varchar | [IP Address](../../schema/account/account_ip.md) |
| notes | varchar | Ban reason |

