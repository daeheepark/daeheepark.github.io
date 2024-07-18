---
title: "Identifying Reflected Images From Object Detector in Indoor Environment Utilizing Depth Information"
authors:
- admin
- Yong-Hwa Park
author_notes:
- "First author"
- "Corresponding author"
date: "2020-12-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal", "paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Robotics and Automation Letters and ICRA 2021"
publication_short: ""

abstract: We observed that mirror reflection severely degrades person detection performance in an indoor environment, which is an essential task for service robots. To address this problem, we propose a new real-time method to identify reflected virtual images in an indoor environment utilizing 3D depth information. Images reflected by the mirror are similar to real objects, so it is a non-trivial task to differentiate them. Conventional object detectors, which do not deal with this problem, obviously recognize reflected images as real objects. The proposed method compares the geometric relationship between the 3D spatial information of the detected object and its surrounding environment where the object locates. It analyzes the layout of surrounding indoor space utilizing semantic segmentation and plane detection method. With the estimated layout of indoor space, detected object candidates are examined whether they are real or reflected images utilizing 3D depth information. To verify the proposed method, a large indoor dataset was newly acquired and examined in a dedicated Living-lab environment. The performance of the algorithm is verified by comparing conventional detectors with the proposed method in the acquired Living-lab dataset.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9310333
url_code: https://github.com/ai4r/AIR-HumanDetector
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

{{% callout note %}}
Click the *Cite* button above to import publication metadata into reference management.
{{% /callout %}}

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
