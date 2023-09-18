---
layout: page
title: About
description: Загальна інформація.
nav_order: 1
---

# Overview
{:.no_toc}

## Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

{% assign overview = site.slides | where: "title", "Огляд" | first %}
{{ overview.content }}


Prerequisites
: 1. **Mathematics**: Knowledge of and ability to use calculus, analytical geometry, linear
algebra and probability theory.
1. **Programming**: Ability to program in Python.


Textbooks
: 1. Goodfellow, I., Bengio, Y., & Courville, A. (2016).  [*Deep Learning.* ](https://www.deeplearningbook.org/) MIT press.
1. Russell, S., & Norvig, P. (2021). [*Artificial Intelligence: A Modern Approach.*](https://www.amazon.com/Artificial-Intelligence-A-Modern-Approach/dp/0134610997#customerReviews)
1. Khan, S., Rahmani, H., Shah, S. A. A., Bennamoun, M., Medioni, G., & Dickinson, S. (2018). [*A guide to convolutional neural networks for computer vision*](https://usermanual.wiki/Document/A20Guide20to20Convolutional20Neural20Networks20for20Computer20Vision.938259461/view)


## Air raid sirens
{% assign specifics = site.slides | where: "title", "Повітряна тривога" | first %}
{{ specifics.content }}

<!-- ## Особливостi
{% assign specifics = site.slides | where: "title", "Особливостi" | first %}
{{ specifics.content }} -->

## Grading
{% assign grading = site.slides | where: "title", "Система оцiнювання" | first %}
{{ grading.content }}


## Honor Code
{% assign honorcode = site.slides | where: "title", "Кодекс честi" | first %}
{{ honorcode.content }}


<!-- ## Як успішно завершити курс?
{% assign succeed = site.slides | where: "title", "Як успішно завершити курс?" | first %}
{{ succeed.content }} -->