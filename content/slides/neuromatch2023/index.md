---
title: Evaluating Reconstruction Accuracy in Neural Decoding Models
summary: An introduction to using Wowchemy's Slides feature.
authors: [Harmandeep Singh Khera, Boyin Feng]
tags: []
categories: []
date: '2022-07-29T00:00:00Z'
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

<a name="br1"></a> 

Evaluating

Reconstruction Accuracy

in Neural Decoding

Models

**Team:** Motorized Marmots 🐿️🐿️


**Members:** Harmandeep Singh Khera & Boyin Feng

**Pod:** Gazpacho 🥘


**Mentors:** Ahmad Samara, Amy Kuceyeski, Javier Guaje



<a name="br2"></a> 

Introduction

\- Decoding models relate regional brain activity (e.g., voxel-wise BOLD

response) to the stimulus:

\- In human vision research, decoding models are evaluated for their ability to

use fMRI responses to an image for predicting:

\-

\-

\-

its stimulus class (‘classification’)

recognise it among distractors (‘identification’),

or reconstruct the original image

\- However….

The “one pixel attack”

From Kay, K., Gallant, J. Nat Neurosci (2009)



<a name="br3"></a> 

Introduction (contd.)

\- There are multiple metrics for quantifying model performance on image

reconstruction — leading to:

\-

\-

ad-hoc choices

less comparability among

decoding models

\- We propose that human judgement should serve as the golden standard; we,

therefore, compared 2 metrics of reconstruction accuracy against 2 human

judgement tasks



<a name="br4"></a> 

Methods

\- Human judgment:

\-

Participants (N = 6, 3F, 3M; Age range: 23-

\27)

\-

2 Dimensions: accuracy; perceived similarity

\-

Conventional measures:

\-

Metrics: RMSE (Root Mean Squared Error)

and FSIM (Feature Similarity Index)

Implemented in Python using the

image\_similarity\_metrics package (Müller et

al., 2020)

Materials:

\-

\-

10 colored pairs (Nishimoto et al., 2011) in 3 min;

9 grayscale pairs (K. Seeliger et al., 2018) in 2 min

\-



<a name="br5"></a> 

Results

Interesting results

\- In general, females matched the

reconstructed images with the original

ones more accurately and more quickly

Accuracy by Gender

\- Males perform better with grayscale

images

\- Mean similarity ratings were lower for

males than females

Perceived Similarity by Gender

(correct trials only)



<a name="br6"></a> 

Discussion

\- Our results suggest that human

judgements may help improve

comparability among decoding

models

\- Future empirical surveys should

investigate:

\-

\-

\-

Differences b/w category of objects

(e.g. faces vs tools)

Graded judgements of similarity (e.g.

shape vs taxonomic class)

The metrics for human judgment

need further examination as well

