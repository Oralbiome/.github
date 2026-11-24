# Oralbiome

Research on whether oral-microbiome models of diabetes status hold up when the study changes.

> Working manuscript, not peer reviewed; no clinical use.

## Current study

**Oral Microbiome Models of Diabetes Status: A Retrospective Audit of Cross-Study Transfer**
Jonathan Scarpelli and Ayesha Akhter

A retrospective audit of diabetes-status prediction from oral-microbiome profiles: six source studies,
10,228 oral specimens, and external benchmarks from other studies.

- **Transfer.** In the four exploratory external benchmarks reported with intervals, every 95% interval for
  transfer AUC includes chance (0.5).
- **Age and sex.** Within NHANES, where diabetes is self-reported, age and sex alone reach AUC 0.803; the
  microbiome alone reaches 0.698. Adding the microbiome to age and sex shows no evidence of a gain under the
  tested learner (preregistered baseline).

The external benchmarks informed development, so these are not untouched test sets. No screening tool,
validated biomarker panel or clinical claim is established.

## Status (2026-11-24)

- **Paper:** working manuscript, revised 2026-11-22. Not peer reviewed.
- **Reanalysis:** registered on OSF on 2026-11-19, before any outcome-bearing fit. Exact transfer values depend
  on how genera absent from a cohort are encoded; the reanalysis addresses that. It has not yet produced results.
- **Version history:** every correction and every analysis set aside during the audit is listed at
  [oralbiome.scarpelli.ai/corrections](https://oralbiome.scarpelli.ai/corrections).

## Links

| | |
|---|---|
| Website | <https://oralbiome.scarpelli.ai> |
| Paper | <https://oralbiome.scarpelli.ai/preprint> |
| Code | <https://github.com/Oralbiome/oral-microbiome-transfer> |
| Registration | <https://osf.io/6k82q/> (DOI [10.17605/OSF.IO/6K82Q](https://doi.org/10.17605/OSF.IO/6K82Q)) |

Questions and reports: open an issue in the
[code repository](https://github.com/Oralbiome/oral-microbiome-transfer/issues).
