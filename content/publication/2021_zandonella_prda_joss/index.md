---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "PRDA: An R package for Prospective and Retrospective
Design Analysis"
authors:
- admin
- Giulia Bertoldo
- Enrico Toffalini
- Anna Vesely
- Angela Andreella
- Massimiliano Pastore
- Gianmarco Altoè
date: 2021-02-21
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-08-18T22:23:01+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Open Source Software"
publication_short: ""

abstract: "Design Analysis was introduced by Gelman & Carlin (2014) as an extension of Power Analysis.
Traditional power analysis has a narrow focus on statistical significance. Design analysis,
instead, evaluates together with power levels also other inferential risks (i.e., Type M error
and Type S error), to assess estimates uncertainty under hypothetical replications of a study.
Given an hypothetical value of effect size and study characteristics (i.e., sample size, statistical
test directionality, significance level), Type M error (Magnitude, also known as Exaggeration
Ratio) indicates the factor by which a statistically significant effect is on average exaggerated.
Type S error (Sign), instead, indicates the probability of finding a statistically significant result
in the opposite direction to the hypothetical effect.
Although Type M error and Type S error depend directly on power level, they underline
valuable information regarding estimates uncertainty that would otherwise be overlooked.
This enhances researchers awareness about the inferential risks related to their studies and
helps them in the interpretation of their results. However, design analysis is rarely applied in
real research settings also for the lack of dedicated software.
To know more about design analysis consider Gelman & Carlin (2014) and Lu et al. (2018).
While, for an introduction to design analysis with examples in psychology see Altoè et al.
(2020) and Bertoldo et al. (2020)."

# Summary. An optional shortened abstract.
summary: "PRDA allows performing a prospective or retrospective design analysis to evaluate inferential risks (i.e., power, Type M error, and Type S error) in a study considering Pearson’s correlation between two variables or mean comparisons (one-sample, paired, two-sample, and Welch’s t-test)."



tags: []
categories: []
featured: false
# Option to display content in the homepage (true/false)
show_homepage: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.theoj.org/joss-papers/joss.02810/10.21105.joss.02810.pdf
url_code: https://github.com/ClaudioZandonella/PRDA
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
