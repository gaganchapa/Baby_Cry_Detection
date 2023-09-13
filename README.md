
# Baby Cry Detection

This repository contains the implementation of a Baby Cry Detection system that utilizes Machine Learning algorithms to analyze audio files of infant cries and predict the underlying reason. The system is trained to classify cries into five distinct classes: Belly Pain, Burping, Discomfort, Hungry, and Tired. The model has achieved an impressive accuracy of 95%.


## Overview

The Baby Cry Detection system employs advanced techniques such as oversampling to balance the dataset, PCA (Principal Component Analysis) for dimensionality reduction, and MFCC (Mel Frequency Cepstrum Coefficient) for feature extraction. These processes enhance the model's ability to accurately classify cries based on their underlying causes.

## Dependencies

To run this project, you will need the following dependencies:

- Python (>=3.6)
- Libraries listed in `requirements.txt`

You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
```
or
```bash
pip install scipy pandas librosa numpy scikit-learn matplotlib seaborn imbalanced-learn
```

[Dataset Link ](https://github.com/gveres/donateacry-corpus/tree/master/donateacry_corpus_cleaned_and_updated_data)

## Results

![Alt Text](https://github.com/gaganchapa/Baby_Cry_Detection/blob/main/result.jpg)https://github.com/gaganchapa/Baby_Cry_Detection/blob/main/result.jpg)

