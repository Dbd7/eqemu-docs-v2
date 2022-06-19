# account_rewards

!!! info
	This page was last generated 2022.06.18

## Relationship Diagram

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYWNjb3VudF9yZXdhcmRzIHtcbiAgICAgICAgaW50dW5zaWduZWQgcmV3YXJkX2lkXG4gICAgICAgIGludHVuc2lnbmVkIGFjY291bnRfaWRcbiAgICB9XG4gICAgdmV0ZXJhbl9yZXdhcmRfdGVtcGxhdGVzIHtcbiAgICAgICAgaW50dW5zaWduZWQgaXRlbV9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBjbGFpbV9pZFxuICAgIH1cbiAgICBhY2NvdW50X3Jld2FyZHMgfHwtLW97IHZldGVyYW5fcmV3YXJkX3RlbXBsYXRlcyA6IE9uZS10by1PbmVcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagram-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYWNjb3VudF9yZXdhcmRzIHtcbiAgICAgICAgaW50dW5zaWduZWQgcmV3YXJkX2lkXG4gICAgICAgIGludHVuc2lnbmVkIGFjY291bnRfaWRcbiAgICB9XG4gICAgdmV0ZXJhbl9yZXdhcmRfdGVtcGxhdGVzIHtcbiAgICAgICAgaW50dW5zaWduZWQgaXRlbV9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBjbGFpbV9pZFxuICAgIH1cbiAgICBhY2NvdW50X3Jld2FyZHMgfHwtLW97IHZldGVyYW5fcmV3YXJkX3RlbXBsYXRlcyA6IE9uZS10by1PbmVcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYWNjb3VudF9yZXdhcmRzIHtcbiAgICAgICAgaW50dW5zaWduZWQgcmV3YXJkX2lkXG4gICAgICAgIGludHVuc2lnbmVkIGFjY291bnRfaWRcbiAgICB9XG4gICAgdmV0ZXJhbl9yZXdhcmRfdGVtcGxhdGVzIHtcbiAgICAgICAgaW50dW5zaWduZWQgaXRlbV9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBjbGFpbV9pZFxuICAgIH1cbiAgICBhY2NvdW50X3Jld2FyZHMgfHwtLW97IHZldGVyYW5fcmV3YXJkX3RlbXBsYXRlcyA6IE9uZS10by1PbmVcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagram}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | reward_id | [veteran_reward_templates](../../schema/admin/veteran_reward_templates.md) | claim_id |

## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| account_id | int | [Account Identifier](account.md) |
| reward_id | int | [Veteran Reward Identifier](../../schema/admin/veteran_reward_templates.md) |
| amount | int | Amount |

