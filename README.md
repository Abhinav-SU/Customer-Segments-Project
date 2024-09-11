
# Creating Customer Segments

## Overview
This project applies unsupervised learning techniques to segment customers of a wholesale distributor. The goal is to use clustering algorithms like K-Means and Gaussian Mixture Models (GMM) to identify distinct customer segments based on their purchasing behavior.

## Installation

To run this project, you need **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [Matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/). If you don’t have Python installed, I recommend installing the [Anaconda distribution](https://www.anaconda.com/products/individual), which comes with these libraries and more pre-installed.

## Code

The following files are included in this project:
- `customer_segments.ipynb`: Main Jupyter Notebook where the analysis is performed.
- `visuals.py`: Helper script for creating visualizations.
- `customers.csv`: Dataset used for the project.
- `report.html`: An HTML version of the report summarizing the findings.

## Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Customer-Segments-Project.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Customer-Segments-Project
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook customer_segments.ipynb
   ```

## Data

The dataset consists of 440 data points, representing annual spending in various product categories by customers of a wholesale distributor in Lisbon, Portugal. The dataset includes the following features:

- **Fresh**: Annual spending on fresh products (monetary units)
- **Milk**: Annual spending on milk products
- **Grocery**: Annual spending on grocery products
- **Frozen**: Annual spending on frozen products
- **Detergents_Paper**: Annual spending on detergents and paper products
- **Delicatessen**: Annual spending on delicatessen products
- **Channel**: Type of customer {Hotel/Restaurant/Cafe - 1, Retail - 2}
- **Region**: Geographic region {Lisbon - 1, Oporto - 2, Other - 3}

More information about the dataset can be found at the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).

## Project Goals

- **Preprocessing**: Clean and preprocess the dataset for unsupervised learning.
- **Dimensionality Reduction**: Use PCA to reduce the number of features while preserving key information.
- **Clustering**: Apply K-Means and GMM clustering algorithms to segment customers.
- **Cluster Evaluation**: Analyze and interpret the customer segments to make actionable recommendations.

## Results

The clustering algorithms successfully segmented the customer base into distinct groups. The results showed that some customers tend to purchase primarily groceries and detergents, while others focus on fresh and frozen products. By identifying these segments, businesses can tailor their marketing strategies more effectively.

## License

This project is licensed under the MIT License.
