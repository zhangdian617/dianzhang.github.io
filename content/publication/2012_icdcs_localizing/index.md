---
title: 'Localizing Multiple Objects in an RF-based Dynamic Environment'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xiaonan Guo
  - admin
  - Lionel M. Ni


date: '2012-06-18'
doi: '10.1109/ICDCS.2012.49'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# journal, conference
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Distributed Computing Systems*
publication_short: In *ICDCS*

abstract: 'Radio Frequency (RF) based technologies play an important role in indoor localization, since Radio Signal Strength (RSS) is easily achieved by various wireless devices without additional cost. Among these, radio map based technologies (also referred as fingerprinting technologies) are attractive. They are able to accurately localize the targets without introducing many reference nodes. Therefore, their hardware cost is low. However, this technology has two fatal limitations. First, it is hard to localize multiple objects, since radio map has to collect all the RSS information when targets are at different possible positions. But due to the multipath phenomenon, different number of target nodes at different positions often generates different multipath signals. So when the target object number is unknown, constructing a radio map of multiple objects is almost impossible. Second, environment changes will generate different multipath signals and severely disturb the RSS measurement, making laborious retraining inevitable. In this paper, we propose a novel method, called Line-Of-Sight (LOS) map matching. It leverages frequency diversity of wireless nodes to eliminate the multipath behavior, making RSS more reliable than before. These reliable RSS signals are able to construct the radio map, which only reserves the LOS signal among nodes. We call it LOS radio map. The number of objects and environment changes will not affect the LOS signal between the targets and reference nodes. Such map is able to be constructed easily and require no training if reference nodes are carefully redeployed. Our basic idea is to utilize the frequency diversity of each wireless node to transmit data in different spectrum channel. Then it solves the optimization problem to get the LOS signal. Our experiments are based on TelosB sensor platform with three reference nodes. It shows that the accuracy will not decrease when localizing multiple targets in a dynamic environment. It outperforms the traditional methods by about60%. More importantly, no calibration is required in such environment. Furthermore, our approach presents attractive flexibility, making it more appropriate for general RF-based localization studies than just the radio map based localization.'
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2012_icdcs_localizing.pdf'

---
