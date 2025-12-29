**Iris Species Classification Model**
A machine learning project that predicts Iris flower species (Setosa, Versicolor, Virginica) based on flower measurements using Scikit-Learn. The model is trained in Google Colab and saved as a .pkl file for reuse.

 **Project Overview**
This project demonstrates a complete ML workflow:
Loading and exploring the Iris dataset
Train/Test split for evaluation
Model training using Random Forest Classifier
Accuracy scoring & classification report
Visualization with confusion matrix
Exporting the trained model (iris_model.pkl)

**Repository Structure**
Species-Classification-Model/
notebooks/iris_training.ipynb  
models/iris_model.pkl  
requirements.txt  

**Model Results**
Algorithm	Random Forest Classifier
Accuracy	96%
Classes	Setosa, Versicolor, Virginica

**Technologies Used**
Python
Google Colab / Jupyter
Scikit-Learn
NumPy, Pandas
Matplotlib, Seaborn
Joblib (for saving model)

**How to Run the Notebook**
Open the .ipynb file in Colab or Jupyter
Install dependencies: pip install -r requirements.txt
Run the cells to train the model
The trained model will be saved as: iris_model.pkl

**Saved Model**
Here’s how to load and use the model later:
import joblib
model = joblib.load("iris_model.pkl")
prediction = model.predict([[5.1, 3.5, 1.4, 0.2]])
print(prediction)

**Author**
Santhiya Periyasamy
