---
title: 'Cross-Technology Localization: Leveraging Commodity WiFi to Localize Non-WiFi Device'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Rujun Zhang
  - Haizhou Guo
  - Peng Xiang
  - Xiaonan Guo


date: '2022-11-01'
doi: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *KSII Transactions on Internet & Information Systems*
publication_short: In *KSII TIIS*

abstract: Radio Frequency (RF)-based indoor localization technologies play significant roles in various Internet of Things (IoT) services (eg, location-based service). Most such technologies require that all the devices comply with a specified technology (eg, WiFi, ZigBee, and Bluetooth). However, this requirement limits its application scenarios in today's IoT context where multiple devices complied with different standards coexist in a shared environment. To bridge the gap, in this paper, we propose a cross-technology localization approach, which is able to localize target nodes using a different type of devices. Specifically, the proposed framework reuses the existing WiFi infrastructure without introducing additional cost to localize Non-WiFi device (ie, ZigBee). The key idea is to leverage the interference between devices that share the same operating frequency (eg, 2.4GHz). Such interference exhibits unique patterns that depend on the target device's location, thus it can be leveraged for cross-technology localization. The proposed framework uses Principal Components Analysis (PCA) to extract salient features of the received WiFi signals, and leverages Dynamic Time Warping (DTW), Gradient Boosting Regression Tree (GBRT) to improve the robustness of our system. We conduct experiments in real scenario and investigate the impact of different factors. Experimental results show that the average localization accuracy of our prototype can reach 1.54m, which demonstrates a promising direction of building cross-technology technologies to fulfill the needs of modern IoT context.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2021_KSII_Localization_wifi.pdf'

---
