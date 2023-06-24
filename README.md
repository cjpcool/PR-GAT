#  CustomGNN

This is the code of paper: "Customizing Graph Neural Networks using Path Reweighting"


# Requirements

* Python 3.8.5
* PyTorch 1.7.1
* Please install other pakeages by `pip install -r requirements.txt`

# Datasets
* Cora and Citeseer are included in `.\data\cora` and `.\data\citeseer` respectively.

* Large datasets will be dowloaded automatically by PyTorch-Geometric when you run `python custom_gnn.py --dataset [CoraFull, CoauthorCS, AmazonComputers, AmazonPhoto]`

# Test CustomGNN

* Test CustomGNN on Citeseer: `sh test_citeseer.sh`
* Test CustomGNN on Cora: `sh test_cora.sh`
* Test CustomGNN on Cora: `sh train_pubmed.sh`

# Train CustomGNN

* Train CustomGNN on Citeseer: `sh train_citeseer.sh`
* Train CustomGNN on Cora: `sh train_cora.sh`
* Train CustomGNN on Cora: `sh train_pubmed.sh`

# Results of CustomGNN

The test accuracies of CustomGNN on 7 datasets (3 citation graphs with public split and 4 large datasets with random split) are as follows.

| Cora | Citeseer | PubMed | Cora-Full | CoauthorCS | AmazonComputers| AmazonPhoto |
| ---- | -------- | ------ | ------ | ------ | ------ | ------ |
| 85.6 | 76.2     | 83.4   |44.2 |93.4 | 81.9 | 92.0 |



# Running Environments

The experiments of Citeseer are conducted on NVIDIA GeForce RTX 3070 Ti with 8GB memory size, the experiments of Cora Full, Amazon Computer, Amazon Photo and Cauthor CS are conducted on Tesla V100 with 32GB memory size, and the experiments of Cora and PubMed are conducted on V100 with 80GB memory size.

---

Please feal free to contact me if you have any question about this code.

