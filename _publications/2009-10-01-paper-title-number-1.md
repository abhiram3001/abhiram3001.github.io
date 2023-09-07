---
title: "G-MAP: A Graph-Neural Network Based Framework for Memory Access Prediction"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'In this paper, we introduce G-MAP, a novel Graph Neural Network-based
framework for Memory Access Prediction. First, we propose Mem2Graph, a novel approach mapping a memory
access sequence to a graph representation, capturing both the spatial and temporal locality in the memory access sequence which most existing methods fail to do. Second, we implement various GNNs for G-MAP, including Graph Convolutional Network (GCN), Gated Graph Sequence
Neural Network (GG-NN), and Graph Attention Network (GAT).'
date: 2023-08-30
venue: 'IEEE HPEC'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Memory access prediction is a crucial problem in data prefetchers, as it helps us improve memory performance and
reduce latency in computing systems. Existing works model the problem as a sequence prediction problem. This can
be limited in its ability to capture complex patterns and dependencies in memory access behavior. In recent years,
Graph Neural Networks (GNNs) have emerged as a promising technique for modeling and predicting complex
relationships in graph-structured data. 

In this paper, we introduce G-MAP, a novel Graph Neural Network-based
framework for Memory Access Prediction. First, we propose Mem2Graph, a novel approach mapping a memory
access sequence to a graph representation, capturing both the spatial and temporal locality in the sequence. Second,
we implement various GNNs for G-MAP, including Graph Convolutional Network (GCN), Gated Graph Sequence
Neural Network (GG-NN), and Graph Attention Network (GAT). Those models take the graph generated from
Mem2Graph as input and predict future memory address jumps (deltas). We evaluate the effectiveness of G-MAP
using the SPEC 2006 benchmark. G-MAP using GG-NN shows the highest among all models, achieving averagely
0.7526 F1-Score, which is 10.77% higher than the Multi-Layer Perceptron baseline.

Future work:
- Building a weighted graph representation, making the mapping more robust.
- Implemented state-of-the-art second models for the graph representation like GINs, GraphSage, and GraphSaint.
- Extending this technique to a secondary storage system instead of just cache memory.
- Heterogenous GNN for the same task, and adding time step to the nodes for a more dynamic representation.


[Download paper here](http://academicpages.github.io/files/paper1.pdf)

Recommended citation: to be added
