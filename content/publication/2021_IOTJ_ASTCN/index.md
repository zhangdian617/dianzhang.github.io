---
title: 'ASTCN: An Attentive Spatial–Temporal Convolutional Network for Flow Prediction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Haizhou Guo
  - admin
  - Landu Jiang
  - Kin-Wang Poon
  - Kezhong Lu


date: '2021-08-10'
doi: '10.1109/JIOT.2021.3100068'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Internet of Things Journal*
publication_short: In *IOTJ*

abstract: Flow prediction attracts intensive research interests, since it can offer essential support to many crucial problems in public safety and smart city, e.g., epidemic spread prediction and medical resource allocation optimization. Among all the models in flow prediction, deep learning models (e.g., convolutional neural networks, recurrent neural networks, and graph neural networks) are popular and outperform other statistics and machine learning models, since they can learn intrinsic structures and extract features from spatial–temporal (ST) data. However, most of them set strict temporal periods in the prediction or separate the interaction between spatial and temporal correlations. Therefore, the prediction accuracy is affected. To overcome the difficulties, we propose a flow prediction network attentive spatial–temporal convolutional network (ASTCN), which can effectively handle large-scale flow data and learn complex features. In ASTCN, we leverage an attention mechanism to overcome the previous problem of strict temporal periods, and can effectively fuse ST data with multiple factors from different time-series sources. Furthermore, we propose a causal 3-D convolutional layer based on temporal convolutional networks (TCNs). It can simultaneously extract both spatial and temporal features to improve the prediction accuracy. We comprehensively conducted our experiments based on real-world data sets. Experimental results show that ASTCN outperforms the state-of-the-art methods by at least 3.78% in root mean square error. Therefore, ASTCN is a potential solution to other large-scale ST problems.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2021_IOTJ_ASTCN.pdf'

---
