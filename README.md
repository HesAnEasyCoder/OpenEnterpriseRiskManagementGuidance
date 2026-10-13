## OpenEnterpriseRiskManagementGuidance

# Risk Management for Open-Weight Models
If you run open weights on your own infrastructure, the safeguards are yours to build. This repository holds the shared taxonomy, the evaluation index, and the templates that accompany the NVIDIA–Microsoft paper series — so you can start from a risk that matters in your deployment. 

# Start Here
taxonomy/ — five risk categories and the risk types beneath them, with stable IDs you can reference in your own register.

# Mitigations
process/ holds the controls, organised by the layer they act on: model-layer controls are in scope for paper 1, runtime-layer controls are previewed here and treated properly in paper 2. Every entry in process/index.yaml names the risk types it addresses and the evaluation that re-verifies it, because a control you have not re-measured is an assumption. Neither layer holds on its own: a content filter will not stop credential abuse, and a rate limit will not stop a fabricated number.

# What this is not
Not a certification, not a compliance checklist, and not a claim that a passing score makes a deployment safe. An evaluation result describes behavior under the conditions you tested and nothing more.

# Contributing
We are explicitly asking for evaluations we are missing. Open a propose-evaluation issue with the risk type it addresses, the task and language it covers, its scoring method, and its known limitations. Mapping gaps and new risk types are equally welcome.

# Maintainership
This repository sits in the NVIDIA org and is co-maintained by NVIDIA and Microsoft. Changes to taxonomy/ and evaluations/index.yaml require approval from a maintainer at each organization; CODEOWNERS enforces this and how a third-party contributor becomes a maintainer. Everything else follows ordinary single-approval review.
