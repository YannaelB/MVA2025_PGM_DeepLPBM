# MVA2025_PGM_DeepLPBM


# Deep Latent Position Block Model (Deep LPBM) — Reimplementation & Extensions

## Overview

This repository provides a full **from-scratch reimplementation** of the **Deep Latent Position Block Model (Deep LPBM)** introduced by Boutin et al. (2025). Deep LPBM is a probabilistic framework that jointly performs **block clustering** and **latent space visualization** of networks by combining block models with deep variational graph autoencoders.

Beyond reproducing the original method, this project critically analyzes its empirical behavior, highlights reproducibility challenges, and proposes an **extension to directed graphs with self-loops** using an attention-based encoder.

All experiments are implemented as **fully executable Jupyter/Colab notebooks**.

[![Open In Colab]([https://colab.research.google.com/assets/colab-badge.svg](https://colab.research.google.com/drive/1PAQlR8zzE5LCQtk4NygP6cVYdwNgRhDp?usp=sharing))]

---

## Abstract

This project reimplements and investigates the Deep Latent Position Block Model (Deep LPBM), a variational framework that unifies block clustering and latent representation learning for graph-structured data. We reproduce the original model on synthetic and real-world networks, analyze its sensitivity to initialization and training dynamics, and benchmark connectivity recovery via Frobenius norm comparisons. In addition, we propose and evaluate an extension of Deep LPBM to directed graphs with self-loops using a graph attention encoder. The accompanying notebooks cover symmetric and asymmetric settings, ego-network experiments, and quantitative analyses of connectivity estimation.

---






