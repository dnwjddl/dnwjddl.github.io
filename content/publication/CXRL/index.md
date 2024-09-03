---
title: 'Advancing Text-Driven Chest X-Ray Generation with Policy-Based Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Chanyoung Kim
  - Dayun Ju
  - Yumin Shim
  - Seong Jae Hwang

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-05-14T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-14T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Medical Image Computer Vision and Pattern Recognition (MICCAI'24 Early Accept & SPOTLIGHT)
publication_short: MICCAI 2024

abstract: Recent advances in text-conditioned image generation diffusion models have begun paving the way for new opportunities in modern medical domain, in particular, generating Chest X-rays (CXRs) from diagnostic reports. Nonetheless, to further drive the diffusion models to generate CXRs that faithfully reflect the complexity and diversity of real data, it has become evident that a nontrivial learning approach is needed. In light of this, we propose CXRL, a framework motivated by the potential of reinforcement learning (RL). Specifically, we integrate a policy gradient RL approach with well-designed multiple distinctive CXR-domain specific reward models. This approach guides the diffusion denoising trajectory, achieving precise CXR posture and pathological details. Here, considering the complex medical image environment, we present “RL with Comparative Feedback” (RLCF) for the reward mechanism, a human-like comparative evaluation that is known to be more effective and reliable in complex scenarios compared to direct evaluation. Our CXRL framework includes jointly optimizing learnable adaptive condition embeddings (ACE) and the image generator, enabling the model to produce more accurate and higher perceptual CXR quality. Our extensive evaluation of the MIMIC-CXR-JPG dataset demonstrates the effectiveness of our RL-based tuning approach. Consequently, our CXRL generates pathologically realistic CXRs, establishing a new standard for generating CXRs with high fidelity to real-world clinical scenarios.

# Summary. An optional shortened abstract.
summary: Early Accept & SPOTLIGHT (top 3.4% of submitted papers)

tags:
  - Medical Imaging
  - Text-to-Image Generation
  - Reinforcement Learning
  - Diffusion Model

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2403.06516'
url_code: 'https://github.com/MICV-yonsei/CXRL'
# url_dataset: ''
# url_poster: ''
url_project: 'https://micv-yonsei.github.io/cxrl2024/'
# url_slides: ''
url_source: 'https://micv-yonsei.github.io/cxrl2024/'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
