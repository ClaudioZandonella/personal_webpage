---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "PRDA package: Enhancing Statistical Inference via Prospective and Retrospective Design Analysis."
event: "useR! 2020"
event_url: "https://user2020.r-project.org/"
location:
address:
  street:
  city:
  region:
  postcode:
  country:
summary: "We introduce the PRDA (Prospective and Retrospective Design Analysis) R-package that allows researchers to perform a “Design Analysis” under different experimental scenarios (Altoè et al., 2020). Considering a plausible effect size (or its prior distribution), researchers can evaluate either the inferential risks for a given sample size or the required sample size to obtain a given statistical power. The main aim of PRDA package is to enhance researcher reasoning about inferential risks avoiding automated decisions."

abstract: "There is growing awareness about the importance of performing  power analysis to define an appropriate sample size when planning an experiment. However, statistical power is not the only relevant aspect of the study design.  Other related inferential risks, such as the probability of estimating the effect in the wrong direction (Type S [sign] error) or the average overestimation of the actual effect (Type M [magnitude] error), are also important. Statistical power, Type M and Type S errors can be evaluated in what Gelman and Carlin (2014) defined as Design Analysis, a process that may inform the planning stage of an experiment and the evaluation of studies’ results.

We introduce the PRDA (Prospective and Retrospective Design Analysis) R-package that allows researchers to perform a “Design Analysis” under different experimental scenarios (Altoè et al., 2020). Considering a plausible effect size (or its prior distribution), researchers can evaluate either the inferential risks for a given sample size or the required sample size to obtain a given statistical power. The main aim of PRDA package is to enhance researcher reasoning about inferential risks avoiding automated decisions.
Previously, PRDA functions were limited to mean differences between groups considering Cohen’s d in the Neyman-Pearson (N-P) framework. Now, we present the newly developed features that include other effect sizes (such as Pearson’s correlation) as well as Bayes Factor hypothesis testing. 

The PRDA R-package can be found at https://github.com/masspastore/PRDA.
"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-07-01T17:25:20+02:00
date_end: 2020-07-31T17:25:20+02:00
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2020-08-18T17:25:20+02:00

authors:
- admin
- Anna Vesely
- Angela Andreella
- Giulia Bertoldo
- Enrico Toffalini
- Gianmarco Altoè
- Massimiliano Pastore

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
    url: 'https://github.com/masspastore/PRDA' # qui mettere il link alla repository

# Optional filename of your slides within your talk's folder or a URL.
url_slides: https://drive.google.com/file/d/14dZZeqYc9pFOd2CXs6O3lvvYP8hUAxZA/view
url_poster:
url_code:
url_pdf: 
url_video: https://www.youtube.com/watch?v=IkCzuJei3_E&feature=youtu.be

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
