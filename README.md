## Applied Machine Learning in Bioinformatics - Feature Selection

MRC Biostatistics Unit  
University of Cambridge  
Easter 2026   
Solon Karapanagiotis  
sk921  

---
## 👋 Welcome
This repository contains all course materials, including:

Lecture slides   
Practicals   
Datasets   

---
## 📂 Repository Structure
. 
├── data/          # datasets used in practicals  
├── practicals/    # practical lab sessions (RMarkdown)   
├── practicals/demos # code for the practicals and data generating functions.  
├── slides/        # lecture slides (HTML/qmd)  

---

## 💻 Getting Started

### Install Required Software

You will need:

- R (latest version)
- RStudio
- Git (recommended)

### Install Required R Packages

```r
install.packages(c(
  "tidyverse",
  "here",
  "rmarkdown",
  "knitr",
  "ggplot2"
))
```
### Working with Paths (Important!)
This course uses the `here` package so file paths work on all computers.

Always load files like this:

```r
library(here)
read.csv(here("data", "dataset.csv"))
```
⚠️ License / Usage

Course materials are provided for educational use only.
Please do not redistribute without permission.
