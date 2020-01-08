+++
title = "LeDeepChef 👨🏻‍🍳 : Deep Reinforcement Learning Agent for Families of Text-Based Games"
date = "2019-08-28"
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**L Adolphs***" ,"T Hofmann"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["0"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract and optional shortened version.
abstract = "While Reinforcement Learning (RL) approaches lead to significant achievements in a variety of areas in recent history, natural language tasks remained mostly unaffected, due to the compositional and combinatorial nature that makes them notoriously hard to optimize. With the emerging field of Text-Based Games (TBGs), researchers try to bridge this gap. Inspired by the success of RL algorithms on Atari games, the idea is to develop new methods in a restricted game world and then gradually move to more complex environments. Previous work in the area of TBGs has mainly focused on solving individual games. We, however, consider the task of designing an agent that not just succeeds in a single game, but performs well across a whole family of games, sharing the same theme. In this work, we present our deep RL agent---LeDeepChef---that shows generalization capabilities to never-before-seen games of the same family with different environments and task descriptions. The agent participated in Microsoft Research's *First TextWorld Problems: A Language and Reinforcement Learning Challenge* and outperformed all but one competitor on the final test set. The games from the challenge all share the same theme, namely cooking in a modern house environment, but differ significantly in the arrangement of the rooms, the presented objects, and the specific goal (recipe to cook). To build an agent that achieves high scores across a whole family of games, we use an actor-critic framework and prune the action-space by using ideas from hierarchical reinforcement learning and a specialized module trained on a recipe database."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
[[url_custom]]
    name = "arXiv"
    url = "http://arxiv.org/abs/1909.01646" # todo change

[[url_custom]]
    name = "Code"
    url = "https://github.com/leox1v/FirstTextWorldProblems" # todo change

[[url_custom]]
    name = "Medium"
    url = "https://medium.com/@leonard.adolphs.95/ledeepchef-deep-reinforcement-learning-agent-for-families-of-text-based-games-a228214378f9" # todo change

# Digital Object Identifier (DOI)
doi = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
