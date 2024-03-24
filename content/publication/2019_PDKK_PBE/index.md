---
title: 'PBE: Driver Behavior Assessment Beyond Trajectory Profiling'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bing He
  - Xiaolin Chen
  - admin
  - Siyuan Liu
  - Dawei Han
  - Lionel M Ni


date: '2019-01-18'
doi: 'https://doi.org/10.1007/978-3-030-10997-4_31'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: 'In *Machine Learning and Knowledge Discovery in Databases: European Conference*'
publication_short: In *ECML PKDD*

abstract: Nowadays, the increasing car accidents ask for the better driver behavior analysis and risk assessment for travel safety, auto insurance pricing and smart city applications. Traditional approaches largely use GPS data to assess drivers. However, it is difficult to fine-grained assess the time-varying driving behaviors. In this paper, we employ the increasingly popular On-Board Diagnostic (OBD) equipment, which measures semantic-rich vehicle information, to extract detailed trajectory and behavior data for analysis. We propose PBE system, which consists of Trajectory Profiling Model (PM), Driver Behavior Model (BM) and Risk Evaluation Model (EM). PM profiles trajectories for reminding drivers of danger in real-time. The labeled trajectories can be utilized to boost the training of BM and EM for driver risk assessment when data is incomplete. BM evaluates the driving risk using fine-grained driving behaviors on a trajectory level. Its output incorporated with the time-varying pattern, is combined with the driver-level demographic information for the final driver risk assessment in EM. Meanwhile, the whole PBE system also considers the real-world cost-sensitive application scenarios. Extensive experiments on the real-world dataset demonstrate that the performance of PBE in risk assessment outperforms the traditional systems by at least 21%.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2019_PDKK_PBE.pdf'

---
