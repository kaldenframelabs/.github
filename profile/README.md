# KaldenFrame Labs

Inspectable local tools for evidence, execution, and release decisions.

KaldenFrame Labs builds small public utilities around decisions that are easy to blur in technical work: whether a claim is documented well enough to review, whether a real execution attempt began, and whether one exact artifact may advance under a declared policy. Each tool keeps its operating boundary explicit and can be inspected before adoption.

## Choose the decision

| Decision you need to make | Product | Current release | Start here |
| --- | --- | --- | --- |
| Is this claim documented well enough to enter serious review? | [Evidence Preflight](https://github.com/kaldenframelabs/evidence-preflight) | [v1.3.2](https://github.com/kaldenframelabs/evidence-preflight/releases/tag/v1.3.2) | [Open the browser-local worksheet](https://kaldenframelabs.com/preflight/) |
| Did preflight stop the job, or was the real execution command invoked? | [Attempt Boundary](https://github.com/kaldenframelabs/attempt-boundary) | [v0.1.0](https://github.com/kaldenframelabs/attempt-boundary/releases/tag/v0.1.0) | [Read the product record](https://kaldenframelabs.com/products/attempt-boundary/) |
| May this exact implementation advance under the declared policy? | [Artifact Admission](https://github.com/kaldenframelabs/artifact-admission) | [v0.1.1](https://github.com/kaldenframelabs/artifact-admission/releases/tag/v0.1.1) | [Read the product record](https://kaldenframelabs.com/products/artifact-admission/) |

The products are independent. They can be adopted separately or sequenced deliberately, but they do not form an automatic pipeline and do not combine into universal proof. The [workflow guide](https://kaldenframelabs.com/products/workflow/) shows the handoffs and the boundary between them.

## When the repository needs a tailored review

The public utilities expose reusable decision boundaries. They do not diagnose how those boundaries interact inside a specific repository.

The [Release Boundary Review](https://kaldenframelabs.com/services/release-boundary-review/) is a fixed-scope **$450 USD** engagement for one public GitHub repository and one named release path. It delivers:

- a repository-specific release-decision map;
- evidence, artifact-identity, and attempt-boundary gap analysis;
- a prioritized implementation roadmap; and
- one consolidated follow-up email.

Delivery is within five business days after written scope acceptance, complete intake, and payment confirmation. Scope is confirmed by email before payment. The review requires no credentials or private-repository access and is not implementation, penetration testing, security certification, or compliance attestation.

[Check the fixed-scope fit in your browser →](https://kaldenframelabs.com/services/release-boundary-review/fit/)

[Inspect a synthetic report sample →](https://kaldenframelabs.com/services/release-boundary-review/sample/)

[Review the complete scope and request the service →](https://kaldenframelabs.com/services/release-boundary-review/)

## What is inspectable

- Public MIT-licensed source, tests, contracts, and neutral examples.
- Dependency-free Node.js packages with no runtime network requests.
- Versioned final releases with exact package and source SHA-256 values.
- First-party documentation for installation, first run, exit behavior, and operating limits.
- A strict [machine-readable product catalog](https://kaldenframelabs.com/products/catalog.json) and [Draft 2020-12 schema](https://kaldenframelabs.com/schemas/product-catalog-v1.schema.json).

Start with the [product catalog](https://kaldenframelabs.com/products/), use the [documentation hub](https://kaldenframelabs.com/docs/) to operate a release, and follow the [release index](https://kaldenframelabs.com/releases/) or [Atom feed](https://kaldenframelabs.com/releases/feed.xml) for current versions.

## Trust boundary

A public repository, commit identifier, release tag, or matching hash identifies reviewable code and exact bytes. It is not a signature, provenance attestation, vulnerability report, endorsement, adoption signal, or guarantee of correctness, safety, or fitness. Each product documents the narrower decision it supports and what remains outside that decision.

For product evaluation, support, billing, or security routing, use the [contact guide](https://kaldenframelabs.com/contact/). For a suspected vulnerability, read the [security policy](https://github.com/kaldenframelabs/.github/security/policy) before sharing details.

© 2026 KaldenFrame Labs.
