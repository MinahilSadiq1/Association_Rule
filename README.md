# Association Rule Mining using Apriori Algorithm

This project involves deriving association rules from a dataset using the Apriori algorithm. It employs the `mlxtend` library for the actual rule mining process. The dataset is read from a Google Drive link and is then preprocessed for the rule mining procedure.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)

## Installation:

Ensure you have `mlxtend` library installed. If not, you can use the following command:

   ```bash
   !pip install mlxtend
   ```

## Usage:

1. Set your dataset path in the dataset_path variable.

   ```bash
   dataset_path = '/path_to_your_dataset/dataset.csv'
   ```
2. Run the entire script to derive the association rules.

## Methodology:

1. The dataset is first read into a DataFrame from a CSV file.
2. Transactions are extracted from the dataset and are then converted into a format suitable for the Apriori algorithm.
3. The mlxtend library's apriori method is used to derive frequent item sets.
4. Association rules are generated from these frequent item sets.

## Results:

After executing the script, you will see two outputs:
1. Frequent item sets that meet the minimum support threshold.
2. Association rules derived from these frequent item sets that meet the confidence threshold.

 
