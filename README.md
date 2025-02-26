# CxC-Datathon
This was our data analysis for the TouchBistro Challenge in the CxC Datathon.
The ipynb file was simply exported from Colab

## Preprocessing
- **KNNImputor** was used to fill in missing values
- target and feature encoding was used to turn categorical and datetime data to numbers
- We scaled time data to be relative to each other

## Technologies Used
- scikit-learn
- numPy 
- pandas
- matplotlib
- PyTorch

## Training
- **Grid Search** was used to optimize hyperparameters for various classical/ensemble/boosting models like **Adaboost, XGBoost, and Random Forest**
- We tried out an **LSTM** in **PyTorch**, but opted to mainly focus on classical models 

## Visualization
- We used matplotlib to visualize model performance and feature importance 