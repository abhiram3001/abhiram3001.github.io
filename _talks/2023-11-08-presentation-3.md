---
title: "Adaptive Signal Processing Project"
collection: presentation
type: "Presentation"
permalink: /talks/2023-09-01-tutorial-3
venue: "ESB 213B, IIT Madras"
date: 2023-11-08
location: "Chennai, India"
---
Compressed sensing is a classical signal processing technique of reconstructing a sparse signal (’compressible’ signal) from as minimum number of measurements as possible. Let’s now consider the problem of reconstructing time sequences of spatially sparse signals (with unknown and time-varying sparsity patterns) from a limited number of linear “incoherent” measurements, in real-time. The signals are sparse in some transform domain referred to as the sparsity basis. For a single spatial signal,we can apply Compressed sensing (CS) to solve the problem.

So now, for a sequence of sparse signals, can we do better than CS, if (a) the sparsity pattern of the signal’s transform coefficients’ vector changes slowly over time, and (b) a simple prior model on the temporal dynamics of its current non-zero elements is available. The broad idea is to make use of a Kalman Filter, exploiting the causal relationship between consecutive realisations of the underlying
signal. We also address the problem of estimating new additions to the support of the signal. 

My work was on solving the classic problem of reconstructing time sequences of sparse signals with minimal measurements using KF-CS. I was able to demonstrate its performance gain in scenarios with slowly evolving sparsity (such as MRI/CT scan), showing that KF-CS achieves a performance rate comparable to that of genie-aided KF when the initial support of the signal is known.

Here are the links to the [slides](https://drive.google.com/file/d/1129Z_QpI9RL3aVEtwBZl3XOEg66AYjS1/view) and [report](https://drive.google.com/file/d/1sJocvKSKmpLytXMw7A7mWbRTROtcwuEa/view).
