
# Climate Data Regression Analysis  

This project applies regression techniques to analyze a time series of climate measurements. Both linear and nonlinear regression models are implemented, with and without regularization methods such as L1 (Lasso) and L2 (Ridge). The goal is to identify the most effective approach for capturing data trends and making accurate predictions.  

## Project Overview  

The study evaluates the performance of various regression models in terms of their ability to generalize and avoid overfitting. By comparing models with and without regularization, the impact of these techniques on model complexity and prediction accuracy is assessed.  

Key aspects of the project include:  
- Implementation of **linear regression** models.  
- Exploration of **nonlinear sinusoidal regression** to capture periodic trends.  
- Use of **L1 (Lasso)** and **L2 (Ridge)** regularization to improve generalization.  
- Evaluation of models using the **Mean Squared Error (MSE)** metric.

  
![output](https://github.com/user-attachments/assets/eadb5123-de00-4050-8dc6-b0d812adfb83)



## Repository Structure  

- **`code/`**: Contains the implementation scripts for regression models and data preprocessing.  
- **`data/`**: Includes the dataset used for climate analysis.
- **`report/`**: Contains the project report detailing the methodology, results, and analysis.  
- **`README.md`**: This file.

## Dependencies  

To run the code, ensure you have the following Python libraries installed:  
- `numpy`  
- `pandas`  
- `matplotlib`  
- `seaborn` 

Install the required packages using:  
```bash  
pip3 install -r requirements.txt  
```  

## Usage  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/darkblackv32/ml-regression-project
   cd ml-regression-project
   ```  

2. Navigate to the `code/` directory and run the desired script to execute the regression models.  

## Results 

The study compares the performance of models in terms of MSE, highlighting the trade-offs between model complexity, generalization, and prediction accuracy. The findings can guide the selection of appropriate regression techniques for similar time series data.

## Keywords  

Regression, Regularization, MSE  

## License  

This project is licensed under the MIT License. See the `LICENSE` file for details.  
