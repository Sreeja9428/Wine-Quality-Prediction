# Wine Quality Predictions

## Description
This project focuses on predicting the quality of red wine using various machine learning algorithms for regression analysis, data visualizations, and data analysis. The dataset comprises physicochemical and sensory variables related to red and white variants of the Portuguese "Vinho Verde" wine.

<img src="https://miro.medium.com/max/875/1*2ayKmvVZCYaLPl-nmLLp5g.png" width="400">

## Context
The datasets present a classification or regression task, considering physicochemical inputs and sensory outputs. Notably, the classes are ordered and imbalanced, making it challenging to predict wine quality accurately. Privacy and logistic constraints limit available information to physicochemical and sensory variables, omitting grape types, wine brand, and selling price.

### Content
For detailed information, refer to the [original publication by Cortez et al., 2009](link_to_publication).
**Input Variables (Physicochemical Tests):**
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

**Output Variable (Sensory Data):**
- Quality (Score between 0 and 10)

## Tips
Consider exploring classification tasks by setting a cutoff for wine quality, e.g., classifying scores of 7 or higher as 'good/1' and the rest as 'not good/0'. Experiment with hyperparameter tuning, decision tree algorithms, ROC curves, and AUC values.

### Project Steps
1. **Importing Libraries**
2. **Loading Data**
3. **Understanding Data**
4. **Missing Values**
5. **Exploring Variables (Data Analysis)**
6. **Feature Selection**
7. **Proportion of Good vs Bad Wines**
8. **Preparing Data for Modeling**
9. **Applying Different Models**
10. **Choosing the Right Model**

## Inspiration
Utilize machine learning to identify physicochemical properties that contribute to a wine being classified as 'good'!

## Acknowledgements
The dataset is also available from the [UCI machine learning repository](https://archive.ics.uci.edu/ml/datasets/wine+quality). Please include the citation below if you plan to use this database:

**Citation:** P. Cortez, A. Cerdeira, F. Almeida, T. Matos, and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

## Relevant Publication
P. Cortez, A. Cerdeira, F. Almeida, T. Matos, and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.
