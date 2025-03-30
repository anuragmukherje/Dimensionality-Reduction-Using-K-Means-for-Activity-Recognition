# Machine Learning Project: Dimensionality Reduction Using K-Means for Activity Recognition
# Improved Activity Recognition with K-Means Clustering

## Objective
Enhancing activity recognition models using high-dimensional sensor data from smartphones by implementing k-means clustering for dimensionality reduction.

## Approach

### Baseline Model
- Constructed an initial model using all 561 features from various smartphone sensors.
- Used Gaussian Naive Bayes for classification.

### Dimensionality Reduction
- Applied k-means clustering to group similar features.
- Reduced the feature set to 65 by selecting representative features from each cluster.
- Normalized the data and re-trained the model using Gaussian Naive Bayes.

## Results

| Model | Features | Accuracy | Training Time |
|--------|---------|----------|--------------|
| Baseline Model | 561 | 73.15% | 0.15 sec |
| K-Means Reduced Model | 65 | 82.53% | 0.01 sec |

## Key Achievements
- **Increased Accuracy**: Improved model accuracy by **11.365%** through effective feature selection.
- **Enhanced Efficiency**: Reduced training time by approximately **92%**, boosting computational efficiency.
- **Feature Reduction**: Streamlined the feature set from **561 to 65**, leveraging k-means clustering to maintain essential information and discard redundancy.
- **Activity Recognition**: Built robust models for Human Activity Recognition using smartphone sensor data.

## Installation

```bash
# Clone the repository
git clone https://github.com/your-repo/activity-recognition-kmeans.git
cd activity-recognition-kmeans

# Install dependencies
pip install -r requirements.txt
```

## Usage

```python
from model import train_model, evaluate_model

# Train and evaluate the model
train_model()
evaluate_model()
```

## Dataset
The dataset used is the **Human Activity Recognition Using Smartphones Dataset** from the UCI Machine Learning Repository.

- Source: [UCI HAR Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)

## Contributing
Feel free to open an issue or submit a pull request if you would like to contribute to this project.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author
[Anurag Mukherjee]
