# Chrono Clustering: A Novel Methodology for Dynamic Topic Trend Analysis

This repository contains the code and data for our paper accepted at IJCNN 2024.

## Introduction
Chrono Clustering is a framework designed to analyze and visualize the temporal changes of topics within textual data. Our method integrates dual clustering, enhanced keyword extraction, and hypergraph visualization to effectively quantify and portray topic evolution over time.

## Methodology
The methodology involves:
- Using K-Means clustering on vector embeddings for initial topic discovery.
- Applying one-iteration K-Medoids for aligning topics across different timeframes.
- Extracting semantically significant keywords to represent evolving topics.
- Visualizing topic progression using hypergraphs.

## Usage
### Requirements
- Python 3.8 or above
- Required libraries: `numpy`, `pandas`, `sklearn`, `matplotlib`, `nltk`, `sentence-transformers`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ChronoClustering-IJCNN2024.git
   cd ChronoClustering-IJCNN2024

