# Detecting Fake Reviews across E-Commerce Websites - A Comparative Study
## Machine Learning - CS584

## Overview
This is research project, led by Fateen, Wali and Riyaz, applies machine learning to distinguish between real and AI-generated reviews, focusing on Amazon products.

## Key Components
1. **Data Preparation**: Cleaning and balancing the dataset, including feature extraction like user IDs, word counts, and sentiment analysis.
2. **Review Generation**: Utilizing OpenAI's `text-davinci-003` to generate synthetic reviews.
3. **Feature Engineering**: Creating and analyzing features like review length, sentiment, and word frequency.
4. **Machine Learning Models**:
   - `Detecting_AI_Reviews.ipynb`: Utilizes Logistic Regression, Naive Bayes, and a Feed-Forward Neural Network.
   - `Detecting_Fake_Reviews.ipynb`: Employs Random Forest, SVM, Decision Tree, and Gradient Boosting.
5. **Visualization and Correlation Analysis**: Understanding feature relationships through heatmaps and other visualizations.

## Data Generation
- **OpenAI GPT Model**: Generates synthetic reviews, labeled as 'fake', to augment the dataset.

## Model Evaluation
- Evaluation using metrics like accuracy, precision, recall, and F1-score.
- Cross-validation for robust model assessment.

## Visualization
- Correlation matrices, bar charts, and violin plots to understand data distributions and feature interactions.

## How to Use
1. Clone the repository.
2. Install necessary libraries: pandas, NumPy, scikit-learn, textblob, nltk, seaborn, matplotlib, torch.
3. Run the Jupyter Notebooks and Python scripts in order.

## Acknowledgements
This research is part of the CS 584 curriculum, with gratitude to instructors and peers for their support.
