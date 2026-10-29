# Applied statistics · Reproducible data science · Reliable AI

I work on **statistical modeling, empirical validation, and data-centric machine learning**. My projects emphasize careful experimental design, uncertainty, reproducible code, and clear limits on what the evidence shows.

## Selected research projects

These links lead to **research software and supporting evidence**, not a list of peer-reviewed journal publications. The README of each repository explains its data, methods, frozen results, and reproducibility limitations.

| Research project | What the code and evidence demonstrate |
| --- | --- |
| **[PISA 2022: model verification and evaluation](https://github.com/Jackxiaozhiren/pisa2022-xai-math)** | Statistical validation using PISA mathematics plausible values, survey weights, Fay–BRR uncertainty, calibration diagnostics, a matched EBM comparison, and unseen-school evaluation. Raw OECD data must be obtained from its original source. |
| **[Biomedical knowledge-graph reliability](https://github.com/Jackxiaozhiren/jbi-biomedical-reliability-screen)** | A conditional reliability screen for biomedical link predictions, with a frozen protocol, derived statistics, and external-data/time-sliced validation. It does **not** establish clinical effectiveness or causal benefit. |
| **[Bayesian TSK regression and uncertainty](https://github.com/Jackxiaozhiren/tsk-spikeslab)** | Corrected Bayesian spike-and-slab model averaging, posterior-predictive uncertainty, numerical diagnostics, and tests. The evaluated method is **not** claimed to beat strong dense-TSK and GP baselines. |
| **[Tabular-to-image encoding experiments](https://github.com/Jackxiaozhiren/tabular-image-encoding-dissection)** | A controlled comparison across 15 public tabular datasets, exploring categorical features, image encoding, architecture, feature ordering, and conventional tabular baselines. Results are protocol-specific. |

**Publication boundary:** GitHub repositories, software version tags, continuous-integration checks, and software/dataset DOIs do not indicate that an associated manuscript has been accepted or peer reviewed. Historical journal submissions, where mentioned in a project, are distinct from published papers.

## Selected engineering work

| Software project | What it demonstrates |
| --- | --- |
| [DataSentry](https://github.com/Jackxiaozhiren/datasentry) | Local-first data-quality detection with evidence-based diagnostics and a reversible propose → preview → repair → verify workflow. |
| [Data Science Agent](https://github.com/Jackxiaozhiren/data-science-agent) | SQL/statistical analysis and machine-learning workflows with traceable evidence behind generated claims. |
| [QuantRisk++](https://github.com/Jackxiaozhiren/quantrisk-plus-plus) | C++/Python quantitative finance implementations with numerical reference checks and reproducible risk simulations. |

Additional software projects: [Interve-AI](https://github.com/Jackxiaozhiren/Interve-AI) (interview practice and feedback) · [MotionSites](https://github.com/Jackxiaozhiren/MotionSites) (motion-driven frontend experiments).

## Research and engineering approach

- **Define the estimand or question first:** distinguish a demonstrated metric, an interpretation, and a real-world claim.
- **Compare against alternatives:** use baselines, ablations, sensitivity checks, and acknowledge meaningful negative findings.
- **Make results inspectable:** publish permitted code, test cases, frozen summaries, data-source instructions, and known reproducibility limits.
- **Report scope accurately:** CI success tests software behavior; it does not prove general theorems, study novelty, or journal acceptance.

## Open-source collaboration

I also contribute to community-maintained projects. For example, [upstream PR #12213](https://github.com/punkpeye/awesome-mcp-servers/pull/12213) is a proposed listing of the DataSentry MCP integration in a third-party community directory, **not** a project I maintain.
