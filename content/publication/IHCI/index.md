---
title: "Effect of Time Window Size for Converting Frequency Domain in Real-Time Remote Photoplethysmography Extraction"
authors:
- Yu Jin Shin
- admin
- Kun Ha Suh
- Eui Chul Lee

date: "2021-03-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-conference"]

# Publication name and optional abbreviated publication name.
publication: "Intelligent Human Computer Interaction (IHCI)"
publication_short: "IHCI 2021"

abstract: Remote-photoplethysmography (rPPG) is an attractive technology that can measure vital signs at a distance without contact. Previous remote-photoplethysmography studies focused mainly on eliminating the artifact such as motion but finding the optimal setup or hyperparameters are also an important factor influencing the performance. As one of them, window size is the length of the signal used to calculate the vital signs once in a spectral method and has not been analyzed in detail in previous works. In general, the use of a long window size increases the re-liability of the estimations, but it cannot reflect continuously changing physiological responses of human. Also, using too short window size increases uncertainty. In this paper, we compare and analyze the pulse rate estimation results according to window sizes from short to long using CHROM, which is one of the popular rPPG algorithms. Results on the PURE dataset showed that the longer the window size, the higher the SNR and the lower the RMSE. At a window size of about 4 s (120 frames), the SNR was switched from negative to positive and an acceptable error rate (RMSE < 5) was observed.

# Summary. An optional shortened abstract.
summary: IHCI 2021

tags:
- rPPG


featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://link.springer.com/chapter/10.1007/978-3-030-98404-5_14
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
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
slides: example
---
