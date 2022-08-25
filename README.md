# XG-Boost-document-similarity-using-fuzzzy-features

Million's of people visit the web every month, so it's no surprise that many people anter similarly worded queries. Multiple textual statements with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question.

#### Problem Statement
- We are tasked with predicting whether a pair of textual statements(question pairs) are duplicates or not.

### Approach:
**1) Basic Feauture Extraction**
- Exploratory Data Analysis.
- Basic Feature Engineering(Constructing new features).
- Analysis of Extracted Features.

**2) Advanced Feaure Engineering**
- Preprocessing of text(expanding contractions etc)
- Extracting Fuzzy Features

**3) Featurizing Text**
- Extract weighted word-vectors using TF-IDF

**4) ML Modelling**
- Baseline Model
- Logistic Regression
- Linear SVM
- XG Boost
