---
title: 'Double Free Measurement-Free Localization for Transceiver-Free Object'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xiaoyan Jiang
  - Lionel M. Ni


date: '2014-12-15'
doi: '10.1109/ICPP.2014.62'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# journal, conference
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Parallel Processing*
publication_short: In *ICPP*

abstract: 'Transceiver-free object localization is essential for emerging location-based service, e.g., the safe guard system and asset security. It can track indoor target without carrying any device and has attracted many research effort. Among these technologies, Radio Signal Strength (RSS) based approaches are very popular because of their low-cost and wide applicability. In such work, usually a large number of reference nodes have to be deployed. However, if in a very large area, many labor work to measure the positions of the reference nodes have to be performed, result in not practical in real scenario. In this paper, we propose Double Free, which can accurately track transceiver-free object without measuring the positions of the reference nodes. Users may randomly deploy nodes in a 2D area, e.g., the ceiling of the floor. Our Double Free contains two steps: reference node localization and target localization. The key to achieve the first step is to utilize the RSS difference in different channel to distinguish the Line-Of-Sight (LOS) signal from combined multiple paths' signal. Thus, the reference nodes can be accurately localized without additional hardware. In the second step, we propose two algorithms: Influential Link & Node (ILN) and MultiPath Distinguishing (MD). ILN is simple to implement, while MD can accurately model the additional signal caused by the target, then accurately localize the target. To implement this idea, 16 TelosB nodes are placed randomly in a 25×10m 2 laboratory. The experiment results show, the average localization error is only round 2 meters without requiring to measure the positions of reference nodes in advance. It shows enormous potential in those localization areas, where manual measurement is hard to perform, or hard labor work want to be saved.'
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2014_ICPP_Double_Free.pdf'

---
