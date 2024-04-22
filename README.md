# Gaussian vs. Cauchy Naive Bayes Classifier

This project implements Gaussian and Cauchy Naive Bayes classifiers and compares their performance on the Heart Disease UCI dataset from Kaggle. Naive Bayes classifiers are popular for their simplicity and efficiency in classification tasks, particularly in medical diagnosis and risk assessment, text classification, and spam filtering.

## Overview

In this project, we have implemented two variations of the Naive Bayes classifier:

1. **Gaussian Naive Bayes**: Assumes that the features follow a Gaussian distribution.

2. **Cauchy Naive Bayes**: Assumes that the features follow a Cauchy (Lorentzian) distribution.

We aim to compare the performance of these classifiers on the Heart Disease UCI dataset and evaluate their strengths and weaknesses.

## Dataset

The Heart Disease UCI dataset is sourced from Kaggle. It contains data on various attributes related to heart disease diagnosis, including age, sex, cholesterol levels, and exercise-induced angina. The dataset can be found at [Kaggle - Heart Disease UCI](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset).

## EDA

![image](https://github.com/SB2520/Complete-Naive-Bayes/assets/109037815/b942f2a9-1dc3-4558-be0c-4cdd83517840)


## Vizualisation and Analysis

![image](https://github.com/SB2520/Complete-Naive-Bayes/assets/109037815/bc23bcda-4844-4029-9b4f-8422c7874243)

![image](https://github.com/SB2520/Complete-Naive-Bayes/assets/109037815/a17dfe59-ae82-486f-a12e-08992a11cb30)

![image](https://github.com/SB2520/Complete-Naive-Bayes/assets/109037815/2936486e-8906-4242-93c5-7bfe922e4ff1)



## Implementation

The classifiers are implemented in Jupyter Notebooks using Python. The code structure is organized as follows:

- `Gaussian.ipynb`: Implementation of Gaussian Naive Bayes classifier.
- `Cauchy.ipynb`: Implementation of Cauchy Naive Bayes classifier.

## Usage

To run the experiment and compare the classifiers:

1. Clone this repository to your local machine.

2. Install the required dependencies using `pip install -r requirements.txt`.

3. Download the Heart Disease UCI dataset from Kaggle and place the `heart.csv` file in the `data/` directory of the project.

4. Open `Gaussian.ipynb` and `Cauchy.ipynb` in Jupyter Notebook.

5. Follow the instructions in the notebooks to execute the code cells and compare the classifiers.

## Results

After running the experiment, the script will display the following results:

![image](https://github.com/SB2520/Complete-Naive-Bayes/assets/109037815/faa850ad-8452-46f3-adb0-37e4e1bcea8f)


## Presentation

The presentation slides for this project are available [here](https://drive.google.com/file/d/1lFvDOs9Qkk6seRv9_cByMzGHuymi7vGh/view). The slides summarize the methodology, experimental setup, results, and conclusions of the classifier comparison.

## Conclusion

Our experiment shows that the Cauchy distribution assumption typically provides better results than the Gaussian distribution assumption.




