---
title: 'A fast algorithm to estimate inverse consistent image transformation based on corresponding landmarks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xuan Yang
  - admin
  - Shuiyong Yao
  - Bo Wang

date: '2015-10-01'
doi: 'https://doi.org/10.1016/j.compmedimag.2015.04.003'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# journal, conference
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *Computerized Medical Imaging and Graphics*
publication_short: In *CMIG*

abstract: Inverse consistency is an important feature for non-rigid image transformation in medical imaging analysis. In this paper, a simple and efficient inverse consistent image transformation estimation algorithm is proposed to preserve correspondence of landmarks and accelerate convergence. The proposed algorithm estimates both the forward and backward transformations simultaneously in the way that they are inverse to each other based on the correspondence of landmarks. Instead of computing the inverse functions and the inverse consistent transformations, respectively, we combine them together, which can improve computation efficiency significantly. Moreover, radial basis functions (RBFs) based transformation is adopted in our algorithm, which can handle deformation with local or global support. Our algorithm maps one landmark to its corresponding position exactly using the forward and backward transformations. Moreover, our algorithm is employed to estimate the forward and backward transformations in robust point matching, as well to demonstrate the application of our algorithm in image registration. The experiment results of uniform grids and test images indicate the improvement of the proposed algorithm in the aspect of inverse consistency of transformations and the reduction of the computation time of the forward and the backward transformations. The performance of our algorithm applying to robust point matching is evaluated using both brain slices and lung slices. Our experiments show that by combing robust point matching with our algorithm, the registration accuracy can be improved and the smoothness of transformations can be preserved.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2015_CMIG_Image_Landmarks.pdf'

---
