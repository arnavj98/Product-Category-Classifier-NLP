# Product-Category-Classifier-NLP

To run the provided script, you need to ensure that you have the necessary packages installed and the dataset (`dummy_products_1000_unique_descriptions.csv`) available in the same directory as the script. Here are the detailed steps and requirements:

pandas==1.3.3
numpy==1.21.2
tensorflow==2.6.0
scikit-learn==0.24.2
matplotlib==3.4.3

Ensure these versions or compatible versions of the libraries to avoid any compatibility issues.

Install them using pip:

```bash
pip install pandas numpy scikit-learn tensorflow matplotlib
```
Prepare the Dataset
Ensure that the dataset file (`dummy_products_1000_unique_descriptions.csv`) in the same directory as script. The dataset should contain the following columns:
- `Name`: Text field for product names.
- `Description`: Text field for product descriptions.
- `Price($)`: Numerical field for product prices.
- `Category`: Categorical field for product categories.

Run the Script
Once the packages are installed and the dataset is prepared, run the script to train the text classification model.
