# Amazon User Segmentation

This repository implements K-Means clustering to segment users from an Amazon e-commerce dataset based on their characteristics.

## Features:

Analyzes user data including annual income, purchase rating, and age.
Applies the Elbow Method to determine the optimal number of clusters.
Visualizes the segmentation results using scatter plots.

## Requirements:

* Python 3.x
* Libraries: numpy, pandas, matplotlib, sklearn

## How to Use:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ar-archith/Amazon-User-Segmentation.git
2. **Install Libraries:**
   ```bash
   pip install numpy pandas matplotlib scikit-learn
3. **Run the Script:**
   Open the `Amazon_User_Suggestion.ipynb` file in your preferred Jupyter Notebook environment and execute the code cells.

## Data:

The script assumes a CSV file named `Amazon_com.csv` exists in the same directory. This file should contain user data with relevant attributes for segmentation.

## Note:

This script provides a basic example of user segmentation using K-Means clustering. Further exploration can involve incorporating additional user features and evaluating different clustering algorithms.

Feel free to explore the code and modify it for your specific needs!

## Additional Information:

The code performs user segmentation using two different feature sets: annual income and purchase rating, and age and purchase rating.
The Elbow Method is used to determine the optimal number of clusters (4 in this case).
The script visualizes the clusters using scatter plots with different colors and labels.
