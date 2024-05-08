+++
abstract = "The recent prevalence of publicly accessible, large medical imaging datasets has led to a proliferation of artificial intelligence (AI) models for cardiovascular image classification and analysis. At the same time, the potentially significant impacts of these models have motivated the development of a range of explainable AI (XAI) methods that aim to explain model predictions given certain image inputs. However, many of these methods are not developed or evaluated with domain experts, and explanations are not contextualized in terms of medical expertise or domain knowledge. In this paper, we propose a novel framework and python library, MiMICRI, that provides domain-centered counterfactual explanations of cardiovascular image classification models. MiMICRI helps users interactively select and replace segments of medical images that correspond to morphological structures. From the counterfactuals generated, users can then assess the influence of each segment on model predictions, and validate the model against known medical facts. We evaluate this library with two medical experts. Our evaluation demonstrates that a domain-centered XAI approach can enhance the interpretability of model explanations, and help experts reason about models in terms of relevant domain knowledge. However, concerns were also surfaced about the clinical plausibility of the counterfactuals generated. We conclude with a discussion on the generalizability and trustworthiness of the MiMICRI framework, as well as the implications of our findings on the development of domain-centered XAI methods for model interpretability in healthcare contexts."
abstract_short = ""
authors = ["Grace Guo", "Lifu Deng", "Animesh Tandon", "Alex Endert", "Bum Chul Kwon"]
date = "2024-04-24"
highlight = true
image_preview = "mimicri.jpg"
math = false
publication = "ACM Conference on Fairness, Accountability, and Transparency (ACM FAccT)"
publication_short = "FAccT"
publication_types = ["1"]
selected = false
title = "MiMICRI: Towards Domain-centered Counterfactual Explanations of Cardiovascular Image Classification Models"
url_code = ""
url_dataset = ""
url_pdf = "pdf/mimicri.pdf"
url_project = ""
url_slides = ""
url_video = ""
url_bib = "bib/mimicri.bib"
url_webapp = ""
video_id = ""

[[url_custom]]
name = "Code"
url = "https://github.com/IBM/mimicri"


[header]
  caption = "Users interactively combine segmented parts of target images sourced from selected images. They then input these newly generated images into the model to generate predicted labels. Users can analyze counterfactuals generated from various image segments."
  image = "mimicri.png"
  video_caption = "This video demonstrates how Causalvis can be helpful for users to conduct causal inference. Causalvis is a Python library that can be used in an interactive computing environment like Jupyter Notebook."

+++

