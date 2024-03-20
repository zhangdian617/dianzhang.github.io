---
title: 'FGRL-Net: Fine-Grained Personalized Patient Representation Learning for Clinical Risk Prediction Based on EHRs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - KaKit Chio
  - Wenhao Zhu
  - Lihua He
  - admin
  - Xu Yang
  - Wuman Luo

date: '2023-10-04'
doi: '10.1109/SMC53992.2023.10393910'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE International Conference on Systems, Man, and Cybernetics*
publication_short: In *SMC*

abstract: Personalized patient representation learning (PPRL) is a critical element in clinical risk prediction. It aims to obtain a complete portrait of each patient based on Electronic Health Records (EHR). Although existing works have achieved remarkable progress in healthcare prediction, there are still three major issues. First, feature correlation is crucial for risk prediction, but it has not yet been fully exploited by existing works. Second, variation pattern of dynamic feature contains useful information about patient's physical status, but adaptive pattern recognition is still a challenge. Third, existing works usually adopt a two-stage embedding process to process each dimension of the EHR data. However, some useful low-level information for PPRL will be lost. To address these issues, in this paper, we propose a fine-grained PPRL architecture named FG RL- N et for clinical risk prediction based on EHR. Specifically, we propose a Medical Feature Correlation Detection Module (FCM) to effectively learn the feature correlations for each patient and a Temporal Variation Pattern Recognition Module (TVM) to effectively detect the variation patterns of each dynamic feature. Moreover, we design a Fine-Grained Representation Mechanism (FGRM) to preserve the low-level information (from both feature and visit dimensions) useful for risk prediction. In addition, in the stage of data preprocessing, We utilize generic medical classification knowledge to classify numerical dynamic data. We conduct the in-hospital mortality experiment and the decompensation experiment on a real-world dataset. The experiment results show that the FGRL-Net outperforms state-of-the-art approaches.


# Display this page in the Featured widget?
featured: true

url_pdf: '2023_SMC_FGRL-Net.pdf'
url_source: 'https://github.com/JackyChio/FGRL-Net'

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

---


{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
