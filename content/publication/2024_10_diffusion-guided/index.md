---
title: 'Diffusion-Guided Weakly Supervised Semantic Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sung-Hoon Yoon
  - Hoyong Kwon
  - Jaeseok Jeong
  - admin
  - Kuk-Jin Yoon

# Author notes (optional)
author_notes:
  - 'First author'
  - 'Second author'
  - 'Second author'
  - 'Second author'
  - 'Corresponding author'

date: '2024-10-1T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ECCV 2024
publication_short: 

abstract: Weakly Supervised Semantic Segmentation (WSSS) with image-level supervision typically uses Class Activation Maps to localize the object based on Convolutional Neural Networks (CNN). With limited receptive fields, CNN-based CAMs often fail to localize the whole object. The emergence of a Vision Transformer (ViT) alleviates the problem with superior performance, but the lack of locality in ViT introduces a new challenge. Inspired by the ability of Denoising Diffusion Probabilistic Models (DDPM) to capture high-level semantic information, we bring diffusion models to WSSS to resolve the problem. Firstly, to fuse and semantically align the information between DDPM and ViT, we design the Locality Fusion Cross Attention (LFCA) module. Using the aggregated features from the denoising process of the pretrained DDPM, LFCA generates CAMs (\ie Diffusion-CAMs) that provide locality information to CAMs from ViT (\ie ViT-CAMs). Secondly, by adding noise to the original image and denoising it with DDPM, we obtain a denoised image that can be leveraged as an augmented sample. To effectively guide ViT in excavating the relation between the patches, we devise the Patch Affinity Consistency (PAC) between the outputs of the original image and the denoised image. Extensive ablation studies support the superiority of the proposed method. Our method achieves new state-of-the-art performance on two widely used datasets in WSSS; PASCAL VOC 2012 and MS-COCO 2014.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Computer Vision
  - Deep Learning
  - Diffusion Model

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: ''
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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
