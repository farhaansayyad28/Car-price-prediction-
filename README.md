# Car Price Prediction 🚗

## Overview

This is a simple Machine Learning project where I built a system to predict car prices based on a few input features.

The project uses a processed dataset and a KNN model to estimate the price, and also includes a small Streamlit app to interact with the model.

---

## Features

- Data cleaning and preprocessing
- Encoding categorical values (fuel type, transmission, etc.)
- Handling missing values
- Model training using KNN Regressor
- Simple UI to input values and get predictions
- Jupyter Notebook for step-by-step understanding

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Streamlit  

---

## Project Structure

carprediction/
│── app.py
│── models.ipynb
│── Car Dataset Processed.csv
│── README.md

---

## How to Run

### Run Locally

1. Clone the repository:
git clone https://github.com/vrushalicbarhate/carprediction.git

2. Go to the project folder:
cd carprediction

3. Install dependencies:
pip install pandas scikit-learn streamlit

4. Run the app:
streamlit run app.py

---

### Run Notebook (Optional)

1. Open Google Colab  
2. Go to File → Open Notebook → GitHub  
3. Paste the repo link  
4. Open models.ipynb  

---

## Dataset

The dataset includes features like:

- Insurance validity  
- Fuel type  
- Transmission  
- Ownership  
- Kilometers driven  
- Price (target)

---

## Notes

- This is a basic project made for learning purposes  
- The model is simple and may not be highly accurate  
- Works well as a demo project  

---

## Future Improvements

- Try better models (Random Forest, etc.)
- Add more features (car brand, year, location)
- Improve UI design
- Deploy the app online

---

## Contributing

Feel free to fork this repository and make improvements.
