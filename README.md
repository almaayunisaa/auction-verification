# Auction Verification Classification

## Introduction

The selected dataset is the Auction Verification dataset. This dataset contains auction data with 9 variables, namely: capacity of bidder 1, capacity of bidder 2, capacity of bidder 3, capacity of bidder 4, auction price, verified item, winning bidder, auction verification result, and verification time. The verification process helps to analyze auction results more efficiently. We apply a classification learning method, specifically **k-nearest neighbors (KNN)**, to predict the auction verification result.

We chose KNN because our data is well-suited for classification tasks, and compared to other learning methods, KNN is more appropriate for our dataset, which contains numerical feature values.

The features used are: capacity of bidder 1, capacity of bidder 2, capacity of bidder 3, capacity of bidder 4, auction price, verified item, and winning bidder. The targets are: auction verification result. In this project, we use **auction verification result** as the target variable, since it is a classification task. The verification time is a regression target and is therefore excluded to maintain consistency in the classification approach.

The data is split into two parts: features stored in variable `X` and target stored in variable `y`. The test set consists of 20% of the data, and the remaining 80% is used for training. Additionally, 20% of the training data is further used for validation, with the remaining 80% for final model training.

Dataset source: [https://archive.ics.uci.edu/dataset/713/auction+verification](https://archive.ics.uci.edu/dataset/713/auction+verification)

## Features

- Dataset: [Auction Verification Dataset](https://archive.ics.uci.edu/dataset/713/auction+verification)
- Features used for classification:
- Capacity of Bidder 1
- Capacity of Bidder 2
- Capacity of Bidder 3
- Capacity of Bidder 4
- Auction Price
- Verified Item
- Winning Bidder
- Target variable: **Auction Verification Result**
- Model used: K-Nearest Neighbors (KNN)
- Predicts auction verification outcomes based on auction-related features

## Evaluation
- F1-score
- Accuracy

## Usage

1. Clone this repository
2. Open `Tugas_Besar_AI.ipynb` with Jupyter Notebook or Jupyter Lab
3. Run all cells to execute the classification and view results

## Requirements

- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-learn

You can install the requirements with:

```bash
pip install numpy pandas matplotlib scikit-learn
```
## Results

- The KNN model achieved around **93% accuracy** 
- F1-score model achieved around **60%**

## License

This project is for educational purposes.
