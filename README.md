# Miguel Castuera García

**Detection Engineering · SOC Platform Engineering · Security Automation**

I build and extend security platforms: bringing telemetry into a usable shape,
turning security questions into testable detections, and connecting findings to
investigation workflows. I enjoy the software engineering behind security
operations, especially when an integration or missing capability needs to be built.

## Featured engineering work

### [SentinelOps MXDR](https://github.com/miguelcastu/SentinelOps-MXDR)

A Microsoft Sentinel engineering lab connecting detection-as-code, scoped Azure
deployment, telemetry health, risk correlation and controlled case handling.
**Python · KQL · Azure · Bicep · GitHub Actions / OIDC.** Dated cloud evidence is
separated from synthetic replay; the security detections remain disabled.

[Architecture](https://github.com/miguelcastu/SentinelOps-MXDR/blob/main/docs/architecture/overview.md)
· [Offline demonstration](https://github.com/miguelcastu/SentinelOps-MXDR#try-it-in-one-command)
· [Engineering decisions](https://github.com/miguelcastu/SentinelOps-MXDR/blob/main/docs/portfolio/engineering-decisions.md)

### [ForgeSOC](https://github.com/miguelcastu/ForgeSOC)

An experimental detection and response platform built from the inside out:
source normalization, stateful rules, durable event evidence, an analyst console
and case management. **Python · PostgreSQL · SQLAlchemy / Alembic · FastAPI.**
The focus is explicit contracts and reproducible behavior, not production scale.

[Architecture](https://github.com/miguelcastu/ForgeSOC/blob/main/docs/architecture/overview.md)
· [Try the pipeline](https://github.com/miguelcastu/ForgeSOC#quick-start)
· [Tests](https://github.com/miguelcastu/ForgeSOC/blob/main/docs/development/testing.md)

### [BrandWatch Lab](https://github.com/miguelcastu/BrandImpersonation)

Explainable investigation of possible brand impersonation: candidate discovery,
provenance, DNS/RDAP context, rendered browser evidence and local review reports.
**Python · SQLite · Playwright.** Candidates and scores are leads for an analyst;
the application does not submit takedowns or classify a domain as proven malicious.

[Design decisions](https://github.com/miguelcastu/BrandImpersonation/tree/main/docs/adr)
· [Offline example](https://github.com/miguelcastu/BrandImpersonation#run-the-offline-example)
· [Collection walkthrough](https://github.com/miguelcastu/BrandImpersonation/blob/main/docs/sprints/02-collection.md)

## Choose a path

| Your interest | Start here |
| --- | --- |
| Recruiting / hiring | Read the three project summaries above, then try SentinelOps' offline explorer. |
| Detection engineering | SentinelOps' KQL portfolio and ForgeSOC's executable rule registry and regression tests. |
| Platform engineering / security architecture | SentinelOps' OIDC boundaries and ForgeSOC's persistence and API architecture. |
| Technical interview | Follow a source event through normalization, rule state, evidence and case handling; compare the trade-offs across projects. |

## Engineering toolkit

The repositories demonstrate **Python backend development**, **SQL/PostgreSQL**,
**KQL detection-as-code**, **Azure/Bicep**, **REST integrations**, **GitHub Actions**,
**Docker-based local workflows**, and deterministic tests. I use these to explore
telemetry quality, detection behavior, investigation evidence and failure handling.
My current learning includes **Google Security Operations**.

## Foundations and contact

[Project directory](PROJECTS.md) — earlier software, AI, data and security exercises,
with their educational scope kept explicit.

Reach me at [miguelcastu27@gmail.com](mailto:miguelcastu27@gmail.com).
