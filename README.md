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
