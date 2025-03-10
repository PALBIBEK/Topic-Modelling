# Sentiment Clustering and Automated Cluster Labelling

This repository provides a text analysis pipeline for sentiment clustering and automated cluster labelling. The pipeline leverages advanced techniques including Bayesian Optimization, UMAP, HDBSCAN, an IDF-based method for key term extraction, and SpaCy for generating concise labels.

## Features

- **Sentiment Clustering:**  
  - Utilizes **Bayesian Optimization** for parameter tuning.
  - Employs **UMAP** for dimensionality reduction and **HDBSCAN** for robust clustering.

- **Automated Cluster Labelling:**  
  - Extracts key terms using an **IDF-based method** to enhance text interpretability.
  - Generates concise labels using **SpaCy** by extracting dominant **verbs**, **nouns**, and **objects** from clusters.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/PALBIBEK/Topic-Modelling.git
   cd Topic-Modelling
