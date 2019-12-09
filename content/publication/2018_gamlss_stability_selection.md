+++
abstract = "We present a new algorithm for boosting generalized additive models for location, scale and shape (GAMLSS) that allows to incorporate stability selection, an increasingly popular way to obtain stable sets of covariates while controlling the per-family error rate. The model is fitted repeatedly to subsampled data, and variables with high selection frequencies are extracted. To apply stability selection to boosted GAMLSS, we develop a new “noncyclical” fitting algorithm that incorporates an additional selection step of the best-fitting distribution parameter in each iteration. This new algorithm has the additional advantage that optimizing the tuning parameters of boosting is reduced from a multi-dimensional to a one-dimensional problem with vastly decreased complexity. The performance of the novel algorithm is evaluated in an extensive simulation study. We apply this new algorithm to a study to estimate abundance of common eider in Massachusetts, USA, featuring excess zeros, overdispersion, nonlinearity and spatiotemporal structures. Eider abundance is estimated via boosted GAMLSS, allowing both mean and overdispersion to be regressed on covariates. Stability selection is used to obtain a sparse set of stable predictors."

authors = ["Thomas, J.", "A. Mayr", "B. Bischl", "M. Schmid", "A.D. Smith", "B. Hofner"]
date = "2018-05-01"
image_preview = ""
math = true
publication_types = ["2"]
publication = "*Statistics and Computing* 28:673-687"
publication_short = ""
selected = false
title = "Gradient boosting for distributional regression: faster tuning and improved variable selection via noncyclical updates"
url_code = "https://github.com/ja-thomas/gamboostLSS_stabsel_paper"
url_dataset = ""
url_pdf = "papers/2018_gamlss_stability_selection.pdf"
url_project = ""
url_slides = ""
url_video = ""

[[url_custom]]
name = "View Journal Article"
url = "https://link.springer.com/article/10.1007%2Fs11222-017-9754-6"

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++