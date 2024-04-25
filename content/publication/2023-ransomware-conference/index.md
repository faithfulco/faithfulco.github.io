---
title: 'Enhancing ransomware classification with multi-stage feature selection and data imbalance correction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Anca Delia Jurcut
  - Liliana Pasquale

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2023-06-01T00:00:00Z'
doi: 'https://doi.org/10.1007/978-3-031-34671-2_20'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 7th International Symposium on Cyber Security, Cryptology, and Machine Learning
publication_short: CSCML

abstract: Ransomware is a critical security concern, and developing applications for ransomware detection is paramount. Machine learning models are helpful in detecting and classifying ransomware. However, the high dimensionality of ransomware datasets divided into various feature groups such as API calls, Directory, and Registry logs has made it difficult for researchers to create effective machine learning models. Class imbalance also leads to poor results when classifying ransomware families. To tackle these challenges, in this paper we propose a three-stage feature selection method that effectively reduces the dimensionality of the data and considers the varying importance of the different feature groups in the classification of ransomware families. We also applied costsensitive learning and re-sampling of the training data using SMOTE to address data imbalance. We applied these techniques to the Elderan ransomware dataset. Our results show that the proposed feature selection method significantly improves the detection of ransomware compared to other state-of-art studies using the same dataset. Furthermore, the data balancing techniques (cost-sensitive learning and SMOTE) were effective in the multi-class classification of ransomware.

# Summary. An optional shortened abstract.
summary: This paper proposed a three-stage feature selection method that effectively reduces the dimensionality of the data and considers the varying importance of the different feature groups in the classification of ransomware families. 

tags: 
- Machine Learning
- Ransomware
- Cybersecurity

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.researchgate.net/profile/Faithful-Onwuegbuche/publication/371743289_Enhancing_Ransomware_Classification_with_Multi-stage_Feature_Selection_and_Data_Imbalance_Correction/links/64fbfb923449310eb9b76a91/Enhancing-Ransomware-Classification-with-Multi-stage-Feature-Selection-and-Data-Imbalance-Correction.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**CSO**](https://www.csoonline.com/article/2094609/authentication-failure-blamed-for-change-healthcare-ransomware-attack.html)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
