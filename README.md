# Markov chain Monte Carlo with PyMC3
### PyData London 2019 Tutorial


Bayesian methods are powerful tools for data science applications, complimenting traditional statistical and machine learning methods. Importantly, Bayesian models generate predictions and inferences that fully account for uncertainty. The main tool for conducting Bayesian analysis is Markov chain Monte Carlo (MCMC), a computationally-intensive numerical approach that allows a wide variety of models to be estimated. MCMC algorithms are available in several Python libraries, including PyMC3. I will teach users a practical, effective workflow for applying Bayesian statistics using MCMC via PyMC3 using real-world examples.

This tutorial is intended for analysts, data scientists and machine learning practitioners. Anyone looking for effective ways of making predictions and obtaining inference from datasets should find it useful. The material will assume an intermediate level of Python familiarity. Ideally, attendees should be familiar with Numpy and Jupyter. There is no expectation of students having a statistical background. Having completed the tutorial, students should be able to build basic Bayesian statistical models using their own data, validate those models, and interpret their output.

## Outline

1. Introduction to Bayes and PyMC3
    - What is a Baysian statistical model?
    - The Bayesian workflow in three steps
    - A high-level introduction to the PyMC3 API
    - Motivating examples
2. Markov chain Monte Carlo
    - Why is Bayesian analysis hard?
    - If you can't calculate, simulate!
    - The Metropolis algorithm
    - A better way: Hamiltonian Monte Carlo
3. Building and Fitting Models with PyMC3
    - Building blocks for Bayesian models
