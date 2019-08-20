---
title: Late Payment Predictor
summary: Predicted borrowers late payments with 99% accuracy 

#tags:
#- 
date: "2018-05-22T00:00:00Z"

# Optional external URL for project (replaces project detail page).
#external_link: ""

image:
  caption: 
  #Photo by rawpixel on Unsplash
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

I worked on this project when I was a Data Scientist at Datank.

## Goal
   - Predict which borrowers will make late payments for a Credit Risk team

## Duration
   - Three-month project

## Activities
   - Wrangled a very messy transaction stream
   - Recognized and extracted relevant information required for feature engineering and visualization
   - Made the selection of Machine Learning models by assessing their perfomance metrics 
   - Applied exponential decay to features, improving dramatically the precision of the predictions
   - Refactored -cleaning, training and prediction- code into Dockerized tasks as required by the Data Engineering team

## Toolbox
   - Docker
   - Python

## Outcome
   - Achieved model performance of 80% precision (99% accuracy)
   - Coded appropriate solutions fit for production
   - An API that delivers predictions seamlessly to a Credit Risk team
