# Vendelux

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

Vendelux is an AI-native event marketing and B2B event intelligence platform. It helps go-to-market
teams decide which conferences and trade shows to attend, pre-book qualified meetings before an
event starts, and attribute pipeline back to specific events — from a proprietary database of
250,000+ global B2B events. Founded in 2021 by Alex Reynolds and Stefan Deeran, headquartered in
New York City, and backed by FirstMark Capital, Cervin Ventures, Tenacity Ventures and Tri-Valley
Ventures.

- Website: https://vendelux.com/
- Pricing: https://vendelux.com/pricing
- Help Center: https://vendelux.com/help
- Trust Center: https://trust.vendelux.com/
- Engineering blog: https://developers.vendelux.com/
- GitHub: https://github.com/Vendelux

## API surface: none published

Vendelux publishes **no public developer API**. Probed 2026-09-02: no OpenAPI, GraphQL schema,
AsyncAPI, webhook catalog, SDK, CLI, MCP server, A2A agent card, developer portal or API reference
exists on any Vendelux host.

- `api.vendelux.com` is a real DNS record but its origin returned HTTP 502 on every path probed.
- `developers.vendelux.com` is a WordPress **engineering blog**, not a developer portal, and
  returned HTTP 404 for every spec and `/.well-known/` path.
- The `Vendelux` GitHub organization is public but has **zero** repositories.
- No `vendelux` package exists on npm, PyPI, RubyGems, crates.io or Packagist.
- No pricing tier lists API access, an API key, or a call quota.

The only programmatic surface Vendelux sells is a CRM integration in which **Vendelux is the OAuth
client**, connecting outbound into a customer's Salesforce or HubSpot tenant — consuming someone
else's API, not publishing one. Vendelux's Terms of Service §2.4 additionally prohibits automated
access outside its own Integration Tools, and its `robots.txt` disallows CCBot, GPTBot,
Google-Extended, Omgilibot and FacebookBot site-wide.

What Vendelux *does* publish, and what this profile records, is a compliance and commercial surface:
a Drata-hosted Trust Center, a GDPR / EU-US Data Privacy Framework privacy program with a public
subprocessor list, and three named (but unpriced) plan tiers.
