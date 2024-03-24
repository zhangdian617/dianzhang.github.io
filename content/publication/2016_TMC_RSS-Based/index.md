---
title: 'RSS-Based Ranging by Leveraging Frequency Diversity to Distinguish the Multiple Radio Paths'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yunhuai Liu
  - admin
  - Xiaonan Guo
  - Min Gao
  - Zhong Ming
  - Lei Yang
  - Lionel M Ni


date: '2016-06-09'
doi: '10.1109/TMC.2016.2579619'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# journal, conference
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Mobile Computing*
publication_short: In *TMC*

abstract: Among various ranging techniques, Radio Signal Strength (RSS) based approaches attract intensive research interests because of its low cost and wide applicability. RSS-based ranging is prone to be affected by the multipath phenomenon which allows the radio signals to reach the destination through multiple propagation paths. To address this issue, previous works try to profile the environment and refer this profile during run-time. In a practical dynamic environment, however, the profile frequently changes and the painful retraining is needed. Ratherthan such static ways of profiling the environments, in this paper, we tryto accommodate the environmental dynamics automatically in real-time. The key observation is that given a pair of nodes, the RSS at different spectrum channels will be different. This difference carries the valuable phase information of the radio signals. By analyzing these RSS values, we are able to identify the amplitude of signals solely from the Line-of-Sight (LOS) path. This LOS amplitude is a simple function of the path length (the physical distance). We find that the analysis is a typical non-linear curvature fitting problem that has no general routing algorithms. We prove that, this problem format is ill-conditioned which has no stable and trustable solutions. To deal with this issue, we further explore the practical considerations for the problem and modify it to a greatly improved conditioning shape. We solve the problem by numerical iterations and implement these ideas in a real-time indoor tracking system called MuD. MuD employs only three TelosB nodes as anchors. The experiment results show that in a dynamic environment where five people move around, the averaged localization error is about 1 meter. Compared with the traditional RSS-based approaches in dynamic environments, the accuracy improves up to 10 times.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2016_TMC_RSS-Based.pdf'

---
