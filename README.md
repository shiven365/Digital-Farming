# HackNUThon: Soil Spectrometer Analyzer 🔬🌱

An advanced soil analysis system that utilizes spectroscopic data to assess soil health and fertility. By analyzing wavelength readings from a soil spectrometer, the system predicts essential soil parameters such as moisture content, electrical conductivity, temperature, NPK (Nitrogen, Phosphorus, Potassium), and pH levels. Machine learning algorithms are used to find correlations between spectral data and sensor readings, providing farmers with actionable insights for precision agriculture. The results are displayed through a user-friendly web interface, enabling efficient soil monitoring and sustainable farming practices.

## 📸 Screenshots

Here is a preview of the application's interface.

**1. Data Input Form:** The main interface for entering spectrometer readings.
<img src="https://github.com/user-attachments/assets/b1db8a38-7382-492e-b8f5-c5bcfdf72ddc" alt="Soil Spectrometer Analyzer Input" width="500"/>

**2. Soil Analysis Results:** Displays the predicted values for various soil attributes.
<img src="https://github.com/user-attachments/assets/bbb1e54d-822f-4ccc-a421-0d2512d6e6c0" alt="Soil Analysis Results" width="500"/>

**3. Model Performance Metrics:** Performance metrics (MAE, RMSE, R²) for the underlying machine learning models.
<img src="https://github.com/user-attachments/assets/88d536a6-598a-4c44-afc7-8dc506f0e741" alt="Model Performance Metrics" width="500"/>

---

## 🚀 How to Run the Website and Model

### **BACKEND SETUP**

1.  Navigate to the backend folder:
    ```sh
    cd backend
    ```

2.  Create a Python virtual environment:
    ```sh
    python -m venv model
    ```

3.  Activate the virtual environment:
    ```sh
    .\model\Scripts\activate
    ```

4.  After activating, install the required dependencies:
    ```sh
    pip install flask flask-cors lightgbm pandas numpy scikit-learn optuna joblib gunicorn google-generativeai python-dotenv
    ```

5.  Run the backend server (while the virtual environment is active):
    ```sh
    flask run
    ```

---

### **FRONTEND SETUP**

1.  Navigate to the frontend folder:
    ```sh
    cd frontend
    ```

2.  Install dependencies using npm:
    ```sh
    npm install
    ```

3.  Run the frontend development server:
    ```sh
    npm run dev
    ```
