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
Please extract (unzip) the dataset files before running the notebook.

or you can download from this website 
[Encrypted Traffic Feature Dataset (Mendeley)](https://[(https://data.mendeley.com/datasets/xw7r4tt54g/1)]


## Tools and Technologies
- Python
- Google Colab
- cuML (GPU-accelerated machine learning)
- PyTorch (for CNN and LSTM)
- scikit-learn
- Pandas, NumPy, Matplotlib

## How to Run the Code
1. Download or clone this repository.
2. If the dataset is provided as a ZIP file, **extract (unzip) it** into the project directory.
3. Open the Jupyter Notebook file `traffic_5.ipynb` in **Google Colab** or **Jupyter Notebook**.
4. Upload or ensure the extracted dataset CSV files are in the working directory.
5. Run all cells sequentially from top to bottom.

The notebook will perform:
- Data cleaning and preprocessing
- Feature scaling
- Model training (Machine Learning and Deep Learning)
- Evaluation using accuracy, precision, recall, F1-score, ROC-AUC, confusion matrices, and ROC curves.

## File Structure
- `traffic_5.ipynb`  
  Main notebook containing data preprocessing, model training, evaluation, and result visualisation.

- Dataset files (`.csv`)  
  Packet-based and session-based encrypted traffic feature datasets.

- Dataset ZIP file (`.zip`)  
  Compressed version of the dataset. Must be extracted before use.

## Output
The project generates:
- Performance metrics for each model
- Confusion matrices
- ROC curves
- Comparative tables of model results

These outputs are used to analyse the effectiveness of different models in detecting encrypted malicious traffic.

## Author
Muhammad Ibrahim Khan  

