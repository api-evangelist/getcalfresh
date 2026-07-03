# GetCalFresh (getcalfresh)

GetCalFresh is a service delivered by Code for America on behalf of the people of California, providing plain-language guidance to help Californians understand and navigate CalFresh (SNAP) food benefits. Since California's statewide move to BenefitsCal.com on the CalSAWS platform, GetCalFresh.org no longer accepts applications directly - it is an informational and guidance site that hands off to BenefitsCal and county agencies for eligibility determination and case processing. No public developer API is documented; historically, before BenefitsCal existed, Code for America's application tooling submitted CalFresh applications to county systems via generated PDF forms, fax, and secure email rather than a documented API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/getcalfresh/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/getcalfresh/refs/heads/main/apis.yml)

## Scope

- **Type:** Nonprofit
- **Position:** Consuming
- **Access:** None Documented

## Tags

- Civic Tech
- Nonprofit
- Government
- Public Benefits
- SNAP
- Food Assistance
- California

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## Access Model

GetCalFresh is an end-user public service, not an API product, and Code for America has not published a developer portal, API reference, or SDK for it. A few things are worth being precise about:

- **GetCalFresh.org today** is informational only. Its own About page states plainly: "You can't apply for CalFresh on this website." Applicants are directed to [BenefitsCal.com](https://benefitscal.com), the state's official application portal built on CalSAWS (California Statewide Automated Welfare System), which all 58 counties now use for eligibility and case management. GetCalFresh does not process applications, determine eligibility, or access case information.
- **Historically**, before BenefitsCal existed, GetCalFresh (and its predecessor, the SF-focused `clean` app) collected applicant information through its own web form and then submitted it into county systems the only way available at the time - by generating a filled-out PDF application and delivering it via fax and secure email, because, in Code for America's own words, "a standard set of APIs doesn't exist" for county eligibility systems.
- **Code for America's public GitHub org** ([github.com/codeforamerica](https://github.com/codeforamerica)) hosts the GetCalFresh-related repositories - `clean` (the original "Apply for CalFresh in SF" Rails app, now archived), `gcf-microsite`, and `calfresh-conversion-experiment` - as open-source application tooling and research code, not as an API or SDK.
- No AsyncAPI, OpenAPI, Postman/OpenCollection, rate limit, plans/pricing, or FinOps artifacts are included in this entry because none are sourced from a real, documented surface. GetCalFresh is a free public benefit service; there is no pricing to model.

## APIs

No public APIs have been documented. GetCalFresh is a guidance and referral service, not an API provider; the underlying eligibility system of record is the state's BenefitsCal/CalSAWS platform, which itself does not publish a public developer API.

## Common Properties

- [GitHub Organization](https://github.com/codeforamerica)
- [Website](https://www.getcalfresh.org)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
