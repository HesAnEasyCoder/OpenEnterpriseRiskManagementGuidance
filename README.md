# OpenEnterpriseRiskManagementGuidance

## Risk Management for Open-Weight Models
Open-weight models give enterprises greater control to inspect, evaluate, modify, and operate models in their own environments. This flexibility also changes how models are evaluated, where safeguards are applied, and who maintains them over time. 

This joint NVIDIA–Microsoft repository offers resources to help enterprises deploy open-weight models safely, securely, and responsibly. The repository is organized as follows.

### Papers
Guidance papers to support risk management and governance of open-weight model deployments.

### Taxonomy
The risk taxonomy provides a shared vocabulary for how risks arise in AI systems, grouping risk types (L2) under broader risk categories (L1) to support effective management. It will be updated regularly as new risks emerge.

### Evaluations
Maps evaluations to the risk taxonomy and will be updated regularly with open-source benchmarks, evaluations published by NVIDIA and Microsoft, and community contributions.

### Mitigations
Controls, organized by system layer (model, runtime, harness, and application).

## Contributing
We encourage developers, security practitioners, researchers, and others working in this space to contribute evaluations that can help strengthen this shared body of work. Open a propose-evaluation issue with the risk type it addresses, the task and language it covers, its scoring method, and its known limitations. Mapping gaps and new risk types are equally welcome.

## Maintainership
This repository sits in the NVIDIA org and is co-maintained by NVIDIA and Microsoft. Changes to taxonomy/ and evaluations/index.yaml require approval from a maintainer at each organization; CODEOWNERS enforces this and how a third-party contributor becomes a maintainer. Everything else follows ordinary single-approval review.
