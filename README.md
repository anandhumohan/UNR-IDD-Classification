# UNR-IDD-Classification

Welcome to the `UNR-IDD-Classification` project! This repository is dedicated to the development and evaluation of machine learning models for Intrusion Detection Systems (IDS) using the UNR-IDD dataset. Our goal is to provide a comprehensive analysis of various algorithms' performance in detecting network intrusions, contributing to more secure and resilient network environments.

## About

The project utilizes the UNR-IDD dataset, a collection of network traffic data that includes both benign and malicious traffic patterns. Our focus is on applying and comparing several machine learning algorithms to accurately classify and detect intrusion attempts.

## Algorithms

The repository includes Jupyter notebooks for each of the following algorithms:
- AdaBoost (`UNR-IDD_AdaBoost.ipynb`)
- Bagging (`UNR-IDD_Bagging.ipynb`)
- Decision Tree (`UNR-IDD_Decision_tree.ipynb`)
- K-Nearest Neighbors (KNN) (`UNR-IDD_KNN.ipynb`)
- Random Forest (RF) (`UNR-IDD_RF.ipynb`)

Each notebook contains the final implementation of the algorithm, including data preprocessing, model training, evaluation, and a discussion of the results.

## Dataset

The `UNR-IDD.csv` file contains the dataset used for model training and testing. It includes a variety of features extracted from network traffic, labeled as either benign or malicious, to facilitate the development of effective intrusion detection models.

## Getting Started

To explore and run the models:
1. Clone the repository to your local machine.
2. Ensure you have Jupyter Notebook or JupyterLab installed, along with necessary Python libraries such as `numpy`, `pandas`, `scikit-learn`, and `matplotlib`.
3. Open the desired algorithm notebook via Jupyter Notebook/Lab and run the cells sequentially to replicate the analysis.

## Contributing

We welcome contributions from the community! If you have improvements to algorithms, additional analysis, or bug fixes, please feel free to fork the repository and submit a pull request.

## License

This project is open-sourced under the MIT license. See the LICENSE file for more details.

## Acknowledgments

Thanks to all contributors and the community for supporting this project. Special thanks to Anandhu Mohan for initiating and maintaining this repository.
