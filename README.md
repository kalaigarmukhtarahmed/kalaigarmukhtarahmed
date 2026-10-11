<p align="center">
  <img src="assets/hero.svg" alt="Kalaigar Mukhtar Ahmed, Computer Science and Engineering student: full-stack web apps, machine learning models, computer vision tools and data stories" width="100%">
</p>

<p align="center">
  <a href="https://kalaigarmukhtarahmed.github.io"><img src="https://img.shields.io/badge/Open%20the%20interactive%20portfolio-5cc8ff?style=for-the-badge&logo=githubpages&logoColor=04101f" alt="Open the interactive portfolio"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Full--stack-0d1930?style=flat-square&logo=react&logoColor=5cc8ff" alt="Full-stack">
  <img src="https://img.shields.io/badge/AI%20%2F%20ML-0d1930?style=flat-square&logo=scikitlearn&logoColor=5cc8ff" alt="AI and ML">
  <img src="https://img.shields.io/badge/Computer%20Vision-0d1930?style=flat-square&logo=opencv&logoColor=5cc8ff" alt="Computer vision">
  <img src="https://img.shields.io/badge/Data%20Analysis-0d1930?style=flat-square&logo=pandas&logoColor=5cc8ff" alt="Data analysis">
</p>

## 👋 About me

I'm a **Computer Science and Engineering student** who likes turning a question into a working system: a React and Flask platform with role-based access, a model that answers a farming question, a camera that names colours, or a notebook that tests a hypothesis.

---

## 🚚 Flagship: [FleetSync](https://github.com/kalaigarmukhtarahmed/Fleetsync)

A logistics platform with three views over one shipment database: **dispatchers** assign and monitor, **drivers** see only their own deliveries, and **anyone** can track a parcel by number. *(Documented from the repository's README, roadmap and test page.)*

```mermaid
flowchart LR
    B["Browser<br/>React 19 + Vite"] -->|"REST /api/v1<br/>Bearer token"| F["Flask 3 API<br/>token_required + roles"]
    F -->|"SQLAlchemy"| D[("MySQL<br/>users · shipments · delivery_logs")]
```

```mermaid
stateDiagram-v2
    [*] --> unassigned
    unassigned --> assigned: dispatcher assigns
    assigned --> unassigned: dispatcher unassigns
    assigned --> out_for_delivery: driver starts transit
    out_for_delivery --> delivered: driver + note
    out_for_delivery --> failed: driver + note
```

Every status change writes a delivery-log entry, and the public tracker shows that same timeline.

---

## 🧩 Projects

| Project | What it does | Stack | Evidence |
|---|---|---|---|
| [**FleetSync**](https://github.com/kalaigarmukhtarahmed/Fleetsync) | Role-based logistics platform | React · Flask · MySQL | Documented |
| [**CodeEval-AI**](https://github.com/kalaigarmukhtarahmed/CodeEval-AI) | Scores the quality of an uploaded Python repository | FastAPI · React · Ruff · Bandit | Documented |
| [**AgroPredict-ML**](https://github.com/kalaigarmukhtarahmed/AgroPredict-ML) | Checks if a crop suits the land and recommends another | Flask · scikit-learn | ✅ Source-verified |
| [**Color-Detection-Project**](https://github.com/kalaigarmukhtarahmed/Color-Detection-Project) | Names colours in a live webcam feed | OpenCV · NumPy | ✅ Source-verified |
| [**Hospital-Employee-Attrition-Analysis**](https://github.com/kalaigarmukhtarahmed/Hospital-Employee-Attrition-Analysis) | Statistical study of attrition in synthetic data | Pandas · SciPy · Seaborn | Documented |
| [**mnc-it-employee-attrition-data-analysis**](https://github.com/kalaigarmukhtarahmed/mnc-it-employee-attrition-data-analysis) | Data-preparation walkthrough | Pandas · scikit-learn | Documented |
| [**Swiggy-Sales-Analysis**](https://github.com/kalaigarmukhtarahmed/Swiggy-Sales-Analysis) | Cleaning and business questions on food-order sales | Pandas · Jupyter | Documented |
| [**Java-program**](https://github.com/kalaigarmukhtarahmed/Java-program) | Interface and inheritance practice | Java | ✅ Source-verified |

<sub>**Source-verified** means the code was read. **Documented** means the description comes from the repository's README or notes.</sub>

---

## 🛠️ Tech stack

![Python](https://img.shields.io/badge/Python-0d1930?style=for-the-badge&logo=python&logoColor=5cc8ff)
![Java](https://img.shields.io/badge/Java-0d1930?style=for-the-badge&logo=openjdk&logoColor=5cc8ff)
![JavaScript](https://img.shields.io/badge/JavaScript-0d1930?style=for-the-badge&logo=javascript&logoColor=5cc8ff)
![React](https://img.shields.io/badge/React-0d1930?style=for-the-badge&logo=react&logoColor=5cc8ff)
![Vite](https://img.shields.io/badge/Vite-0d1930?style=for-the-badge&logo=vite&logoColor=8f7bff)
![Flask](https://img.shields.io/badge/Flask-0d1930?style=for-the-badge&logo=flask&logoColor=8f7bff)
![FastAPI](https://img.shields.io/badge/FastAPI-0d1930?style=for-the-badge&logo=fastapi&logoColor=8f7bff)
![MySQL](https://img.shields.io/badge/MySQL-0d1930?style=for-the-badge&logo=mysql&logoColor=8f7bff)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0d1930?style=for-the-badge&logo=scikitlearn&logoColor=5cc8ff)
![OpenCV](https://img.shields.io/badge/OpenCV-0d1930?style=for-the-badge&logo=opencv&logoColor=5cc8ff)
![Pandas](https://img.shields.io/badge/Pandas-0d1930?style=for-the-badge&logo=pandas&logoColor=8f7bff)
![Jupyter](https://img.shields.io/badge/Jupyter-0d1930?style=for-the-badge&logo=jupyter&logoColor=8f7bff)

---

<p align="center">
  <a href="https://kalaigarmukhtarahmed.github.io"><b>🌐 Interactive portfolio</b></a> ·
  <a href="https://github.com/kalaigarmukhtarahmed?tab=repositories"><b>📂 All repositories</b></a>
</p>
