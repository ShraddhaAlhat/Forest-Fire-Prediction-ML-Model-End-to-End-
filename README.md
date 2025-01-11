# Algerian Forest Fire Prediction  

A Machine Learning model to predict the **Fire Weather Index (FWI)** based on environmental attributes. This project utilizes Ridge Regression for high accuracy and incorporates a Flask-based frontend to provide an intuitive user interface.  
<p align="center">
  <img src="https://raw.githubusercontent.com/ShraddhaAlhat/Forest-Fire-Prediction-ML-Model-End-to-End-/main/dataset-cover.jpg" alt="Image Description" width="300" height="200">
</p>


---

## Dataset Overview  

The dataset contains **244 instances** collected from two regions in Algeria:  
- Bejaia (Northeast Algeria)  
- Sidi Bel-Abbes (Northwest Algeria)  

The data covers the period from **June 2012 to September 2012**.  
Key details:  
- **Attributes**: 11 input features, including temperature, humidity, wind speed, and more.  
- **Output**: Fire classification (Fire: 138 instances, Not Fire: 106 instances).  

---

## Models Used  

1. **Linear Regression**  
2. **Lasso Regression**  
3. **Ridge Regression** (Chosen Model - Best Accuracy)  

The Ridge model and StandardScaler were saved as `.pkl` files for deployment.  

---

## Features  

- **Prediction Model**: Predicts Fire Weather Index (FWI).  
- **Frontend**: Built using Flask for interactive predictions.  

---

## Installation  

### Steps to Run the Project:  

1. **Clone the Repository**:  
   Clone the project from GitHub using the following command:  
   ```bash
   git clone https://github.com/YourUsername/Forest-Fire-Prediction.git
2. **Navigate to the Project Directory:**:    
   ```bash
   cd Forest-Fire-Prediction
3. **Run the Jupyter Notebook:**:
  - Navigate to the `notebook` folder:
    
    ```bash
     cd notebook
    ```
  - Open the file `Algerian Case Study.ipynb` in Jupyter Notebook or any compatible IDE.
  - Run all the cells to preprocess the dataset and generate the required model files:
     -  `Models/scaler.pkl`
     - `Models/ridge.pkl`
4. **Install Dependencies:**
 - Install all required Python libraries using the following command:
   ```bash
     pip install -r requirements.txt
   ```
5. **Run the Flask Application:**
- Navigate back to the root folder:
  ```bash
   cd ..
  ```
- Run the Flask app using the following command:
  ```bash
   python Application.py
  ```
6. **Access the Application:**
 - After running Application.py, a URL will be displayed in the terminal (e.g., http://127.0.0.1:5000/).
 - Click on the URL to open the application in your browser.
---
### Screenshots

- **Frontend Output:**
  <p align="center">
  <img src="https://raw.githubusercontent.com/ShraddhaAlhat/Forest-Fire-Prediction-ML-Model-End-to-End-/main/Screenshot (22).png" alt="Image Description" width="900" height="500">
</p>

## Conclusion:
  This project demonstrates the use of machine learning in predicting forest fires based on environmental factors. The deployment of the Ridge Regression model provides an effective solution for assessing 
  fire risk and can be extended to real-time applications.



---

   
