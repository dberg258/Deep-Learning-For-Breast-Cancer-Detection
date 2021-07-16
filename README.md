# Detection of Lymph Node Metastases in Women With Breast Cancer

## Overview

This repository contains a solution to the [CAMELYON16](https://camelyon16.grand-challenge.org/Home/) challenge. The goal of this challenge is to develop an algorithm to detect cancer in digital slides of lymph node tissue.

## Motivation

To detect the presence of cancer on a slide containing lymph node tissue, a pathologist must spend a great deal of time analyzing the specimen under a microscope. This task is time consuming and subject to human error. With advancements in deep learning, an automated solution could be developed to analyze slides more efficiently and objectively. 

## Medical Background

![Image](https://grand-challenge-public-prod.s3.amazonaws.com/f/challenge/65/5ec25408-41fb-4075-a95f-4e855caee0c3/lymphNode.png)

Lymph node metastases occur in most cancer types (e.g. breast, prostate, colon). Lymph nodes are small glands that filter lymph, the fluid that circulates through the lymphatic system. The lymph nodes in the underarm are the first place breast cancer is likely to spread. Analyzing the tissue of the lymph node can therefore be used to detect breast cancer[.](https://camelyon16.grand-challenge.org/Background/) 


## Data

![Image](https://github.com/dberg258/Deep-Learning-For-Breast-Cancer-Detection/blob/main/Images/full_slide.png)

- The data for the challenge consists of high resolution slides of tissue

- 

## Implementation

The implementation in this repository uses a convolutional neural network. It was built using tensorflow and was trained on top of Mobilenetv2.



### Example Slide 

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```



