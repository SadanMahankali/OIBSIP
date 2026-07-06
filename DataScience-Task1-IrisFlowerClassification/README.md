# Task 1 - Iris Flower Classification

## Objective

Given a flower's measurements, predict which of three iris species it is (setosa, versicolor, virginica). It's a supervised classification problem.

## Dataset

The classic Iris dataset, loaded straight from scikit-learn (no download needed).
- 150 flowers
- 3 species (50 of each)
- 4 features per flower: sepal length, sepal width, petal length, petal width

## Approach
1. Load the data and explore it, checking it's clean (shape, types, no missing values).
2. Visualises it (pairplot + box plots) to see which features seperate the species.
3. Split the data 80/20 into train and test sets (stratified, since it's sorted by species).
4. Build and train two classifiers, K-Nearest Neighbours and a Decsion Tree.
5. Test each on the held-out data and evaluate (accuracy, confusion matrix, classification report).
6. Cross-validate both to compare them fairly, then pick the best.
7. Refit the best model on all the data and save it as the final model.

## Results

- **KNN was the best model.** On the single train/test split it hit 100%, but 5-fold cross-validation gave us a more honest ~97% (the Decision Tree got ~95%).
- **Petal length was the most useful feature** for seperating species; sepal width the least.
- **Setosa** was completely seperated from the other two, while **versicolor** and **virginica** overlapped slightly, which is exactly where the Decision Tree made its only 2 mistakes.

## How to run

    pip install -r requirements.txt

Then open the notebook and run the cells top to bottom:

    SadanMahankali_Task1.ipynb

## Files
- 'SadanMahankali_Task1.ipynb' - the full analysis notebook
- 'data/' - the dataset
- 'models/' the saved final model ('.joblib')
- 'README.md' - this file