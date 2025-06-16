# 🥕🍎 Fruit & Vegetable Recognition System using TensorFlow & Streamlit

This is a deep learning-based web application that predicts the **type of fruit or vegetable** from an uploaded image and also randomly provides its **freshness status** like **Fresh**, **Medium**, or **Dull**. The app is built using **TensorFlow**, **NumPy**, and **Streamlit**.
## DEMO VIDEO


https://github.com/user-attachments/assets/ac8315a4-3d22-4a88-b320-81bbe1e57742


---

## 📌 Table of Contents

- [🎯 Features](#-features)
- [👥 Team Members](#-team-members)
- [📦 Project Structure](#-project-structure)
- [🧠 Dataset Info](#-dataset-info)
- [⚙️ Setup & Installation](#-setup--installation)
- [▶️ Running the App](#️-running-the-app)
- [🛠 Commands Used](#-commands-used)
- [📈 Future Scope](#-future-scope)
- [📃 License](#-license)

---

## 🎯 Features

✅ Predicts fruit/vegetable type from image  
✅ Randomly shows freshness status  
✅ Simple UI with Streamlit  
✅ Displays prediction confidence  
✅ Trained with custom dataset of fruits & vegetables  
✅ Shows uploaded image before prediction  
✅ Team member information included  

---

## 👥 Team Members

- 👩‍💼 **Team Lead**: Chahath Harshiya  
- 👩 Chandana  
- 👩 Divya  

---

## 📦 Project Structure

Fruit_veg_webapp/
│
├── main.py # Main application code
├── trained_model.h5 # Pretrained CNN model
├── labels.txt # Labels for predicted classes
├── home_img.jpg # Image for homepage display
├── requirements.txt # Dependencies list
└── README.md # You're reading it!


---

## 🧠 Dataset Info

This project uses a custom image dataset with the following details:

### 🔸 Folders

- `train/` — 100 images per class  
- `test/` — 10 images per class  
- `validation/` — 10 images per class  

### 🔹 Classes Included

#### Fruits:
```text
banana, apple, pear, grapes, orange, kiwi, watermelon,
pomegranate, pineapple, mango
Vegetables:
cucumber, carrot, capsicum, onion, potato, lemon, tomato, radish, beetroot,
cabbage, lettuce, spinach, soy bean, cauliflower, bell pepper, chilli pepper,
turnip, corn, sweetcorn, sweet potato, paprika, jalapeño, ginger, garlic, peas, eggplant
⚙️ Setup & Installation
Step 1: Clone the Repository
git clone https://github.com/your-username/fruit-veg-webapp.git
cd fruit-veg-webapp
Step 2: Install Python (Recommended: 3.9.x)
Download Python 3.9.13 from official site

Step 3: Create Virtual Environment
python -m venv venv
Step 4: Activate Virtual Environment
Windows (PowerShell):
venv\Scripts\activate
Windows (CMD):
venv\Scripts\activate.bat
📦 Install Dependencies
Option 1: From requirements.txt
pip install -r requirements.txt
Option 2: Manually install key libraries
pip install streamlit tensorflow numpy
▶️ Running the App
streamlit run main.py
If 'streamlit' is not recognized, use:
python -m streamlit run main.py
🛠 Commands Used
Create Virtual Environment
python -m venv venv
Activate Virtual Environment (PowerShell)
venv\Scripts\activate
Install Streamlit & TensorFlow
pip install streamlit tensorflow numpy
Run the Streamlit App
streamlit run main.py
🧠 How It Works
You upload an image of a fruit or vegetable.

The trained TensorFlow model classifies it.

A random freshness value is selected from:

Fresh

Medium

Dull

A confidence percentage is also displayed.

🔮 Future Scope
Integrate real freshness detection using deep image quality metrics

Improve model to output real confidence on freshness

Add multilingual support

Upload image from camera

Track prediction history

📃 License
This project is for educational purposes only and developed as part of SmartBridge AI/ML Internship.

Created with ❤️ by Chahath Harshiya, Chandana, and Divya


---

Let me know if you want:
- a `requirements.txt` file generated
- the `README.md` downloaded as a file
- your GitHub repo description written

I'm happy to help you wrap this project up smoothly!
