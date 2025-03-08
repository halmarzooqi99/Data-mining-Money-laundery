# Data-mining-Money-laundery
Graph Neural Networks (GNNs) for Data Mining

# **Overview**

This repository contains implementations of Graph Neural Networks (GNNs) for data mining and machine learning tasks. The models include GCN (Graph Convolutional Networks), GAT (Graph Attention Networks), trained and evaluated on a Kaggle dataset.

Dataset

The dataset can be downloaded from Kaggle:
Multi-GNN Dataset

Downloading the Dataset

Ensure you have a Kaggle account.

## **Install the Kaggle API by running:**

```pip install kaggle

```

Run the following command to download the dataset:

```kaggle datasets download -d trnaacthng/multi-gnn
unzip multi-gnn.zip -d multi_gnn_data
```

## **Installation**

To set up the environment, install the necessary dependencies:

```pip install torch torch_geometric torch_sparse torch_scatter torch_spline_conv torch_cluster
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn
```

## **Running the Models**

Ensure that the dataset is downloaded and extracted into the correct folder before proceeding.

## **Training the GAT Model**

```python data_mining_gnns_models.py --model GAT
```

## **Training the GCN Model**

```python data_mining_gnns_models.py --model GCN
```

## **Results & Visualization**

The training script will generate:

Loss and accuracy curves

Confusion matrices

Classification reports


## **👥 Team Members**
- Mohamed Alhashmi 24000162
- Hamed Almarzooqi 24000630
- Saleh Alharthi   24001998


**Happy Coding! 🚀**
