---
title: 'Privacy Preserving Federated Learning for Lung Cancer Classification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Md. Munawar Hossain

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2023 26th International Conference on Computer and Information Technology (ICCIT)
publication_short: In *ICW*

abstract: Lung cancer is characterized by high mortality and incidence rates, making it one of the most prevalent cancers globally. Early detection significantly improves the chances of survival for individuals affected by this disease. The histopathological diagnosis is a crucial factor in determining the specific type of cancer. In recent years, there has been a significant increase in novel computer-aided diagnostic techniques utilizing deep learning algorithms for the early detection of lung cancer. However, sharing sensitive patient data is significantly restricted by regulations such as HIPAA and GDPR, primarily due to privacy concerns. Given the current constraints, institutions face challenges in effectively exchanging information to enhance the accuracy of lung cancer classification. In order to address the issue of privacy in lung cancer classification, we propose a federated learning approach. This methodology involves employing local models with an Inception-v3 backbone to carry out the classification of histopathological images of lung cancer & updating the global model based on the local weights. These images have been obtained from the LC25000 dataset. The lung cancer images from the LC25000 dataset were analyzed, which consisted of three distinct classes. Each class contained a total of 5000 images. The applied model has achieved a classification accuracy of 99.867% in categorizing lung cancer images into three distinct classes. The performance of the proposed framework has demonstrated superiority over other existing methodologies. Furthermore, this solution effectively addresses the privacy concerns associated with the sharing of medical data among different institutions.

# Summary. An optional shortened abstract.
summary: Proposing federated learning for lung cancer classification to protect patient privacy.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder' 
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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
