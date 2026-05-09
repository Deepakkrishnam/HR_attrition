HR Attrition Prediction 📋
This project is a Machine Learning application designed to predict the likelihood of employee attrition. By analyzing key organizational metrics and employee data, the tool helps HR departments identify at-risk talent and improve retention strategies.  

🚀 Live Demo
Access the interactive web application here:


HR Attrition Prediction App   

🛠️ Tech Stack

Frontend: Streamlit   


Machine Learning: Scikit-learn (using kr_model.pkl)   


Programming Language: Python   

📁 Project Structure

app.py: The core Streamlit script managing the user interface and prediction logic.  


kr_model.pkl: The serialized machine learning model used for generating predictions.  


HR attrition.txt: Project documentation and deployment metadata.  

📋 Features

Dynamic Prediction: Input employee parameters to receive a real-time assessment of attrition risk.  


Automated Interface: A clean, sidebar-driven UI for easy data entry.  


Cloud Deployment: Fully hosted on Streamlit Cloud for instant accessibility.  

⚙️ Installation & Local Setup
To run this project locally, follow these steps:

Clone the repository:

Bash
git clone https://github.com/your-username/hr-attrition-prediction.git
cd hr-attrition-prediction
Install the required dependencies:

Bash
pip install -r requirements.txt
Run the application:

Bash
streamlit run app.py
💡 Recommendation
Ensure you have a requirements.txt file in your repository. Based on your app.py, it should at least include:

streamlit

pandas

scikit-learn

pickle-mixin (or just pickle)
