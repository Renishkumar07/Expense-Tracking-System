# 💰 Expense Management System

A simple **expense tracking application** with a **Streamlit frontend** and a **FastAPI backend**.  
This project helps users log and visualize their expenses in an intuitive UI.  

---

## 📂 Project Structure

```plaintext
expense-management-system/
├── frontend/         # Streamlit app code
├── backend/          # FastAPI backend code
├── tests/            # Test cases for frontend & backend
├── requirements.txt  # Python dependencies
└── README.md         # Project overview & instructions

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn backend.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py

   ```
