---
title: "A template for projects"

---

# Introduction

This repository represents a template to organise research projects. There is not a very well defined project structure, so you can think this is a good starting point for your projects.

Plese use this template as *template* and do not fork it. 

# A proposed structure

In this template, I mainly used the [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/) example.

```
Project name
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- All the document information should go here
│   ├── reports
│   ├── presentations
│   ├── papers
│   ├── references
│   └── templates
│
├── notebooks          <- Jupyter or R notebooks
│
├── workflow           <- Source code and snakemake rules 
│   ├── Snakefile      <- A snakefile, should include all sub rules
│   │
│   ├── rules          <- Seperate snakefile that contains submodules of the workflow
│   │
│   ├── environments   <- Conda environments
│   │
│   └── singularity    <- Singularity containers
│ 
└── results

```

# References

+ https://drivendata.github.io/cookiecutter-data-science/#contributing
+ https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424
+ https://bookdown.org/alapo/learnr/
+ https://the-turing-way.netlify.app/welcome.html
