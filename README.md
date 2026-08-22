# GetCalFresh (getcalfresh)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
