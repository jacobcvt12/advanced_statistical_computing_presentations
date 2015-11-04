---
title: "Generalized Linear Models - Nelder and Wedderburn"
author: "Jacob Carey and Guanghao Qi"
date: \today
output: 
    beamer_presentation:
        theme: "Szeged"
        slide_level: 1
---

# Who are Nelder and Wedderburn?

- Why are they important?
- Where/when did they work?

# John Nelder
- 1924 - 2010
- Graduated from Cambridge
- Worked at the prestigious National Vegetable Research Station
- Visiting Professor at Imperial College London from 1972 - 1984
- Developed statistical software such as GLIM

# 
![More than one Wedderburn...](img/wedderburn.png)

# Robert Wedderburn
- 1947 - 1975 (died at 28)
- Also graduated from Cambridge
- Worked at  Rothamsted Experimental Station where he developed GLMs with Nelder.

# What is a GLM?
- Generalizes several different "linear models"
- Uses a link function to "link" linear model to a response
    - In the paper, unifies normal, logistic, poisson and gamma

# How does one fit a GLM?

## Solving the maximum likelihood equation is equivalent to an iterative weighted least squares.

# What did you find interesting about the article?
- Tried to put myself in the shoes of people at this time period
- Before this GLM paper, it seems like linear models were the purview of statisticians only
- not so easily implemented (computationally)
- Now, these disparate linear models are grouped into one procedure
- For better or worse anyone can use GLMs now to make inference about regression parameters
