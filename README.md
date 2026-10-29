# DS-401 Project 🚀

An end-to-end data science project developed as part of the **DS-401** course. This project encompasses data preprocessing, model training, and deployment of a machine learning model using **FastAPI**, with deployment facilitated via **Vercel**.

---

## 📌 Project Overview

### Team
1. Muhammad Hanzala Bin Rehan (461738)
2. Muhammad Abdullah Waleed Ahmed Janjua (459244)
3. Muhammad Arshyan Khan (462685)
4. Khadija Faisal (467936)

**Objective**  
Develop a machine learning pipeline that includes data preprocessing, model training, and deployment.

**Technologies Used**
- **Programming Language:** Python  
- **Framework:** FastAPI  
- **Deployment:** Vercel  
- **Others:** Jupyter Notebook

---

## 📁 Repository Structure

```
DS-401-Project/
├── content/               # Data files and related content
├── notebooks/             # Jupyter notebooks for EDA and model development
├── templates/             # HTML templates for the FastAPI application
├── app.py                 # Main FastAPI application script
├── asgi.py                # ASGI configuration for deployment
├── train.py               # Script for training the machine learning model
├── requirements.txt       # Python dependencies
├── vercel.json            # Vercel deployment configuration
```

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/HanzalaRehan/DS-401-Project.git
cd DS-401-Project
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Train the Model
```bash
python train.py
```

### 5. Run the Application
```bash
uvicorn app:app --reload
```

Visit the application at: [http://localhost:8000](http://localhost:8000)

---

## 🌐 Deployment

The application is deployed on Vercel and can be accessed here:  
👉 [expo-project-nu.vercel.app](https://expo-project-nu.vercel.app)

---

## 📊 Notebooks

The `notebooks/` directory contains Jupyter notebooks that provide insights into:
- Data exploration  
- Preprocessing steps  
- Model development

---

## 🤝 Contributing

Contributions are welcome!  
Please fork the repository and submit a pull request for any enhancements or bug fixes.

---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.