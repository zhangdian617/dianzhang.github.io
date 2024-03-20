---
title: 'Leveraging statistical information in fine-grained financial sentiment analysis

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Han Zhang
  - Zongxi Li
  - Haoran Xie
  - Raymond YK Lau
  - Gary Cheng
  - Qing Li
  - Dian Zhang


date: '2022-02-05'
doi: 'https://doi.org/10.1007/s11280-021-00993-1'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *World Wide Web*
publication_short: In *WWW*

abstract: The recent development of deep learning-based natural language processing (NLP) methods has fostered many downstream applications in various fields. As one of the applications in the financial industry, fine-grained financial sentiment analysis (FSA) aims to understand the sentimental orientation, i.e., bullish or bearish, of financial texts by predicting the polarity score and has been widely applied in the financial industry stock-related opinion mining. Because of the lack of a large-scale labeled dataset and the domain-dependent nature, FSA is challenging. Previous works mainly focus on constructing and exploiting handcrafted lexicons that encode expert knowledge to enhance the semantic features in decision making, which yields improvements but are expensive to acquire. This paper proposes a lightweight regression model incorporating the statistical distribution of a term over the polarity range, say between − 1 and 1, to address the fine-grained FSA task. More concretely, we first count each word’s appearance at different polarity intervals and produce a statistic-based representation for each text, which will be encoded as a corpus-level statistical feature vector by an autoencoder. Subsequently, the obtained feature vector will be integrated with the semantic feature vector in the regression model. Our experiments show such a model can produce significant improvements compared with the baseline models on two FSA subsets, i.e., news headlines and microblogs, without a computational overhead. Furthermore, we notice the signs that lexicon-based approaches have neglected can play an important role in FSA.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2022_WWW_financial_sentiment.pdf'
---
