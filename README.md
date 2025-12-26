# KNN from Scratch – Diamond Dataset

##  Overview
This project demonstrates a **manual implementation of the K‑Nearest Neighbors (KNN) algorithm** using Python, applied to the **Diamond dataset**. The goal is to understand how KNN works internally by coding it step‑by‑step without relying on external machine learning libraries. The implementation covers both **classification** and **regression** tasks, with comparisons against scikit‑learn’s KNN models for validation.


##  Dataset
- **File**: `diamonds.csv`  
- **Features**:  
  - Numerical: carat, depth, table, x, y, z  
  - Categorical: cut, color, clarity  
- **Target Variable**: price (regression) or categorical attributes (classification)

##  Implementation Workflow
1. **Data Loading & Exploration**  
   - Import dataset with Pandas  
   - Inspect structure, summary statistics, and feature distributions  

2. **Preprocessing**  
   - Handle missing values  
   - Encode categorical variables (cut, color, clarity)  
   - Scale numerical features for distance calculations  

3. **Distance Metrics**  
   - Euclidean distance  
   - Manhattan distance  
   - Generalized to n‑dimensional space  

4. **KNN Algorithm (Scratch)**  
   - Calculate distances between points  
   - Select k nearest neighbors  
   - Apply majority voting (classification) or averaging (regression)  

5. **Evaluation**  
   - Metrics: Accuracy, MAE, RMSE  
   - Compare scratch implementation with scikit‑learn’s `KNeighborsClassifier` and `KNeighborsRegressor`  


##  Results
- Scratch KNN achieves performance comparable to scikit‑learn’s implementation  
- Highlights importance of preprocessing and feature scaling  
- Demonstrates trade‑offs in distance metrics and choice of k  

##  Key Learnings
- How distance‑based algorithms work internally  
- Importance of feature scaling in KNN  
- Handling categorical and numerical features together  
- Performance trade‑offs in brute‑force KNN  
