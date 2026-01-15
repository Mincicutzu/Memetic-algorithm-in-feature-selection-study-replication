# ReliefF–Memetic Algorithm Replication Study

This repository contains the code and experimental artifacts for a **replication study of the ReliefF–Memetic Algorithm (ReliefF–MA)** proposed by Yang et al. (2008) for feature selection in classification tasks.

The study reproduces the two-stage hybrid framework combining:
1. **ReliefF filter-based feature selection**
2. **Memetic Algorithm (MA) wrapper-based feature refinement**

Experiments are conducted on the Breast Cancer Wisconsin (Diagnostic) dataset using a 1-nearest neighbor (1-NN) classifier with leave-one-out cross-validation (LOOCV).

---

The implementation is written in **Python 3.8+** and depends on the following libraries:

- numpy
- scikit-learn
- scikit-rebate (`skrebate`)
- matplotlib (for plotting)
