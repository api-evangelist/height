# Height (height)

Height was an AI-powered collaborative project management tool that provided a REST API for managing tasks, lists, workspaces, attributes, dependencies, and automation triggers. The API enabled developers to programmatically interact with workspace resources, manage team members, post activity comments, configure webhooks for real-time event notifications, and integrate Height into custom workflows. Authentication was handled via secret API keys from workspace settings, with OAuth 2.0 available for third-party integrations. Height announced the shutdown of its service with a final date of September 24, 2025.

APIs.json: https://raw.githubusercontent.com/api-evangelist/height/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=height-api-evangelist&utm_content=repo

## Tags

- Project Management
- Task Management
- Collaboration
- Productivity
- Workflow Automation
- AI

## APIs

| Name | Description | Docs |
|------|-------------|------|
| Height REST API | REST API for tasks, lists, users, activities, field templates, webhooks, and automations | [Docs](https://www.notion.so/API-documentation-643aea5bf01742de9232e5971cb4afda) |

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/height-plans-pricing.yml](plans/height-plans-pricing.yml) |
| Rate Limits | [rate-limits/height-rate-limits.yml](rate-limits/height-rate-limits.yml) |
| FinOps | [finops/height-finops.yml](finops/height-finops.yml) |

**Pricing summary:**
- Free: $0/member/month — unlimited members, 50 MB storage, basic automations
- Team: $8.50/member/month (monthly) or $6.99/member/month (annual)
- Business: $14.99/member/month (monthly) or $11.99/member/month (annual)
- Enterprise: Custom pricing

**Rate limits:**
- Global: 120 requests/minute
- POST /activities: 60 requests/minute
- POST /tasks: 60 requests/minute
- HTTP 429 returned on excess

## Timestamps

| Field | Value |
|-------|-------|
| Created | 2026-06-13 |
| Modified | 2026-06-13 |

## Common

| Type | URL |
|------|-----|
| Website | https://height.app |
| Documentation | https://www.notion.so/API-documentation-643aea5bf01742de9232e5971cb4afda |
| GitHub Org | https://github.com/heightapp |
| LinkedIn | https://www.linkedin.com/company/heightapp |
| Blog | https://height.app/blog |
| Pricing | https://height.app/pricing |
| Status Page | https://status.height.app |
| X / Twitter | https://twitter.com/height_app |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
