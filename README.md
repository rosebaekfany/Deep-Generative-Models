# Deep Generative Models

Homework assignments and the final project for the **Deep Generative Models** course. It includes assignments (HWs) as well as the project on *Aligning Consistency Models via Preference Optimization*.

## 📝 Homeworks

| Notebook | Topic |
|---|---|
| `hw1-dgm-pr-400110009.ipynb` | Autoregressive models (LSTM) |
| `DGM_HW2_Practical.ipynb` | Variational autoencoders, out-of-distribution and anomaly detection |
| `DGM_HW3_GAN_Practical_real (1).ipynb` | DC-GAN on MNIST and latent-space interpolation |
| `Normalizing_Flow_Practical_Students (1).ipynb` | Normalizing flows from scratch, training and in-painting |

## 🧠 Final Project: Aligning Consistency Models via Preference Optimization

The main project for the course is **“Aligning Consistency Models via Preference Optimization”**, which you can find here:

[Aligning Consistency Models via Preference Optimization](https://github.com/Theborna/Aligning-Consistency-Models-via-Preference-Optimization)

### Project Overview

* The project introduces a framework for aligning *consistency models* (a class of deep generative models) with human preferences using an extended DPO (Direct Preference Optimization) approach.
* It tackles challenges such as modifying DPO to work with models that are more deterministic (consistency models), preserving the consistency property, and dealing with intractable distributions.
* The approach balances preference optimization with consistency preservation via a combined loss function.
