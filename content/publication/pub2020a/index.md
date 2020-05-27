---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Exploring Latent Class Structures in Classification-By-Components Networks"
authors: ["Lars Holdijk"]
date: 2020-05-26:00:00+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-05-26T16:18:32+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: "CVPR workshop on Compositionality in Computer Vision"
publication_short: "CICV2020"

abstract: "A Classification-by-Components network (CBC) operates under the assumption that every input image can be classified based on its decomposition into a set of components. An important characteristic of these components is that they can be used in the decomposition of images from different classes. The components are class independent. In this work, we discuss the latent class structure encoded in the sharing of components between classes. We propose to visualize this structure using a Shared Component Graph (SCG). Consecutively we discuss the insight into the decision making process of a CBC the visualization can provide."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter
links:
 - name: Workshop paper
   url: "publication/pub2020a/paper.pdf"
   icon_pack: fas
   icon: file-pdf
 - name: Graph ImageNet
   url: "scg/imagenet.html"
   icon_pack: fas
   icon: project-diagram
 - name: Graph CUB
   url: "scg/bird.html"
   icon_pack: fas
   icon: project-diagram
 - name: Slides
   url: "scg/slides.pdf"
   icon_pack: fas
   icon: file-pdf

url_pdf: 
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""
---
{{<video library="1" src="scg-video.mp4" controls="yes">}}