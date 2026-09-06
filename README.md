# Alexander Korovin

Staff Software Engineer focused on agentic systems, AI-assisted engineering,
developer tooling, reliability, and security boundaries.

> I am currently open to Staff / Senior engineering opportunities around
> agentic systems, developer infrastructure, reliability, and security.

## Open-source systems portfolio

These projects are intentionally small enough to run and inspect. Each one
includes a reproducible demo, explicit limitations, automated tests, and a
public release path.

| Project | What it does | Try or inspect |
|---|---|---|
| [ctxfire](https://github.com/korovin-aa97/ctxfire) | Maps the context inherited by coding agents and estimates repeated token load with visible assumptions. | [PyPI](https://pypi.org/project/ctxfire/) · local CLI · SARIF |
| [Fleet Failure Atlas](https://github.com/korovin-aa97/fleet-failure-atlas) | Turns synthetic coding-agent failure mechanisms into bounded reproductions, detectors, repair invariants, and regression proofs. | [Live atlas](https://korovin-aa97.github.io/fleet-failure-atlas/) · dependency-free fixtures |
| [FairSem](https://github.com/korovin-aa97/fairsem) | Gives unrelated commands on one Linux machine a visible, oldest-first admission queue. | [Latest release](https://github.com/korovin-aa97/fairsem/releases/latest) · five-job demo |
| [CI Evidence Gate](https://github.com/korovin-aa97/ci-evidence-gate) | Binds GitHub checks to the exact PR commit, workflow provenance, changed surface, and base-commit policy. | [GitHub Marketplace](https://github.com/marketplace/actions/ci-evidence-gate) · JSON receipts |
| [Agent Self-Edit Gate](https://github.com/korovin-aa97/agent-self-edit-gate) | Applies deterministic policy to coding-agent behaviour edits while keeping authority files outside the mutable set. | [PyPI](https://pypi.org/project/agent-self-edit-gate/) · threat model |

## What this work emphasizes

- narrow contracts instead of broad AI claims;
- failure modes, adversarial tests, and fail-closed behaviour;
- exact provenance and machine-readable evidence;
- local-first tools with no telemetry or required hosted service;
- quickstarts and demos that can be reproduced without private infrastructure;
- explicit boundaries for what a tool does **not** prove or enforce.

The repositories are maintained as public engineering artifacts. Issues,
independent reproductions, integration reports, and critical review are welcome.
