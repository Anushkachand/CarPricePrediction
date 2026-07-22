# 🚗 Car Price Prediction ML App
 
**Predict fair market prices for used cars instantly using Machine Learning.**
 
## [🌐 Live Demo](https://datascienceproject-ccyxqq4mzcdn3r3f7dvygo.streamlit.app/) 
 
## 📖 About
 
A Machine Learning web app that predicts the selling price of a used car based on brand, manufacturing year, kilometers driven, fuel type, transmission, seller type, and ownership history — helping buyers and sellers make data-driven pricing decisions.
 
## ✨ Features
 
- 🚀 Real-time price prediction
- 📊 ML-based estimation from historical sales data
- 🎯 Clean, interactive Streamlit interface
- 🌐 Works on any device, no install needed
## 🛠️ Tech Stack
 
`Python 3.12` · `Pandas` · `NumPy` · `Scikit-learn` · `Streamlit` · `Pickle` · `Git/GitHub`
 
**Frontend:** The entire user interface is built using **Streamlit**, a Python framework that turns data scripts into interactive web apps without needing HTML, CSS, or JavaScript. It powers the input form, prediction button, and result display — making the app fast to build and easy to deploy.
 
## 🎯 How It Works
 
1. Select car brand, year, and kilometers driven
2. Choose fuel type, seller type, transmission, and ownership
3. Click **Predict**
4. View the estimated selling price
## 🤖 ML Workflow
 
```
Raw Data → Cleaning → Missing Value Handling → Feature Selection
        → Categorical Encoding → Model Training → model.pkl → Streamlit App
```
 
## 📊 Dataset
 
Includes: Car Name, Year, Selling Price, Kilometers Driven, Fuel Type, Seller Type, Transmission, Owner Type — cleaned and preprocessed before training.
 
## 📂 Project Structure
 
```
Car-Price-Prediction-ML-App/
│
├── app.py                 # Streamlit application
├── model.pkl              # Trained ML model
├── requirements.txt       # Project dependencies
├── README.md              # Documentation
└── dataset/                # Dataset files
```
 
## 🚀 Getting Started
 
Want to run this project on your own laptop? Just follow these steps one by one — no prior experience needed.
 
**Before you start, make sure you have:**
- [Python](https://www.python.org/downloads/) (3.10 or above) installed on your system
- [Git](https://git-scm.com/downloads) installed to clone the repository
- A code editor like VS Code (optional, but helpful)
### Step 1: Copy the project to your computer
This downloads all the project files from GitHub to your system.
```bash
git clone https://github.com/ANushkachand/Car-Price-Prediction-ML-App.git
cd Car-Price-Prediction-ML-App
```
 
### Step 2: Create a virtual environment
A virtual environment is like a separate, clean box for this project's dependencies — it keeps them from clashing with other Python projects on your system.
```bash
python -m venv venv
```
 
### Step 3: Activate the virtual environment
This "switches on" the box you just created, so any package you install next goes inside it.
 
**Windows**
```bash
venv\Scripts\activate
```
 
**Linux / macOS**
```bash
source venv/bin/activate
```
💡 You'll know it worked if you see `(venv)` appear at the start of your terminal line.
 
### Step 4: Install the required packages
This installs Pandas, Scikit-learn, Streamlit, and everything else the project needs — all listed in `requirements.txt`.
```bash
pip install -r requirements.txt
```
 
### Step 5: Run the app
This starts the Streamlit server and opens the app in your browser automatically.
```bash
streamlit run app.py
```
 
That's it! 🎉 If everything went well, you should see the Car Price Prediction app open at `http://localhost:8501` in your browser.
 
**Common issue:** If `streamlit` isn't recognized, double-check that your virtual environment is activated (Step 3) before running Step 4 and Step 5.
 
## 💡 Future Enhancements
 
- Confidence-interval price ranges instead of a single number
- SHAP-based explainability for predictions
- REST API endpoint for external integrations
- Model comparison (Linear Regression vs Random Forest vs XGBoost)
- Regional price adjustment & depreciation forecasting
## 📈 Use Cases
 
Used car buyers & sellers · Market analysis · Data science portfolio project
 
## 👩‍💻 Author
 
**Anushka Kaushik**
Computer Science Engineering Student — Data Science · AI · Machine Learning
 
- GitHub: [@ANushkachand](https://github.com/ANushkachand)
- LinkedIn: [Anushka Chand](https://www.linkedin.com/in/anushka-chand-18ab44300/)
- Email: [anushkakasuhik0801@gmail.com](mailto:anushkakasuhik0801@gmail.com)
## ⭐ Support
 
If this project helped you, please ⭐ star the repo, 🍴 fork it, and share it with others.
 
## 📜 License
 
This project is created for **educational and learning purposes**.
