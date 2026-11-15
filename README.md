# Machine Learning Coursework

Coursework for the 2023/24 BSc Computer Science machine learning module at the University of Bristol. The notebook explores classification, sequence labelling, clustering, dimensionality reduction and Bayesian regression.

## Explore

- [Browse the notebook](coursework-view.ipynb): a lightweight copy with code and narrative preserved and cell outputs cleared for easier viewing on GitHub.
- [Original notebook with outputs](coursework.ipynb): the complete original, which is large and may need to be downloaded to view.
- [Coursework report](machine_learning.pdf): the original report, awarded 76.

The experiments include neural networks and decision-tree ensembles for activity recognition, a hidden Markov model, PCA and Gaussian mixtures, SVM classifiers, and Bayesian linear regression.

## Running the notebook

Open either notebook in Jupyter. The code imports NumPy, pandas, Matplotlib, scikit-learn, hmmlearn, PyMC, PyTensor and other libraries; it does not include a pinned environment. The activity-recognition section expects `activity_recognition_dataset/S1_Dataset` relative to the notebook, which is not included in this repository. Other cells fetch data or need additional packages; inspect the cells before running them. Results may depend on library versions and external data availability.
