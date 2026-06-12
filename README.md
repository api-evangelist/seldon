# Seldon (seldon)

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
