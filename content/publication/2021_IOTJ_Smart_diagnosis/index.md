---
title: 'Smart diagnosis: Deep learning boosted driver inattention detection and abnormal driving prediction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Landu Jiang
  - Wen Xie
  - admin
  - Tao Gu


date: '2021-08-10'
doi: '10.1109/JIOT.2021.3103852'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Internet of Things Journal*
publication_short: In *IOTJ*

abstract: Inattentive driving is one of the high-risk factors that causes a large number of traffic accidents every year. In this article, we aim to detect driver inattention leveraging on large-scale vehicle trajectory data while at the same time explore how do these inattentive events affect driver behaviors and what following reactions they may cause, especially, for commercial vehicles. Specifically, the proposed system targets four most commonly occurring critical inattentive events, including smoking, phone call, turning back, and yawning. By applying a deep convolutional neural network (CNN) (Inception v3) with two data augmentation routines—Mixup and synthetic minority oversampling technique (Smote), we are able to balance the training data distribution and improve the generalization of the classification model. Then, based on the output derived from the inattention detection combining with point of interest (POI) and climate data, a long short-term memory (LSTM)-based model is deployed to predict driver upcoming abnormal operations on road (due to inattention) which may result in potential dangerous driving conditions, such as sudden acceleration/deceleration, aggressive left/right lane change, etc. To evaluate our proposed system, we collect more than 120000 real-world driving traces from over 200 drivers. The experimental results show that our model achieves a weight accuracy (WA) of 92.27% for inattentive driving detection and a WA of 91.67% for abnormal driving prediction, demonstrating its great potential of shaping good driving habits and promoting road safety.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2021_IOTJ_Smart_diagnosis'

---
