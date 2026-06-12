# NewsAPI (newsapi)

NewsAPI is a simple, easy-to-use REST API that returns JSON metadata for news articles and breaking headlines published by over 80,000 worldwide sources and blogs. The API supports full-text keyword search across hundreds of millions of articles, filtering by source domain, language, date range, and sorting by relevance or publication date. A dedicated top-headlines endpoint delivers live breaking news by country and category — covering business, entertainment, general, health, science, sports, and technology. Developers authenticate via an API key passed as a query parameter or HTTP header, and all responses are returned as standard JSON.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/newsapi/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=newsapi-api-evangelist&utm_content=repo

## Tags

- News
- Headlines
- Articles
- Search
- Media
- Content
- REST
- JSON

## APIs

| Name | Base URL | Documentation |
|------|----------|---------------|
| NewsAPI | https://newsapi.org/v2 | https://newsapi.org/docs |

### Endpoints

| Endpoint | Method | Path | Description |
|----------|--------|------|-------------|
| Everything | GET | /v2/everything | Search all news articles with keyword, source, domain, language, and date filters |
| Top Headlines | GET | /v2/top-headlines | Retrieve live breaking headlines by country, category, or source |
| Sources | GET | /v2/sources | List available news sources supported by the API |

## Plans, Rate Limits, and FinOps

| Resource | Path |
|----------|------|
| Plans and Pricing | [plans/newsapi-plans-pricing.yml](plans/newsapi-plans-pricing.yml) |
| Rate Limits | [rate-limits/newsapi-rate-limits.yml](rate-limits/newsapi-rate-limits.yml) |
| FinOps | [finops/newsapi-finops.yml](finops/newsapi-finops.yml) |

### Plan Summary

| Plan | Price | Included Requests | Overage |
|------|-------|-------------------|---------|
| Developer | Free | 100/day | None |
| Business | $449/month | 250,000/month | $0.0018/request |
| Advanced | $1,749/month | 2,000,000/month | $0.0009/request |
| Enterprise | Contact | Unlimited | Custom |

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | https://newsapi.org/ |
| Documentation | https://newsapi.org/docs |
| GitHub Org | https://github.com/News-API-gh |
| LinkedIn | https://www.linkedin.com/company/newsapi |
| Blog | https://newsapi.org/blog |
| Pricing | https://newsapi.org/pricing |
| Status Page | https://newsapi.org/status |
| X (Twitter) | https://x.com/newsapi |

### Official SDKs (GitHub: News-API-gh)

- [News-API-python](https://github.com/News-API-gh/News-API-python) — Python client library
- [News-API-node](https://github.com/News-API-gh/News-API-node) — Node.js client library
- [News-API-csharp](https://github.com/News-API-gh/News-API-csharp) — C# client library
- [News-API-java](https://github.com/News-API-gh/News-API-java) — Java client library
- [News-API-php](https://github.com/News-API-gh/News-API-php) — PHP client library

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
