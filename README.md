# Applied statistics · Verifiable data science · Reliable AI

I build data, statistics, and AI systems with an emphasis on **reproducibility, measurable quality, and evidence-backed results**. My work spans data quality, autonomous analysis, interactive applications, and quantitative research.

## Selected software projects

| Project | Focus |
| --- | --- |
| [DataSentry](https://github.com/Jackxiaozhiren/datasentry) | Local-first data quality: inspect statistical evidence, detect drift, and review repairs before applying them. |
| [Data Science Agent](https://github.com/Jackxiaozhiren/data-science-agent) | Reproducible data analysis across SQL, statistics, machine learning, and visualization, with evidence for generated claims. |
| [Interve-AI](https://github.com/Jackxiaozhiren/Interve-AI) | Multimodal AI interview **practice** and feedback platform; not a hiring-screening tool. |
| [QuantRisk++](https://github.com/Jackxiaozhiren/quantrisk-plus-plus) | C++/Python quantitative finance engine with numerical reference tests and reproducible risk/Monte Carlo experiments. |
| [MotionSites](https://github.com/Jackxiaozhiren/MotionSites) | Gallery of 30 motion-driven frontend experiments and live demos. |

## Research and reproducibility

- [REA-Bench](https://github.com/Jackxiaozhiren/rea-bench) — auditable benchmark and FDR-controlled claim verifier for reverse-engineering agents. The current public report is explicit that the M3 cohort is captured but the stochastic layer-2 adjustment is still pending.
- [DeepInfer research audit](https://github.com/Jackxiaozhiren/deepinfer-research) — independent CPU-only simulation study of published speculative-decoding speedup claims; it is not presented as a production hardware benchmark.
- [PISA 2022 XAI & mathematics](https://github.com/Jackxiaozhiren/pisa2022-xai-math) — design-aware model verification with plausible values, Fay-BRR uncertainty, fairness and calibration checks.
- [Bayesian TSK spike-and-slab](https://github.com/Jackxiaozhiren/tsk-spikeslab) — model averaging, posterior predictive uncertainty, diagnostics, and reproducibility materials.
- [Tabular-to-image encoding](https://github.com/Jackxiaozhiren/tabular-image-encoding-dissection) — controlled comparison of encoding decisions across tabular datasets.
- [Biomedical KG reliability](https://github.com/Jackxiaozhiren/jbi-biomedical-reliability-screen) — study-specific verification protocol and frozen evidence artifacts.

These repositories document research methods, inputs, limitations, and verification steps. Please check each project's README and data-use terms before reproducing or citing a result.

## Open-source collaboration

I contribute to projects maintained by the wider open-source community. For example, my [upstream pull request #12213](https://github.com/punkpeye/awesome-mcp-servers/pull/12213) proposes listing the DataSentry MCP server in [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers). **That directory is an upstream community project, not one of my original software projects.** The PR remains open until its maintainers merge it.

## How I work

- Statistical evidence first; AI assistance with explicit checks and human review where needed.
- Deterministic tests, locked dependencies, and CI that fails when an expected artifact or result is missing.
- Clear separation between demonstrated results, hypotheses, and limitations.
