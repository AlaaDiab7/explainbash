# Software Journal article: Bash code comment automatic generation method based on dual information retrieval

Here is the data set and source code of the Journal of Software 'Method for Automatically Generating Bash Code Comments Based on Dual Information Retrieval'

## Corpus

The data set is from the NL2Bash Research Shared Prediction Library and the official data of the NLC2CMD competition. There are duplicate data in it. After deleting the duplicate data, we constructed a corpus containing 10592 data. Including train.csv, test.csv and valid.csv.

## How to run the code

- Download the item
- Our project contains two folders: IR_Code and dataset, where IR_Code is the code required for the experiment, and dataset is the data set required for the experiment.
- The IR_Code file contains two files: explainBash.py and Information_Retrival.py. explainBash.py is the main method and the entry point of the operation. Here we need to confirm whether the path of the read training set and test set (the information retrieval method does not need the verification set) is correct. Information_Retrival.py is the specific code of the retrieval method. explainBash.py calls the method of Information_Retrival.py to retrieve all code annotations of the test set, and then calculates the evaluation indicators for the generated code annotations and real annotations.


# Interesting other references:
BASHEXPLAINER: Retrieval-Augmented Bash Code Comment Generation based on Fine-tuned CodeBERT
https://arxiv.org/pdf/2206.13325.pdf
