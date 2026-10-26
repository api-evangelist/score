# Score (score)

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

Score is an open-source, platform-agnostic workload specification developed under the Cloud Native Computing Foundation (CNCF) Sandbox program. It provides a developer-centric YAML specification that enables teams to define application workloads once and deploy them across multiple container platforms including Docker Compose, Kubernetes, and cloud runtimes without environment-specific configuration drift.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/score/refs/heads/main/apis.yml)

## Tags

- Platform Engineering
- Cloud Native
- CNCF
- Workload Specification
- Kubernetes
- Docker
- Developer Experience
- Open Source

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs / Specifications

### Score Specification

The Score Specification (score.yaml) is a declarative, platform-agnostic workload definition format that captures containers, service ports, and resource dependencies in a single file.

**Human URL:** [https://score.dev/](https://score.dev/)

#### Tags

- Platform Engineering
- Workload Specification
- Cloud Native
- CNCF
- Open Source

#### Properties

- [Documentation](https://docs.score.dev/)
- [Specification Reference](https://docs.score.dev/docs/score-specification/score-spec-reference/)
- [GitHub Repository](https://github.com/score-spec/spec)

### score-compose

The reference Score implementation for Docker Compose. Translates score.yaml into docker-compose.yml for local development.

- [Documentation](https://docs.score.dev/docs/score-implementation/score-compose/)
- [GitHub Repository](https://github.com/score-spec/score-compose)

### score-k8s

The reference Score implementation for Kubernetes. Translates score.yaml into Kubernetes manifests.

- [Documentation](https://docs.score.dev/docs/score-implementation/score-k8s/)
- [GitHub Repository](https://github.com/score-spec/score-k8s)

## Common Properties

- [Website](https://score.dev/)
- [GitHub Organization](https://github.com/score-spec)
- [Documentation](https://docs.score.dev/)
- [CNCF Slack #score](https://cloud-native.slack.com/archives/C07DN0D1UCW)

## Artifacts

### JSON-LD

- [Score Context](json-ld/score-context.jsonld) — Linked data context mapping Score specification vocabulary to schema.org and OCI/CNCF terms.

### Examples

- [Basic Workload Example](examples/score-basic-workload-example.json) — Example score.yaml for a web service with database and cache resources.
- [Compose Output Example](examples/score-compose-output-example.json) — Example Docker Compose output generated by score-compose.

### Vocabulary

- [Score Vocabulary](vocabulary/score-vocabulary.yml) — Domain vocabulary for Score specification concepts, platform engineering, and cloud-native deployment patterns.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
