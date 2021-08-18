---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "trackdown: collaborative writing and editing your R Markdown and Sweave documents in Google Drive"
event_url: "https://user2021.r-project.org/"
location:
address:
  street:
  city:
  region:
  postcode:
  country:
summary: ""

abstract: "The advantages of using literate programming that combines plain-text and code chunks (e.g., R Markdown and Sweave) are well recognized. This allows the creation of rich, high quality, and reproducible documents. However, collaborative writing and editing have always been a bottleneck. Distributed version control systems like git are recommended for collaborative code editing but are far from ideal when working with prose. In the latter cases, other software (e.g, Microsoft Word or Google Docs) offer a more fluent experience, tracking document changes in a simple and intuitive way. When you further consider that collaborators often do not have the same level of programming competence, there does not appear to be an optimal collaborative workflow for writing reproducible documents.

trackdown (formerly rmdrive) overcomes this issue by offering a simple solution to collaborative writing and editing of reproducible documents. Using trackdown, the local R Markdown or Sweave document is uploaded as plain-text in Google Drive allowing other colleagues to contribute to the prose using convenient features like tracking changes and comments. After integrating all authors’ contributions, the edited document is downloaded and rendered locally. This smooth workflow allows taking advantage of the easily readable Markdown and LaTeX plain-text combined with the optimal and well-known text editing experience offered by Google Docs.

In this contribution, we will present the package and its main features. trackdown aims to promote good scientific practices that enhance overall work quality and reproducibility allowing collaborators with no or limited R knowledge to contribute to literate programming workflows.
"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-07-05T17:25:20+02:00
date_end: 2021-07-09T17:25:20+02:00
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2020-08-18T17:25:20+02:00

authors:
- Filippo Gambarota
- admin
- Janosch Linkersdörfer
- Mathew Ling
- Emily Kothe

# Select one tag between Talk and Poster
tags: [Talk]

# Talk or Poster type.
# Legend: 0 = Uncategorized; 1 = Talk; 2 = Poster
talk_poster_types:
- "1"

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

links:
  - icon_pack: fab
    icon: github
    name: Github Repository
    url: 'https://github.com/claudiozandonella/trackdown' # qui mettere il link alla repository

# Optional filename of your slides within your talk's folder or a URL.
url_slides: 
url_poster:
url_code:
url_pdf: 
url_video: https://www.youtube.com/watch?v=hXhLGzn6S60

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
