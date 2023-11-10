---
title: Digital Images Processing with different filters
summary: Coursework in Signal Processing, 2021 Fall
tags:
  - Coursework
  - Signal Processing
  - Image Processing
  - 2021 Fall
date: '2021-10-20T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo of Abstract of the course paper
  focal_point: Smart

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---
In this study, we will investigate the best way to reduce different noises on images. 

According to the mathematics principles, convolution and pooling methods are employed to define functions of median and mean filters to process images with varies kind of noise(i.e. Gaussian noise, Salt&Pepper noise, Speckle noise, etc.). Also, Fast Fourier Transform(which will be noted as FFT in the following) is used for getting image results on frequency domain.

On images with Salt&Pepper noise, median filter did well than mean filter when the density is lower than 30%. When the density is above 60%, both filters have poor performance for Salt&Pepper noise. Median filter is better than mean filter for Gaussian noise, while mean filter is better than median filter for Salt&Pepper noise. Both filters did not bad for Speckle noise.

On the reason of linearity, mean filter can’t protect details on the images when reducing noise. While median filter has the nonlinear property, it’s better to process impulse but there’s trouble dealing with continuous polluted points, which accounts for the poor performance on reducing Gaussian noise.

To deal with Gaussian noise, mean filter is the best way. To deal with Salt&Pepper noise, median filter is the best way. Different filters should be applied according to different situations, for each filters has merits and demerits.

**KEYWORDS**: Median filter, Mean filter, Sobel operator


Access to full PDF: [Digital Images Processing with Different Filters](./English%20version_Yunzhe%20Li20123101_Digital%20Images%20Processing%20to%20reduce%20noise.pdf)
