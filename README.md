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


2.	Install the required libraries:
   pip install -r requirements.txt


Running the Code

	1.	Extract the contents of ChronoClustering.zip into the repository directory.
	2.	Navigate to the project directory.
	3.	Follow the instructions in the RUNNING.md file to set up and execute the analysis.

Citation

If you use this code or data in your research, please cite our paper:
@inproceedings{Li2024ChronoClustering,
  title={Chrono Clustering: A Novel Methodology for Dynamic Topic Trend Analysis},
  author={Qiaomu Li, Ying Xie, Shaoen Wu},
  booktitle={Proceedings of the International Joint Conference on Neural Networks (IJCNN)},
  year={2024}
}


Contact

For any questions or issues, please contact Qiaomu Li at qli12@students.kennesaw.edu.

License

This project is licensed under the MIT License - see the LICENSE file for details.
Just copy and paste this text into a new file named `README.md` in your GitHub repository.
