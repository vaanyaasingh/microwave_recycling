##  **Microwave-Assisted Polycarbonate Recycling with AI/ML Optimization**

## **Project Overview**
This project focuses on the microwave-assisted recycling of polycarbonate plastics. By leveraging AI/ML models, we aim to optimize process parameters and predict recycling outcomes. The goal is to enhance efficiency, reduce energy consumption, and improve yield quality.

## **Dataset Information**
The dataset used for this project is `Microwave_Recycling_Dataset1.csv` located at `/Users/vaanya/Desktop/mse_el/`. It contains the following columns:
- Microwave Power (W)
- Reaction Temperature (°C)
- Reaction Time (minutes)
- Catalyst Type
- Catalyst Concentration (%)
- Polycarbonate Composition (%)
- Contaminant Levels (%)
- Yield of Liquid Oils (%)
- Yield of Syngas (liters)
- Yield of Solid Residues (char in %)
- Energy Consumption (kWh)
- Process Efficiency (%)

## **Project Structure**
- **data/**: Contains `Microwave_Recycling_Dataset1.csv`
- **notebooks/**: Jupyter notebooks for EDA and modeling
- **models/**: Saved AI/ML models
- **src/**: Source code for data processing and modeling
- **streamlit_app/**: Streamlit app for visualization and predictions
- **README.md**: Project documentation (this file)

## **AI/ML Model Overview**
- **Objective:** Predict yields and efficiency from input parameters.
- **Modeling Approach:**
  - Exploratory Data Analysis (EDA)
  - Feature Engineering
  - Model Training (e.g., Random Forest, Gradient Boosting, Neural Networks)
  - Hyperparameter Tuning
- **Model Evaluation:** Using metrics such as RMSE, MAE, and R-squared.

## **Streamlit Web Application**
A Streamlit-based web app is developed to visualize the dataset and predict recycling outcomes. Key features include:
- Interactive input fields for process parameters
- Real-time predictions for yield and efficiency
- Visualizations of process trends and results

## **Installation and Usage**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/microwave-recycling.git
   cd microwave-recycling
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Streamlit app:**
   ```bash
   streamlit run streamlit_app/app.py
   ```

## **Contributors**
- Vaanya

## **License**
This project is licensed under the MIT License.
