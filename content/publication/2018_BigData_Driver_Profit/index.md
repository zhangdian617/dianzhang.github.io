---
title: 'Profiling Driver Behavior for Personalized Insurance Pricing and Maximal Profit'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bing He
  - admin
  - Siyuan Liu
  - Hao Liu
  - Dawei Han
  - Lionel M Ni


date: '2018-12-10'
doi: '10.1109/BigData.2018.8622491'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Big Data*
publication_short: In *Big Data*

abstract: Profiling driver behaviors and designing appropriate pricing models are essential for auto insurance companies to gain profits and attract customers (drivers). The existing approaches either rely on static demographic information like age, or model only coarse-grained driving behaviors. They are therefore ineffective to yield accurate risk predictions over time for appropriate pricing, resulting in profit decline or even financial loss. Moreover, existing pricing strategies seldom take profit maximization into consideration, especially under the enterprise constraints. The recent growth of vehicle telematics data (vehicle sensing data) brings new opportunities to auto insurance industry, because of its sheer size and fine-grained mobility for profiling drivers. But, how to fuse these sparse, inconsistent and heterogeneous data is still not well addressed. To tackle these problems, we propose a unified PPP (Profile-Price-Profit) framework, working on the real-world large-scale vehicle telematics data and insurance data. PPP profiles drivers' fine-grained behaviors by considering various driving features from the trajectory perspective. Then, to predict drivers' risk probabilities, PPP leverages the group-level insight and categorizes drivers' different temporal risk change patterns into groups by ensemble learning. Next, the pricing model in PPP incorporates both the demographic analysis and the mobility factors of driving risk and mileage, to generate personalized insurance price for supporting flexible premium periods. Finally, the maximal profit problem proves to be NP-Complete. Then, an efficient heuristic-based dynamic programming is proposed. Extensive experimental results demonstrated that, PPP effectively predicts the driver's risk and outperforms the current company's pricing strategy (in industry) and the state-of-the-art approach. PPP also achieves near the maximal profit (difference by only 3%) for the company, and lowers the total price for the drivers.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2018_BigData_Driver_Profit.pdf'

---
