# omniScan
## Deep and Confident Image Analysis for Disease Detection [PDF](https://doi.org/10.1145/3442705.3442720 "Downdoald the paper from here")

## Abstract
_This paper proposes an efficient deep learning classifier built on Bayesian deep neural network framework for general probabilistic disease detection along with reliable principled uncertainty estimation. Specifically we harness the expressiveness and temporal nature of Seq-2-Seq Convolutional neural networks (CNNs) to model explicitly disease detection problem via deep and confident image processing. The work in this paper shows that the uncertainty informed decision making can improve the diagnostic performance considerably. Furthermore, we deploy a Memory Network in order to memorize detected images representing infected cells in historical records. We demonstrate and validate empirically the effectiveness of the proposed framework via extensive experimental and rigorous evaluation on large-scale real world data sets. Experiments across different tasks and datasets show robust generalization, accurate and superior performance of proposed method compared to the well-known state-of-the-art diseases detectors._

## omniscan.py 
This file contains OFA implemetation algorithm 

## Datasets
- Wisconsin breast cancer [available from here](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic) "breast cancer dataset link")
* Malaria image dataset [can be downloaded here](https://ceb.nlm.nih.gov/proj/malaria/cell_images.zip "Malaria dataset")
- Skin cancer dataset [card can be downloaded here](https://www.kaggle.com/mlg-ulb/creditcardfraud "skin cancer dataset")

## Dependencies
1. Tensoflow 2
2. Keras 2.3.1
3. Python 3.6

