# Mastering Gaussian Processes with PyMC

**PyData NYC 2024**

Gaussian processes (GPs) are a powerful Bayesian approach for quantifying uncertainty and making probabilistic inferences, especially when dealing with complex, non-linear relationships in regression and classification.
This tutorial will introduce you to the flexibility of GPs in handling diverse data problems, including the [new Hilbert space Gaussian process (HSGP) approximation](https://www.pymc.io/projects/examples/en/latest/gaussian_processes/HSGP-Basic.html), which scales GPs to large datasets.
By the end, you will be equipped to specify, fit, and validate GP models using PyMC, with a special focus on a real-world sports analytics case study.

---

Gaussian processes (GPs) are a versatile and powerful tool in the Bayesian modeling toolkit, allowing users to model complex systems without needing to specify exact functional forms. This tutorial is designed for data scientists and statisticians who are new to GPs or want to deepen their understanding.

We'll begin with an overview of probabilistic modeling before outlining the key properties of GPs, notably their flexibility in capturing non-linear relationships and their ability to incorporate prior knowledge. We will then focus on the practical aspects of building and fitting GP models in PyMC, highlighting the importance of selecting the right covariance function and demonstrating how to apply the HSGP approximation for scaling to larger datasets.

To reinforce these concepts, we will demonstrate a Gaussian process modeling workflow using a sports analytics example. Here we will demonstrate how to use GPs to model the data and generate predictions, showcasing the practical application of these concepts in real-world scenarios.

## Target Audience

This tutorial is aimed at data scientists, statisticians, and researchers with a basic understanding of statistics and Python, who are interested in learning how to apply Gaussian Processes to their work. Prior experience with PyMC is not required but will be beneficial.

## Takeaway

Participants will leave with a solid understanding of Gaussian Processes and the skills needed to apply these models using PyMC, including handling large datasets with HSGP. They will also gain insight into practical applications through a detailed sports analytics case study.

## Background Knowledge Required

Basic understanding of probability and statistics, and familiarity with Python.

## Materials Distribution

All tutorial materials, including notebooks and datasets, will be made available via a GitHub repository.

## Computer Setup

We recommend using either [Conda](https://docs.conda.io/en/latest/miniconda.html) or [Pixi](https://pixi.sh/latest/) to install the dependencies for this tutorial. Which you choose is a matte of personal preference. Once installed, you can create the environment by running the appropriate command below from within the project directory.

### Conda

```bash
conda env create -f environment.yml
```

### Pixi

```bash
pixi shell
```

## Tutorial Outline

1. Introduction to Gaussian Processes
2. Covariance Functions and Kernel Methods
3. Bayesian Inference in PyMC
4. HSGP Approximation for Large Datasets
5. Sports Analytics Case Study
