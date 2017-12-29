+++
title = "The Blended Paradigm: Robust Bayesian Modeling using Non-Sufficient Statistics"
date = 2014-04-08T15:27:29-07:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2014-04-08T15:27:29-07:00
time_end = 2014-04-08T15:27:29-07:00

# Abstract and optional shortened version.
abstract = "Bayesian methods have proven themselves to be enormously successful across a wide range of scientific problems, with analyses ranging from the simple one-sample problem to complicated hierarchical models. However, Bayesian methods run into difficulties for two major and prevalent classes of problems: handling data sets with outliers and dealing with model misspecification. This research is focused on the development and implementation of a new method to handle both of these problems. In particular, we propose the use of what we call *restricted likelihood* in place of the originally posited likelihood. When working with the restricted likelihood, we summarize the data through a set of (insufficient) statistics $T(y)$ and update our prior distribution with the likelihood given $T(y)$ rather than the likelihood given $y$. By choice of $T(y)$, we retain the main benefits of Bayesian methods while reducing the sensitivity of the analysis to selected features of the data which are difficult (if not impossible) to model correctly. This talk will discuss the developed MCMC method for implementating the restricted likelihood and a hierarchical regression example applied to a messy insurance data set with many outliers."
abstract_short = ""

# Name of event and optional event URL.
event = "Craig Cooley Memorial Prize Talk"
event_url = "https://stat.osu.edu/events/ransom-and-marian-whitney-research-award-and-craig-cooley-memorial-prize-winners"

# Location of event.
location = "The Ohio State University, Columbus, OH"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_slides = "pdf/cooleyTalk.pdf"
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
