---
title: 'MoCha: Large-Scale Driving Pattern Characterization for Usage-based Insurance'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhihan Fang
  - Guang Yang
  - admin
  - Guang Wang
  - Yu Yang
  - Fan Zhang
  - Desheng Zhang


date: '2021-08-14'
doi: 'https://doi.org/10.1145/3447548.3467114'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: In *ACM SIGKDD Conference on Knowledge Discovery & Data Mining*
publication_short: In *KDD*

abstract: Given widely adopted vehicle tracking technologies, usage-based insurance has been a rising market over the past few years. With potential discounts from insurance companies, customers voluntarily install sensing devices in their vehicles for insurance companies, which are utilized to analyze their historical driving patterns to derive the risks of future driving. However, it is challenging to characterize and predict driving patterns, especially for new users with limited data. To address this issue, we propose and evaluate a system called MoCha to accurately characterize driving patterns for usage-based insurance. The key question we aim to explore with MoCha is whether we can fully explore long-term driving patterns of new users with only limited historical data of themselves by leveraging abundant data of other users and contextual information. To answer this question, we design (i) a multi-level driving pattern modeling component to capture the spatial-temporal dependency on both individual and group level, and (ii) a multi-task learning method to utilize underlying relations of driving metrics and predict multiple driving metrics simultaneously. We implement and evaluate MoCha with real-world on-board diagnostics data from a large insurance company with more than 340,000 vehicles. Further, we validate the usefulness of MoCha by predicting driving risks based on real-world claim data in a Chinese city, Shenzhen.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2021_KDD_MoCha.pdf'
url_video: 'MoCha.mp4'

---
