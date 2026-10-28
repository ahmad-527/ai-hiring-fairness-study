# AI hiring: perceived fairness and employer attractiveness

An exploratory survey study comparing reactions to hypothetical job rejections attributed to a human recruiter or an AI system. Completed for **M506 — Research Methods and Scientific Work, Gisma University of Applied Sciences**, September 2026. This is a coursework research showcase; it has not been peer reviewed.

**My contribution:** I completed all statistical analysis and wrote the full submitted report. The original coursework submission carries a group author list.

## Research question

Do early-career job seekers rate procedural fairness and employer attractiveness differently after a hypothetical human-mediated versus AI-mediated rejection?

Each participant rated both scenarios. The primary analytical sample contained **19 participants**, with presentation order counterbalanced: 10 human-first and 9 AI-first. The project covers survey design, scale scoring, paired statistical comparisons, effect sizes, confidence intervals and sensitivity analysis.

## Main findings

Ratings were higher for the human scenario on both outcomes in this sample. All ratings use a 1–5 scale; differences are **human minus AI**.

| Outcome | Human mean | AI mean | Paired difference | 95% CI for difference | Cohen's dz | Holm-adjusted p |
| --- | ---: | ---: | ---: | --- | ---: | ---: |
| Procedural fairness | 2.93 | 2.45 | 0.481 | [0.055, 0.908] | 0.54 | 0.029 |
| Employer attractiveness | 3.32 | 2.42 | 0.895 | [0.299, 1.490] | 0.72 | 0.011 |

These estimates describe reactions to the specific scenarios. They do not establish how applicants behave in real recruitment or whether a hiring system is objectively fair.

## How much confidence to place in the results

- **Small, non-probability sample:** N = 19 was below the report's smallest planning estimate of 30 participants. Of 41 eligible respondents, 22 completed all outcome items and 19 passed the attention check.
- **Sensitivity to exclusions:** including the three attention-check failures reduced the fairness difference to 0.279 (unadjusted p = 0.202). The attractiveness difference remained positive at 0.764 (unadjusted p = 0.007).
- **Order and interpretation:** differences were larger when the AI scenario came first. Only 12 of 19 participants correctly identified the reviewer in both scenarios. Contrast, carryover and comprehension may affect the estimates.
- **Hypothetical attitudes:** the study measured self-reported ratings, with no actual hiring, discrimination, application behaviour or business outcomes observed.

## Explore the work

- [Methods and sample flow](docs/methods.md)
- [Aggregate results](results/aggregate_results.csv)
- [Numerical checks and their limits](docs/validation.md)

This repository contains a portfolio summary and aggregate statistics. Respondent records, survey exports and questionnaire items are not distributed. The complete submitted PDF and original analysis script are not included. The original report remains unchanged privately; this summary uses the numerical checks documented above.

## Sources

The underlying coursework report is *Rejected by a Machine: Procedural Fairness and Organizational Attractiveness in AI-Mediated Versus Human-Mediated Job Rejection* (18 September 2026). Its submitted author list is Ahmad Sajjad Siddiqui, Ingrid Jacqueline De la Cruz Reyes, Ayush, and Syed Ahmed Abdul Quadeer. The contribution statement above describes my analysis and writing role.

Measurement sources are cited for attribution; their questionnaire text is not reproduced:

- Colquitt, J. A. (2001). On the dimensionality of organizational justice: A construct validation of a measure. *Journal of Applied Psychology, 86*(3), 386–400. [DOI](https://doi.org/10.1037/0021-9010.86.3.386).
- Highhouse, S., Lievens, F., & Sinar, E. F. (2003). Measuring attraction to organizations. *Educational and Psychological Measurement, 63*(6), 986–1001. [DOI](https://doi.org/10.1177/0013164403258403).
