# dq_data
Data and code used in the research
# Interpretable Machine Learning for the Prediction of the Death Risk in Patients with Acute Diquat Poisoning

## Overview
This study aims to establish and validate predictive models based on novel machine learning for the death risk in patients with acute diquat (DQ) poisoning and to explain the predictive models using Shapley Additive Explanations (SHAP). We analyzed the initial clinical data of 201 patients admitted for deliberate oral intake of DQ from February 2018 to August 2023. Machine learning methods such as Logistic Regression, Random Forest, Support Vector Machine (SVM), and Gradient Boosting were applied for building prediction models, and SHAP was used to provide an intuitive explanation of the death risk.

## Data and Scripts
We have uploaded the study data and main scripts, which include:
- Data: `dq_data`
- Model Evaluation Metrics: `model_metrics.ipynb`
- ROC Curve: `roc_curve.ipynb`
- Calibration Curve: `calibration_curve.ipynb`
- Clinical Decision Curve Analysis (DCA): `dca_curve.ipynb`
- SHAP Summary: `shap_summary.ipynb`
- SHAP Explanation: `shap_explain.ipynb`

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/liuzheng01/dq_data.git
    cd dq_data
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the model evaluation metrics:
    ```bash
    jupyter notebook model_metrics.ipynb
    ```

4. Plot the ROC curve:
    ```bash
    jupyter notebook roc_curve.ipynb
    ```

5. Plot the calibration curve:
    ```bash
    jupyter notebook calibration_curve.ipynb
    ```

6. Perform Clinical Decision Curve Analysis (DCA):
    ```bash
    jupyter notebook dca_curve.ipynb
    ```

7. Generate SHAP summary:
    ```bash
    jupyter notebook shap_summary.ipynb
    ```

8. Perform SHAP explanation:
    ```bash
    jupyter notebook shap_explain.ipynb
    ```

## Results
The study found that the Random Forest model had the best predictive performance with an AUC of 0.98. SHAP analysis identified key features such as Cr, PaCO2, DQ dose, lactic acid, and white blood cell count (WBC) as important factors in predicting the death risk in patients with acute DQ poisoning.

## Contact
For any questions or further information, please contact:
- **Zheng Liu**: zhengliu@cmu.edu.cn

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
This research was supported by the National Natural Science Foundation of China (#81971821).
