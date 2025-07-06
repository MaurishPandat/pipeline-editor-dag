# 🧠 Pipeline Editor DAG 🚀

An **interactive, dynamic, and intuitive DAG-based pipeline editor** built using **React**, **ReactFlow**, and **FastAPI**. This project allows users to create, connect, and manage custom logic pipelines using smart nodes — perfect for visual workflows, automation systems, or ML/ETL pipelines.

---

🎯 Drag and drop nodes  
📐 Auto-sized text inputs  
🔌 Smart connection handles  
🌈 Styled with Tailwind CSS  
⚡ Integrated with a FastAPI backend

---

## 🛠️ Tech Stack

| Layer       | Tech Used |
|-------------|-----------|
| 🧩 Frontend | React, ReactFlow, Tailwind CSS, Zustand, Sass |
| 🔙 Backend  | Python, FastAPI |
| 🎨 Styling  | Tailwind CSS, Framer Motion (optional), React Icons |
| 🧪 State    | Zustand (lightweight state management) |

---

## ✨ Features

- ⚙️ **Node Abstraction**: Custom-built ReactFlow nodes for text inputs and variable recognition.
- 📏 **Smart Text Nodes**: Auto-resizing with dynamic input logic and conditionally rendered handles.
- 🎨 **Fully Styled UI**: Clean sidebar, drag-and-drop editor, smooth transitions with Tailwind.
- 🔁 **Live Data Flow**: Zustand-based state sync for instant UI updates.
- 🧠 **FastAPI Integration**: Backend to handle node data, structure, or future persistence logic.

---

## 📂 Folder Structure

pipeline-editor-dag/
├── frontend/ # React + ReactFlow editor
├── backend/ # FastAPI backend
├── README.md
└── .gitignore

yaml
Copy
Edit

---

## 🚀 Getting Started

### 🔧 Frontend Setup 

```bash
cd frontend
npm install
npm run dev

Backend Setup
bash
Copy
Edit
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
🌍 Use Case Ideas
🧬 Visual data pipeline builders (ETL / ML workflows)

🤖 Automation workflow creators

🧰 Custom logic chain creators for no-code platforms

📦 Dependency graph visualizations

🧠 Learnings & Goals
This project was created as a technical assignment for VectorShift, and demonstrates:

⚛️ React + ReactFlow mastery

🧮 Logical node processing & design thinking

🖼️ UI/UX consistency with real-time state

📡 Frontend ↔ Backend communication with FastAPI

🤝 Let's Connect
👨‍💻 Built with passion by Maurish Kaushik
📫 Reach out: LinkedIn | Email

🏁 Future Improvements
💾 Persistent node saving via backend

🔐 Auth-based pipeline access

📊 Live preview of node output

🧠 LLM-based node generation (AI-enhanced flow builder 🤯)
