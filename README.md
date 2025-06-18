# PROG8245 – Lab 5  
# 🏡 Min-Max Normalization Workshop

## 📁 Dataset Description

This project demonstrates **manual Min-Max normalization** applied to a housing dataset. The dataset includes real estate listings with various numeric features such as:

- `Price` – Selling price of the house (in CAD)
- `Area_sqft` – Total area of the house in square feet
- `Num_Bedrooms` – Number of bedrooms
- `Num_Bathrooms` – Number of bathrooms
- `Lot_Size` – Size of the property lot in square feet

Min-Max normalization ensures that each feature contributes equally to machine learning models by rescaling all values to a common range, typically [0, 1].

---

## 👥 Team Members

- Kapil  
- Paula  
- Parag

---

## 🔗 Dataset & License

- **Dataset Source**: `housing_data.csv` (located in the `Data/` folder)
- **License**: For educational use only

### 🧾 Dataset Overview

| Column Name       | Description                                       |
|-------------------|---------------------------------------------------|
| `House_ID`        | Unique identifier for each house                  |
| `Price`           | Market price of the house (CAD)                   |
| `Area_sqft`       | Size of the house in square feet                  |
| `Num_Bedrooms`    | Number of bedrooms                                |
| `Num_Bathrooms`   | Number of bathrooms                               |
| `Year_Built`      | Year the house was built                          |
| `Lot_Size`        | Size of the property lot in square feet           |

---

## 🚀 How to Run

1. Clone the repository and navigate to the project folder.
2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
   .\venv\Scripts\activate  # On Windows
   pip install -r requirements.txt
