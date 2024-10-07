# Linear-Algebra---Project-11

# Sure Tomorrow Insurance Prediction Project

### Description
This project is aimed at helping the "Sure Tomorrow" insurance company solve multiple business problems using machine learning techniques. The tasks include predicting customer similarity, insurance benefit likelihood, and obfuscating personal data without affecting model performance.

### Project Structure
- **notebook.ipynb**: This notebook contains all the steps for data preprocessing, model training, evaluation, and data obfuscation techniques.
- **/datasets/**: Contains the datasets used for model training and testing.
- **/output/**: Stores outputs such as predictions, model performance metrics, and data obfuscation results.

### Objectives
The main objectives of the project are:
1. **Task 1: Customer Similarity**:
   - Identify customers similar to a given customer to aid in personalized marketing efforts.
   
2. **Task 2: Insurance Benefit Prediction**:
   - Build a classification model to predict whether a new customer is likely to receive an insurance benefit and compare its performance to a dummy model.

3. **Task 3: Predict Number of Insurance Benefits**:
   - Use linear regression to predict the number of insurance benefits a new customer is likely to receive.

4. **Task 4: Data Obfuscation**:
   - Develop a data transformation algorithm (data masking) to protect personal client information, ensuring that the model's performance remains unaffected.

### Findings
- **Customer Similarity**: Successfully identified similar customers using clustering and distance metrics, providing insights for targeted marketing.
- **Insurance Benefit Prediction**: The model outperformed the dummy classifier, demonstrating the viability of machine learning for predicting insurance benefits.
- **Linear Regression for Benefits**: Achieved reasonably accurate predictions of the number of benefits using linear regression.
- **Data Obfuscation**: Developed a data masking algorithm that effectively protected sensitive customer data without reducing model performance.

### Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sure-tomorrow-insurance-prediction.git
2. Install the required dependencies
   pip install -r requirements.txt
3. Launch Jupyter Notebook
   jupyter notebook
