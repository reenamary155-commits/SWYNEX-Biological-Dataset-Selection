# SWYNEX – Biological Dataset Selection

## 1. Selected Dataset
*Breast Cancer Wisconsin (Diagnostic) Dataset*

- *Source:* UCI Machine Learning Repository (open, public, no login required)
- *Link:* https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
- *Also available in:* scikit-learn (sklearn.datasets.load_breast_cancer) and Kaggle
- *Type:* Tabular numeric data derived from digitized images of fine needle aspirate (FNA) of breast masses

## 2. Dataset Size
- *Samples:* 569
- *Features:* 30 numeric features (mean, standard error, and "worst" value of 10 cell-nucleus measurements: radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, fractal dimension)
- *Target:* Diagnosis (Malignant = 212, Benign = 357)
- *Missing values:* None
- *File size:* Small (well under 1 MB)

## 3. Research Question
> Can the measured characteristics of cell nuclei be used to accurately distinguish malignant tumors from benign tumors, and which features are most predictive of malignancy?

### Sub-questions
1. Which nucleus features differ most between malignant and benign samples?
2. How well can a simple model (e.g., logistic regression) classify the diagnosis?
3. Are the features highly correlated with each other (redundancy)?

## 4. Why This Dataset
- Public, well-documented, and widely cited in biomedical research
- Clean and small, suitable for quick exploration
- Clear biological meaning: nuclear size and shape irregularity are hallmarks of malignancy

## 5. Scope
- *No lab work.* This task only involves selecting and documenting an existing public dataset.
- No data was collected or modified by me.

## 6. Citation
Wolberg, W., Mangasarian, O., Street, N., & Street, W. (1995). Breast Cancer Wisconsin (Diagnostic). UCI Machine Learning Repository.
