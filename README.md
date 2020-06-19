# Replicated Region of Attraction Analysis

## Summary
This repository contains a [report](/Report/Carpinelli_ROA_Estimation.pdf), and [Jupyter Notebook](/Code/Carpinelli%20-%20ROA%20Estimation.pdf) summarizing (and at times, replicating) nonlinear region of attraction analysis completed by [Chakraborty et al](https://www.sciencedirect.com/science/article/abs/pii/S0967066110002595). This project was completed as part of the University of Maryland Aerospace Engineering Department's Applied Nonlinear Control course (ENAE 743). The end result has been placed here for convenience, the full repository history is in a private coursework repository.

## Background
NASA's GTM is a high-fidelity radio controlled model aircraft, which is used to research off-nominal flight control conditions. Chakraborty et al summarized the longitudinal state dynamics of NASA's GTM, approximated the dynamics as low-order polynomials, and then took advantage of existing sum-of-squares optimization software (such as [SOSTOOLS](https://www.cds.caltech.edu/sostools/)) to efficiently approximate the maximum elliptical subset of a trim condition's region of attraction.

As part of a Spring 2020 ENAE 743 final project, Chakraborty et al's results were summarized. First, the results were informally summarized and partially implemented with Python code in a [Jupyter Notebook](/Code/Carpinelli%20-%20ROA%20Estimation.pdf). Then, the results (replicated and not) were formally summarized in a [report](/Report/Carpinelli_ROA_Estimation.pdf).
