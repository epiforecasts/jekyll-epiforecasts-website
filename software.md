---
layout: page
title: Software
subtitle: R packages and other software developed by the group
---

### Real-time infection dynamcis and forecasting

[EpiNow2](http://epiforecasts.io/EpiNow2) estimates the time-varying reproduction number, rate of spread, and doubling time using a range of [open-source tools](https://wellcomeopenresearch.org/articles/5-112), and current [best practices](https://doi.org/10.1371/journal.pcbi.1008409).

### Covid-19 data

[covidregionaldata](https://github.com/epiforecasts/covidregionaldata) is an interface to subnational and national level COVID-19 data.

[covid19.nhs.data](https://epiforecasts.io/covid19.nhs.data/index.html) is an R package that contains a many-to-many mapping between local authority districts and NHS Acute Trusts in England.

### Forecast evaluation

[scoringutils](http://github.com/epiforecasts/scoringutils) is an R package to evaluate forecasts. It provides a collection of metrics and proper scoring rules that make it simple to score forecasts against the true observed values.

### Social contact patterns

[socialmixr](http://github.com/sbfnk/socialmixr) is an R package to estimate contact matrices from diary data such as collected in the [POLYMOD](http://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.0050074) study.

[epimixr](http://github.com/sbfnk/epimxir) is an R package to conduct epidemiological analysis using these contact matrices.

### Bayesian inference using state-space models with high-performance hardware

[rbi](https://cran.r-project.org/package=rbi) is an R interface to [LibBi](https://libbi.org), or Library for Bayesian Inference. It performs fast Bayesian inference with parallelised Sequential Monte Carlo, on CPUs or GPUs.

[rbi.helpers](http://github.com/sbfnk/rbi.helpers) is a supporting package for rbi, especially for constructing proposal distributions and determining the number of particles.
