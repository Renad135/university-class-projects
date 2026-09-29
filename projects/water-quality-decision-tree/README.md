# Water Quality Classification with a Decision Tree

A class exercise using a decision tree to classify water samples as safe or unsafe from 20 chemical and biological measurements.

## Method

- Decision tree using entropy, maximum depth 6, and minimum split size 45
- 70/30 train/test split
- Evaluated with a confusion matrix and accuracy

## Reported result

The saved Colab run reported **95.83% accuracy** and a confusion matrix of `[[2084, 35], [65, 215]]`. The split had no fixed random seed, so reruns may produce different results. Recall for class 1 in that run was about **76.8%**.

## Run the notebook

1. Obtain the course dataset `waterQuality1.csv` and place it beside the notebook.
2. Open `water_quality_decision_tree.ipynb` in Google Colab or Jupyter.
3. Run the cells from top to bottom.

The dataset is not included here. This coursework model is for learning and should not be used to make real drinking-water safety decisions.
