# Sentiment classification

## Problem Statement :-

Classifying movie reviews from IMDB dataset.

### Deep learning model used :-

For this task I have used BERT model. **Accuracy achieved :- 90.22 % (test set)**

### Project Workflow :-

The general workflow for this project is visualized using the following pic :-

![workflow image](https://raw.githubusercontent.com/subhromitra/sentiment-classification/master/proj_workflow.JPG)

### Experiments coducted :-

**1) Varying token length :-**

| Token length | Test set acc |
|--------------|--------------|
|     224      |     89.3 %   |
|     280      |     90.22 %  |

### Prerequisites:

```
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* PyTorch
* Hugging face transformers library
* Jupyter notebooks
