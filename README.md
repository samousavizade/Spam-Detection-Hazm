# Dependencies

- Hazm `hazm`
- OS `os`
- Pandas `pandas`
- Matplotlib `matplotlib`
- RegEx `re`
- Seaborn `seaborn`
- WordCloud Farsi `wordcloud-fa`
- tqdm `tqdm`
- itertools `itertools`
- collections `collections`
- SciKit Learn `sklearn`

---

# Dataset

Dataset is available through `train.csv` and `test.csv` files in root directory.

---

# Project Definition

In this project, the issue of email English **Spam Detection** is investigated. (using `hazm` Preprocessing and `TF-IDF` Word Vectorization)

Data are given in train and test parts. Training dataset has `Text` and `Class` columns, the first column of which is the tet of the email and the second column is the class related to that email. (A value of 0 indicates that the email is not spam and a value of 1 indicates that the email is spam.)

Using this data, a model is designed that can distinguish spam emails from non-spam ones. After training the model on the training data, the model predictions on the test data are stored in a file named `submission.csv`.

---

# Report

The report of this project is available in the jupyter notebook form in `spam_detection.ipynb`.

