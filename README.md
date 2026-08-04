# Seldon (seldon)

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

Seldon is a Kubernetes-native MLOps platform that enables enterprises to deploy, monitor, manage, and explain machine learning models at scale. The platform provides REST and gRPC inference APIs following the Open Inference Protocol, enabling standardized model serving across frameworks including TensorFlow, PyTorch, and scikit-learn. Seldon Core 2 supports advanced deployment strategies such as A/B testing, canary rollouts, and shadow deployments. The Seldon Enterprise Platform extends the open source core with a comprehensive REST management API, model drift detection via Alibi-Detect, and explainability via the Alibi library.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/seldon/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/seldon/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=seldon-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=seldon-api-evangelist&utm_content=repo)

## Tags

- MLOps
- Machine Learning
- Model Serving
- Inference
- Kubernetes
- AI Operations
- Drift Detection
- Explainability
- Canary Deployment
- A/B Testing
- LLMOps

## APIs

| Name | Description |
|------|-------------|
| Seldon Inference API | REST and gRPC endpoints for serving ML model predictions following the Open Inference Protocol (V2). |
| Seldon Enterprise Platform REST API | Programmatic management of ML deployments via a full REST API with Swagger UI. |
| Seldon Drift Detection API | Alibi-Detect powered endpoints for monitoring incoming request distributions against training data baselines. |
| Seldon Explainability API | Dedicated /explain REST endpoint powered by the Alibi library (SHAP, integrated gradients, anchors). |

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans and Pricing | [plans/seldon-plans-pricing.yml](plans/seldon-plans-pricing.yml) |
| Rate Limits | [rate-limits/seldon-rate-limits.yml](rate-limits/seldon-rate-limits.yml) |
| FinOps | [finops/seldon-finops.yml](finops/seldon-finops.yml) |

**Plans summary:** Open source (Seldon Core, MLServer — free), Seldon Enterprise Platform (custom annual pricing), Seldon Core+ (custom, unlimited models/users).

**Rate limits:** Seldon is self-hosted on Kubernetes; no platform-enforced API rate limits exist. Throughput is governed by infrastructure resources and ingress-layer configuration managed by the deploying organization.

**FinOps:** Primary cost drivers are Kubernetes compute (CPU/GPU nodes) billed through the cloud provider, plus an annual Seldon Enterprise Platform license for commercial deployments. MLServer adaptive batching and multi-model serving are key optimization levers.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Property | URL |
|----------|-----|
| Website | https://www.seldon.io |
| Documentation | https://docs.seldon.ai/home |
| GitHub Organization | https://github.com/SeldonIO |
| LinkedIn | https://www.linkedin.com/company/seldon |
| X (Twitter) | https://x.com/seldon_io |
| Blog | https://www.seldon.io/resources/blog/ |
| Pricing | https://www.seldon.io/pricing/ |
| Status Page | https://status.seldon.io |
| SDK (Python) | https://github.com/SeldonIO/seldon-deploy-sdk |

## Maintainers

**Kin Lane** — kin@apievangelist.com
