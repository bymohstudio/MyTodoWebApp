# 📝 MyTodoWebApp  

A simple and interactive **Python To-Do web application** built using **Streamlit**.  
This project was created as part of my Python learning journey through a **Udemy course**, where I explored file handling (reading/writing), state management, and building user interfaces with Streamlit.  

---

## 🚀 Features  

- ✅ **Add Tasks** – Add new to-do items through an easy Streamlit UI.  
- 🗑️ **Delete Tasks** – Remove completed or unnecessary tasks dynamically.  
- 💾 **Persistent Storage** – Saves tasks in a local text file using Python file handling (`open()`, `read()`, `write()`).  
- ⚡ **Real-Time Updates** – Automatically refreshes the task list after every action.  
- 🎨 **Minimal & Fast Interface** – Powered by Streamlit for instant UI rendering.  

---

## 🧠 What I Learned  

- 📘 How to read and write files in Python using file modes (`r`, `w`, `a`).  
- 🧩 Basics of Streamlit components (`st.text_input`, `st.button`, `st.checkbox`).  
- ⚙️ Managing app state and user input in Streamlit.  
- 🗂️ Structuring a small Python project for maintainability.  

---

## 🧰 Tech Stack  

- **Language:** Python 🐍  
- **Framework:** Streamlit  
- **Storage:** Local text file (`todos.txt`)  

---

## 🧭 Project Structure  

```
MyTodoWebApp/
│
├── todo_app.py          # Main Streamlit app
├── functions.py         # Helper functions for reading/writing tasks
├── todos.txt            # Local file storing task list
└── README.md
```

---

## ⚙️ How to Run  

1. **Clone the Repository**
   ```bash
   git clone https://github.com/bymohstudio/MyTodoWebApp.git
   cd MyTodoWebApp
   ```

2. **Create and Activate a Virtual Environment**
   ```bash
   python -m venv env
   source env/bin/activate  # macOS/Linux
   env\Scripts\activate     # Windows
   ```

3. **Install Dependencies**
   ```bash
   pip install streamlit
   ```

4. **Run the App**
   ```bash
   streamlit run todo_app.py
   ```

5. **Open in Browser**
   Streamlit will open automatically, or go to:  
   👉 [http://localhost:8501](http://localhost:8501)

---

## 💡 Example  

**Add a Task:**  
Type your task in the input box → Click **Add** ✅  

**Mark as Done:**  
Check the box next to a task → It disappears from the list and updates the file automatically.  

---

## 🧾 License  

This project was created for educational and personal learning purposes while completing a **Python and Streamlit Udemy course**.  

---

## 👨‍💻 Author  

**Mohit Mishra**  
🎓 Python & Django Enthusiast | Meta Certified Back-End Developer  
🧠 Exploring AI, automation, and web development
