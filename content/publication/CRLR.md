+++
title = "Causally Regularized Learning with Agnostic Data Selection Bias"
date = 2018-09-12T17:25:51+08:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Zheyan Shen", "Peng Cui", "Kun Kuang", "Bo Li", "Peixuan Chen"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = " In *ACM Multimedia Conference* "
publication_short = "In *ACM MM*"

# Abstract and optional shortened version.
abstract = "Most of previous machine learning algorithms are proposed based on the i.i.d. hypothesis. However, this ideal assumption is often violated in real applications, where selection bias may arise between training and testing process. Moreover, in many scenarios, the testing data is not even available during the training process, which makes the traditional methods like transfer learning infeasible due to their need on prior of test distribution. Therefore, how to address the agnostic selection bias for robust model learning is of paramount importance for both academic research and real applications. In this paper, under the assumption that causal relationships among variables are robust across domains, we incorporate causal technique into predictive modeling and propose a novel Causally Regularized Logistic Regression (CRLR) algorithm by jointly optimize global confounder balancing and weighted logistic regression. Global confounder balancing helps to identify causal features, whose causal effect on outcome are stable across domains, then performing logistic regression on those causal features constructs a robust predictive model against the agnostic bias. To validate the effectiveness of our CRLR algorithm, we conduct comprehensive experiments on both synthetic and real world datasets. Experimental results clearly demonstrate that our CRLR algorithm outperforms the state-of-the-art methods, and the interpretability of our method can be fully depicted by the feature visualization."
abstract_short = "Most of previous machine learning algorithms are proposed based on the i.i.d. hypothesis. However, this ideal assumption is often violated in real applications. Therefore, how to address the agnostic selection bias for robust model learning is of paramount importance for both academic research and real applications. In this paper, we incorporate causal technique into predictive modeling and propose a novel Causally Regularized Logistic Regression (CRLR) algorithm by jointly optimize global confounder balancing and weighted logistic regression."

# Featured image thumbnail (optional)
image_preview = "CRLR.jpg"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/pdf/1708.06656.pdf"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
