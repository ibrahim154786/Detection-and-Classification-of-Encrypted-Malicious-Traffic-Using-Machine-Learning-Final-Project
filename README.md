# Detection and Classification of Encrypted Malicious Traffic Using Machine Learning

## Project Overview
This project investigates how encrypted malicious network traffic can be detected and classified without decrypting the payload. 
It uses publicly available feature-based datasets and applies both traditional machine learning and deep learning techniques to distinguish between malicious and legitimate encrypted traffic.

The study compares conventional models with deep learning architectures and evaluates their performance using standard classification metrics.

## Objectives
- To classify encrypted malicious and legitimate network traffic using feature-based machine learning.
- To compare traditional models (Logistic Regression, Decision Tree, Random Forest) with deep learning models (CNN-1D, LSTM).
- To analyse the impact of resampling techniques (SMOTE) on model performance.

## Dataset
The dataset used in this project is the **Encrypted Traffic Feature Dataset** from Mendeley Data:

Wang, Z., Fok, K.W. and Thing, V.L. (2022)  
The dataset contains packet-based and session-based features extracted from encrypted network traffic collected from multiple public sources.

The dataset includes:
- Packet-level features
- Session-level features
- Binary labels (0 = legitimate, 1 = malicious)

📦 **Note:** The dataset is also provided in this repository in **ZIP format** for convenience.  

or you can download from this website 
[Encrypted Traffic Feature Dataset (Mendeley)](https://[(https://data.mendeley.com/datasets/xw7r4tt54g/1)]
"Encrypted Traffic Feature Dataset for Machine Learning and Deep Learning based Encrypted Traffic Analysis.zip" and upload to your drive.

## Tools and Technologies
- Python
- Google Colab
- cuML (GPU-accelerated machine learning)
- PyTorch (for CNN and LSTM)
- scikit-learn
- Pandas, NumPy, Matplotlib

## How to Run the Code
1. Download or clone this repository.
2. The dataset is provided as a ZIP file.
3. Open the Jupyter Notebook file `traffic_5.ipynb` in **Google Colab**.
4. Upload zip file and traffic_5.ipynb.
5. And Change **zip file path** by your uploaded **"Encrypted Traffic Feature Dataset for Machine Learning and Deep Learning based Encrypted Traffic Analysis.zip"** zip file in drive to your traffic_5.ipynb fil in Colab.
7. Run all cells sequentially from top to bottom.

The notebook will perform:
- Data cleaning and preprocessing
- Feature scaling
- Model training (Machine Learning and Deep Learning)
- Evaluation using accuracy, precision, recall, F1-score, ROC-AUC, confusion matrices, and ROC curves.

## File Structure
- `traffic_5.ipynb`  
  Main notebook containing data preprocessing, model training, evaluation, and result visualisation.


- Dataset ZIP file (`.zip`)  
  Compressed version of the dataset.

## Output
The project generates:
- Performance metrics for each model
- Confusion matrices
- ROC curves
- Comparative tables of model results

These outputs are used to analyse the effectiveness of different models in detecting encrypted malicious traffic.

## Author
Muhammad Ibrahim Khan  

