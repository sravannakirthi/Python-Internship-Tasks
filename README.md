# Python-Internship-Tasks
# 💻 Python Development Internship Portfolio

Welcome to my portfolio showcasing the software engineering solutions I built and deployed during my Python Development Internship at Alfido Tech. This repository serves as my official public submission link containing code implementations and structural documentation.

---

## 🛠️ Implemented Project Architecture

### 📁 1. Automated File Management Engine (`Task1_File_Automation`)
* **Objective:** Developed a system-level background utility to resolve disk clutter by automatically parsing unorganized source file trees.
* **Core Mechanisms:** Leverages native `os` and `shutil` libraries. Employs dynamic path mapping rules (`os.path.abspath(__file__)`) to scan directories, extract variable extensions, and dynamically migrate loose items into sorted target folders (`Images`, `Documents`, `Videos`).

### 🌤️ 2. Live REST API Weather Client (`Task2_API_JSON`)
* **Objective:** Built a network I/O command-line application that pulls real-time environmental metrics.
* **Core Mechanisms:** Utilizes the `requests` library to handle HTTP client-server handshakes with external endpoints (`wttr.in`). Implements strict defensive programming practices by verifying connection integrity (`response.status_code == 200`) before parsing and deserializing nested JSON payloads.

### 🎓 3. Student Management Web Dashboard (`Task4_Flask_Project`)
* **Objective:** Created a lightweight, monolithic CRUD application monitoring student registration parameters.
* **Core Mechanisms:** Engineered using the Flask micro-framework. Maps standard backend HTTP routing logic onto incoming synchronous browser form payloads. Uses `GET` and `POST` server lifecycles to mutate state parameters and output data seamlessly via Jinja HTML templates.
