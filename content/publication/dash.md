+++
abstract = 'Image classification models often learn to predict a class based on irrelevant co-occurrences between input features and an output class in training data. We call the unwanted correlations "data biases," and the visual features causing data biases "bias factors."" It is challenging to identify and mitigate biases automatically without human intervention. Therefore, we conducted a design study to find a human-in-the-loop solution. First, we identified user tasks that capture the bias mitigation process for image classification models with three experts. Then, to support the tasks, we developed a visual analytics system called DASH that allows users to visually identify bias factors, to iteratively generate synthetic images using a state-of-the-art image-to- image translation model, and to supervise the model training process for improving the classification accuracy. Our quantitative evaluation and qualitative study with ten participants demonstrate the usefulness of DASH and provide lessons for future work.'
authors = ["Bum Chul Kwon", "Jungsoo Lee", "Chaeyeon Chung", "Nyoungwoo Lee", "Ho-Jin Choi", "Jaegul Choo"]
date = "2022-04-23"
highlight = true
image_preview = "dash.png"
math = false
publication = "Eurographics Conference on Visualization (EuroVis)-Short Papers"
publication_short = "EuroVis-Short"
publication_types = ["1"]
selected = false
title = "DASH: Visual Analytics for Debiasing Image Classification via User-Driven Synthetic Data Augmentation"
award = "Honorable Mention"
url_award = "https://conferences.eg.org/eurovis2022/best-paper-and-best-reviewer-awards/"
url_code = ""
url_dataset = ""
url_pdf = "pdf/dash.pdf"
url_project = ""
url_slides = ""
url_video = "https://vimeo.com/702371195"
url_bib = "bib/dash.bib"
video_id="702371195"

#[[url_custom]]
#name = "Supplementary Material"
#url = "pdf/vlat_sup.pdf"

[header]
  caption = "DASH is a visual analytics system that enables users to identify and mitigate data biases CNN-based image classification models learned from training data."
  image = "dash_teaser.png"

+++