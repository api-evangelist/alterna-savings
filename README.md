# Alterna Savings (alterna-savings)

Alterna Savings and Credit Union Limited is a member-owned financial cooperative (credit union) founded in 1908, headquartered in Ottawa, Ontario and regulated by the Financial Services Regulatory Authority of Ontario (FSRAO). It serves roughly 217,000 members with about C$10.8 billion in assets and operates the federally regulated direct-banking subsidiary Alterna Bank, one of Canada's earliest digital-first banks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/alterna-savings/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/alterna-savings/refs/heads/main/apis.yml)

## Open-Finance / API Posture

Alterna Savings exposes **no public first-party developer portal or documented API**. A probe of `developer.alterna.ca` does not resolve (DNS `ENOTFOUND`), and neither the main site nor its online-banking pages document any API, OpenAPI/Swagger, or third-party data-sharing program.

- **Developer portal:** none found.
- **Documented APIs:** none. Digital access is delivered through Alterna's online and mobile banking apps.
- **Canadian rails:** the online-banking product includes **Interac e-Transfer** (send/receive/request money) as a consumer feature — not a published API. No documented Real-Time Rail (RTR) / Payments Canada API surface.
- **Consumer-Driven Banking (CDB):** Canada's federal open-banking / consumer-driven banking framework (Budget 2024 + Fall Economic Statement 2024, overseen by the FCAC) is legislated but **not yet operational**. Alterna publishes no stated CDB or FDX position.
- **Aggregator access:** consistent with most Canadian credit unions, any third-party consumer data access today is aggregator/screen-scraping based (e.g. Flinks, Plaid, MX, Salt Edge) rather than a first-party API.

This is an identity-only record. It will be enriched by a separate pipeline; no public API surface exists to harvest at bootstrap time.

## Tags

- Financial Services
- Banking
- Canada
- Credit Union
- Cooperative
- Consumer-Driven Banking
- Interac
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None documented. Alterna Savings does not operate a public developer portal or expose a documented public API.

## Common Properties

- [Website](https://www.alterna.ca/)
- [Terms of Service](https://www.alterna.ca/en/legal)
- [Privacy Policy](https://www.alterna.ca/en/privacy-and-security)
- [Support](https://www.alterna.ca/en/about-us/contact-us)
- [Blog](https://www.alterna.ca/en/personal/resource-centre/advice-for-life-blog)
- [LinkedIn](https://www.linkedin.com/company/alternasavings)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
