---
layout: page
title: Graduate earnings across institutions and programs
description: College Scorecard and IPEDS merged to test whether program scale predicts post-graduation earnings, benchmarked on UCLA.
img: assets/img/projects/graduate-earnings-comparison.png
importance: 4
category: coursework
---

How do UCLA graduates compare to peers from other institutions across degree types, fields of study, and institutional characteristics? The project asks two questions: how UCLA's program sizes compare to peer institutions, and whether program scale affects post-graduation earnings.

Group project with Abdul Bholat, Albert Carreno, Andrew Darwin, Anish Deshpande, and Caleb Williams.

## Approach

- Merged and filtered College Scorecard and IPEDS data for recent, complete institution- and program-level records
- Imputed missing values by linear regression for small gaps and K-nearest neighbors for categorical variables
- Clustered institutions on control type, graduation rate, size, and selectivity to identify UCLA's peer group
- Regressed median earnings on program scale, controlling for institution type and field of study

## Result

Scale is positively but weakly associated with earnings in Business and Computer Science (p &lt; 0.05), and not in Engineering or Social Sciences (p &gt; 0.1) — statistically significant only in some contexts. The main obstacle was missing or inconsistent program-level earnings reporting, especially at smaller institutions and in niche programs. Planned next steps: cost-of-living adjustment for geographic wage differences, and interaction terms to capture nonlinear scale effects.

## Materials

- [Slides (PDF)](https://github.com/narenp12/my_work/blob/main/Undergraduate/Graduate_Earnings_Comparison/Graduate_Earnings_Comparison_Slides.pdf)
