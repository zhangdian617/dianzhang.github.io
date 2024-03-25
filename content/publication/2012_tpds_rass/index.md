---
title: 'RASS: A Real-Time, Accurate, and Scalable System for Tracking Transceiver-Free Objects'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yunhuai Liu
  - Xiaonan Guo
  - Lionel M. Ni


date: '2012-06-01'
doi: '10.1109/TPDS.2012.134'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# journal, conference
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Parallel and Distributed Systems*
publication_short: In *TPDS*

abstract: 'Transceiver-free object tracking is to trace a moving object that does not carry any communication device in an environment with some monitoring nodes predeployed. Among all the tracking technologies, RF-based technology is an emerging research field facing many challenges. Although we proposed the original idea, until now there is no method achieving scalability without sacrificing latency and accuracy. In this paper, we put forward a real-time tracking system RASS, which can achieve this goal and is promising in the applications like the safeguard system. Our basic idea is to divide the tracking field into different areas, with adjacent areas using different communication channels. So, the interference among different areas can be prevented. For each area, three communicating nodes are deployed on the ceiling as a regular triangle to monitor this area. In each triangle area, we use a Support Vector Regression (SVR) model to locate the object. This model simulates the relationship between the signal dynamics caused by the object and the object position. It not only considers the ideal case of signal dynamics caused by the object, but also utilizes their irregular information. As a result, it can reach the tracking accuracy to around 1 m by just using three nodes in a triangle area with 4 m in each side. The experiments show that the tracking latency of the proposed RASS system is bounded by only about 0.26 m. Our system scales well to a large deployment field without sacrificing the latency and accuracy.'
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2012_tpds_rass.pdf'

---
