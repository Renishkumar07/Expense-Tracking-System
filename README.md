# 💰 Expense Management System

A simple **expense tracking application** with a **Streamlit frontend** and a **FastAPI backend**.  
This project helps users log and visualize their expenses in an intuitive UI.  


## 📂 Project Structure

```plaintext
expense-management-system/
├── frontend/         # Streamlit app code
├── backend/          # FastAPI backend code
├── tests/            # Test cases for frontend & backend
├── requirements.txt  # Python dependencies
└── README.md         # Project overview & instructions
```


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
2. **Install dependencies:**:   
   ```bash
    pip install -r requirements.txt
   ```
3. **Run the FastAPI server:**:   
   ```bash
    uvicorn backend.server:app --reload
   ```
4. **Run the Streamlit app:**:   
   ```bash
    streamlit run frontend/app.py

