# SEED
## Statistical Exploration Environment for Data

In many engineering projects the aim is to obtain a good understanding of underlaying data. Let it be finding sensitivies or correlations of measurement
data (where inputs and outputs are known) or FE-model-based sensitivity studies in which the outputs, also called responses, are calculated and tracked.
Later these data can be used to derive response surfaces, mathematical models of the system's behavior, on which optimizations can be performed with
minimal time effort.

The aim is to provide a multidisciplinary design study program to explore and optimize data-based models. A smart combination of automated preprocessing, predictive modeling and data mining is utilized for design space exploration.

## Capabilities
Within my MPS (manufacturing process simulation) history and grown skills over the past years we gained the theoretical as well as the pratical knowledge of how to perform such studies but
also how to develop tools that can mimic HyperStudy's functionalities.
The proposal is to create a browser-based environment that can be used by anyone within our company with as little effort as possible. Let it be experts
setting up complex FE-based non-linear optimizations or production and R&D engineers that want to explore and understand production and experimental
data up to making sense out of sales data.

## Functionalities
This interface between a design study software and applied data science can be established by connecting following dots:
- Python flask backend
- pyDOE2: an experimental design package for python that is designed to help scientists, engineers, statisticians, etc., to construct appropriate
experimental designs
- python LUX - an intelligent data visualization toolkit
- Python statsmodels https://www.statsmodels.org/stable/index.html - Python module that provides classes and functions for the estimation of many
different statistical models, as well as for conducting statistical tests, and statistical data exploration
- Scipy - Python-based ecosystem of open-source software for mathematics, science, and engineering
- Scikit Learn - Simple and efficient tools for predictive data analysis for regression, classification, clustering, dimensionality reduction and much
more
