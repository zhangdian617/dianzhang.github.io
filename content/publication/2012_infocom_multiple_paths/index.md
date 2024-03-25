---
title: 'On Distinguishing the Multiple Radio Paths in RSS-based Ranging'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yunhuai Liu
  - Xiaonan Guo
  - Min Gao
  - Lionel M. Ni

date: '2012-06-10'
doi: '10.1109/INFCOM.2012.6195605'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# journal, conference
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE INFOCOM*
publication_short: In *INFOCOM*

abstract: 'Among the various ranging techniques, Radio Signal Strength (RSS) based approaches attract intensive research interests because of its low cost and wide applicability. RSS-based ranging is apt to be affected by the multipath phenomenon which allows the radio signals to reach the destination through multiple propagation paths. To address this issue, previous works try to profile the environment and refer this profile in run-time. In practical dynamic environments, however, the profile frequently changes and the painful retraining is needed. Rather than such static ways of profiling the environments, in this paper, we try to accommodate the environmental dynamics automatically in real-time. The key observation is that given a pair of nodes, the RSS at different spectrum channels will be different. This difference carries the valuable phase information of the radio signals. By analyzing these RSS values, we are able to identify the amplitude of signals solely from the Line-of-Sight (LOS) path. This LOS amplitude is a simple function of the path length (the physical distance). We find that the analysis is a typical non-linear curvature fitting problem that has no general routing algorithms. We prove this problem format is ill-conditioned which has no stable and trustable solutions. To deal with this issue, we further explore the practical considerations for the problem and reform it to a greatly improved conditioning shape. We solve the problem by numerical iterations and implement these ideas in a real-time indoor tracking system called MuD. MuD employs only three TelosB nodes as anchors. The experiment results show that in a dynamic environment where five people move around, the averaged localization error is 1 meter. Compared with the traditional RSS-based approaches in dynamic environment, the accuracy improves up to 10 times.'
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2012_infocom_multiple_paths.pdf'

---
