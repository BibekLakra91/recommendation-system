
# Personalised Recommendation System for a Content Feed

This repository contains code for building a recommendation system after finding similarity measurements using cosine similarity. The model undergoes training using 70% of the provided dataset.

## Data

The dataset used for this recommendation system is provided in the "Assignment - ML - Supporting Data.xlsx" file. It includes information about items, user interactions, and other relevant features.

## Requirements

Make sure you have the required libraries installed. You can install them using the following command:

```bash
pip install pandas numpy scikit-learn
```
**OR**
```bash
conda install pandas numpy scikit-learn
```
## Running the Code

1. Open the Jupyter Notebook `Recommendation_System.ipynb`.
2. Run the cells in the notebook to load the dataset, preprocess features, and train the recommendation system.
3. The system calculates cosine similarity between items and predicts interactions based on a specified threshold.
4. The accuracy of the recommendation system is evaluated using the test set.

## Code Structure

- `Recommendation_System.ipynb`: Jupyter Notebook containing the code for building and testing the recommendation system.
- `README.md`: Documentation file providing information about the project, data, requirements, and how to run the code.

## Important Functions

- `important_features(dataset)`: A function to preprocess features in the dataset by combining 'tags' and 'hashtags' into a single 'feature' column.

## Results

The recommendation system achieved an accuracy of 98% on the test set. Adjustments to the similarity threshold and interaction rates can be made based on specific requirements.

