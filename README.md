# PRELUDE

**P**redicting **R**ecurrence in **E**arly **LU**ng a**DE**nocarcinoma. A multi-center research consortium pairing whole-slide histology with omics to predict relapse in stage IA / IB lung adenocarcinoma.

This repository hosts the consortium's landing page.

## About

Predicting relapse in stage I lung adenocarcinoma is no longer a technology problem. It is a coordination problem. Foundation pathology models have arrived. Transcriptomic profiling is routine. The math fuses cleanly across modalities. What is missing is scale.

The world's stage IA / IB lung adenocarcinoma WSIs and matched omics sit in institutional silos of 50, 100, 200 cases. No single cohort, however carefully curated, reaches the levels required for clinical translation. Pooled, they do.

PRELUDE is a community effort. Federated by design, contributor-built, contributor-credited. Member sites retain custody of their data. Their names go on the paper. Joined, we move the needle. Alone, we don't.

The pilot study, **PATH-ORACLE** (medRxiv, 2026), trained a foundation-model-based predictor on 272 stage IA/IB cases from TCGA-LUAD and validated across CPTAC, TRACERx, and KORANYI, achieving a pooled C-index of 0.70 vs. 0.63 for whole-slide imaging alone. The signal is real. n=272 is not.

## Founding institutions

- Boston Children's Hospital
- Massachusetts General Hospital
- The Francis Crick Institute

## The ask

Member sites contribute curated cohorts of resected stage IA / IB lung adenocarcinoma cases:

1. Whole-slide images (H&E, 20× or 40×)
2. Matched omics (bulk transcriptomics preferred; WES, methylation, proteomics welcomed)
3. Outcome data (recurrence status with date, plus core clinicopathologic variables)
4. A scientific lead (pathologist, oncologist, or PI willing to co-author)

Near-term milestone: **5,000 cases**.

## Contact

Express interest at **join@prelude-consortium.org**

## Pilot preprint

Kilim O., Pipek O., Sztupinszki Z., Diossy M., Prosz A., Naceur-Lombardelli C., Veeriah S., Moore D., Jamal-Hanjani M., Hackshaw A., Fillinger J., Moldvay J., Csabai I., Swanton C., Szallasi Z. *A multimodal AI biomarker PATH-ORACLE improves prediction of recurrence in stage I lung adenocarcinoma*. medRxiv, 2026. https://www.medrxiv.org/content/10.64898/2026.01.28.26344973v3

## Local development

This is a single static HTML file. To preview:

```bash
# Option 1: open directly
open index.html

# Option 2: serve locally
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Drop `index.html` into any static host (Vercel, Netlify, GitHub Pages, Cloudflare Pages). No build step required.

To enable GitHub Pages: repository **Settings → Pages → Branch: main → /(root) → Save**.

## License

© 2026 PRELUDE Consortium. All rights reserved.
