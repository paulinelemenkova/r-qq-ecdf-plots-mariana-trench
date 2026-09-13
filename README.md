# R QQ, ECDF and Facet-Wrapped Statistics — Mariana Trench Depths

R scripts producing distributional-statistics plots for the 25 bathymetric profiles of the Mariana Trench: theoretical-versus-sample quantile (Q-Q) plots and the empirical cumulative distribution function (ECDF), arranged as a facet-wrapped small-multiples panel.

## Related publication

Lemenkova, P. Statistical Analysis of the Mariana Trench Geomorphology Using R
Programming Language. Geodesy and Cartography 2019, 45(2), 57-84.

- DOI: https://doi.org/10.3846/gac.2019.3785
- figshare: https://doi.org/10.6084/m9.figshare.9762860
- HAL: https://hal.science/hal-02277500
- Zenodo: https://zenodo.org/record/3385005
- ISSN: 2029-6991 (Scopus)

These scripts produced Figure 6 (quantile statistics / ECDF).

## Scripts

- QQ_facetwrapMD.R: facet-wrapped normal Q-Q plots of the depth distribution for each profile (ggplot2 stat_qq / facet_wrap).

- QQ_25profiles.R: the per-profile Q-Q set; ecdf.r: the empirical cumulative distribution function; QQ_t_test-basic.r: a basic Q-Q with t-test.

## Methods

- Q-Q comparison against a theoretical (normal) distribution; empirical CDF; small-multiples faceting.

## Data

- Depths.csv: depths along 25 Mariana Trench cross-section profiles.

## Requirements

- R (>= 3.5); packages: ggplot2

## Author and citation

Polina Lemenkova — ORCID https://orcid.org/0000-0002-5759-1089

Cite: Lemenkova, P. Statistical Analysis of the Mariana Trench Geomorphology Using R Programming Language. Geodesy and Cartography 2019, 45(2), 57-84. https://doi.org/10.3846/gac.2019.3785

## License

MIT — see LICENSE (Copyright Polina Lemenkova).
