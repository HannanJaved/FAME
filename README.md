# Fairness in Graph Neural Networks using FAME

This repository contains the code and experiments for the paper, "GNN’s FAME: Fairness-Aware MEssages for Graph Neural Networks (GNNs)". The primary contribution of this work is the development of two novel layers designed to mitigate biases within GNNs: the Fairness-Aware MEssages (FAME) layer and the Attention Fairness-Aware MEssages (A-FAME) layer.

## Table of Contents
- [Introduction](#introduction)
- [Repository Structure](#repository-structure)
- [Datasets](#datasets)

## Introduction

Graph Neural Networks (GNNs) are powerful tools for learning representations of graph-structured data. However, GNNs are susceptible to biases that can arise from the underlying data, leading to unfair predictions. To address this issue, we propose two novel message-passing layers:

- **FAME (Fairness-Aware Message Passing)**: This layer adjusts the messages during the aggregation phase based on the disparities in sensitive attributes of connected nodes.
- **A-FAME (Attention Fairness-Aware Message Passing)**: This layer extends FAME by incorporating an attention mechanism to weigh the importance of node connections dynamically.

These layers aim to ensure more equitable outcomes by mitigating bias propagation within GNNs.

## Repository Structure
Due to the size of the datasets, only the code and some results have been uploaded to this repository.  
The 'Datasets' folder contains sub-folders for the various datasets on which the FAME and A-FAME have been tested.  
Since there is no common general use code for the FAME and A-FAME layer (for now), the code for each of the datasets is specific to the dataset and is available as python notebooks.

## Datasets
The datasets can be found under the following links: 
- Alibaba: [Alibaba Link](https://tianchi.aliyun.com/dataset/56)
- NBA: [NBA Link](https://www.kaggle.com/datasets/noahgift/social-power-nba)
- Pokec: [Pokec Link](https://snap.stanford.edu/data/soc-Pokec.html)
- German: [UCI Datasets Repo](https://archive.ics.uci.edu/)
- Credit: [UCI Datasets Repo](https://archive.ics.uci.edu/)
