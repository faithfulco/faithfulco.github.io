---
title: "Value-at-Risk Measurement Incorporating Sentiments from Financial Tweets for Risk Analysis of Nigerian Banks"
authors:
- admin

author_notes:
- ""
- ""
date: "2019-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["thesis"]

# Publication name and optional abbreviated publication name.
publication: "An unpublished thesis submitted to the Department of Mathematics, Pan African University Institute for Basic Sciences, Technology and Innovation, Kenya for the degree of Master of Science in Financial Mathematics"
publication_short: ""

abstract: This study measured the value-at-risk (VaR) of five Nigerian banks using an innovative approach of incorporating sentiments from financial tweets. This is aimed at solving the problem of poor market-data-only VaR measurements, since market data alone may not reveal all the needed information of a financial institution. Four specific objectives guided the study, broadly to perform sentiment analysis, model volatility and measure VaR. Furthermore, the study proposed a framework for sentiment analysis of five Nigerian banks' tweets using Support Vector Machine. The Twitter data used for the study was crawled from Twitter API and spans 2 years, from 1st January 2017 to 31st December 2018. Also, stock market data for the five banks was obtained from the Nigerian Stock Exchange, covering the stated period. The sentiment analysis results reveal that the number of positive tweets within this period was slightly greater than the number of negative tweets for each of the five banks and the majority of the data falls between 0 and 100 sentiments per day, with few outliers above this range. The study also extended the Arbex-Valle et al. (2013) volatility model using news sentiments under the GJR-GARCH framework, to incorporate tweet sentiments under both the standard GARCH framework and the EGARCH framework. Modelling the volatility indicates that the EGARCH model with the t-distribution outperforms the standard GARCH model and the GJR-GARCH model. The parameters for both the positive and negative tweet sentiments that were incorporated into the model as external regressors, were significant. This shows that incorporating tweet sentiments in the modelling of volatility brought about a better model. Furthermore, the VaR was calculated using the variance-covariance approach. For the 5% 1-day and 1% 1-day VaR, the VaR without tweets sentiments were higher than the VaR with tweets sentiments, apart from that of UBA and ZENITHBANK. To the best of our knowledge, as suggested by the literature review, this is the first work that innovatively measures value-at-risk using both market data and social media (Twitter) data for Nigerian banks. Recommendations and suggestions for further studies were presented.

# Summary. An optional shortened abstract.
summary: This study measured the value-at-risk (VaR) of five Nigerian banks using an innovative approach of incorporating sentiments from financial tweets. 
tags:
- Machine Learning
- Finance
- FinTech
- Risk Analytics
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
