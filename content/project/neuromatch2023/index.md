---
title: Evaluating Reconstruction Accuracy in Neural Decoding Models
summary: We compared 2 metrics of reconstruction accuracy, namely, RMSE (Root Mean Squared Error) and FSIM (Feature Similarity Index) against human judgement in two tasks of relating the reconstructed images to original images.
date: '2022-07-29T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Research Materials and Accuracy Comparison
  focal_point: Smart

links:
# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: neuromatch2023
---
Decoding models may use human fMRI responses to an image for reconstructing the original image. That is - "we see what we think". For the project at Neuromatch Academy 2022, we are interested in whether human judgment or metrics for quantifying model performance on image reconstruction reflect more preciseness.

Human participants (N = 6, 3F, 3M; Age range: 23-27) were asked to a) match two sets (colored and grayscale) of reconstrcuted images to their original versions, and rate the perceived similarity on a scale of 0-100%, whereas algorithmic judgment was evaluated via RMSE (Root Mean Squared Error) and FSIM (Feature Similarity Index)
in Python using the image_similarity_metrics package (Müller et al., 2020).
 
Findings:
- In general, females matched the reconstructed images with the original ones more accurately and more quickly
- Males perform better with grayscale images
- Mean similarity ratings were lower for males than females
- Human judgment of both genders outperforms the two metrics
- FSIM outperforms RMSE
