# 🛡️ SafeFood BD: Pesticide Residue Risk Assessment Pipeline

SafeFood BD is a predictive data science microservice designed to evaluate, predict, and monitor pesticide residue safety limits—specifically tracking **Pre-Harvest Intervals (PHI)**—in fruits and vegetables across Bangladesh [fao.org]. 

Instead of relying on slow, high-cost physical laboratory testing at the point of sale, this system leverages historical agricultural safety thresholds published by the **Bangladesh Agricultural Research Institute (BARI)** [fao.org]. It transforms abstract biochemical safety timelines into an automated, low-latency software decision pipeline to protect public health and empower consumer awareness.

---

## 👥 The Contributor Team & Modular Work Distribution

Our 3-member capstone group operates via an isolated, modular codebase utilizing **Git/GitHub Branching Workflows**:

*   **📊 1. Data Science & Engineering Track (Person A):** Compiling the PHI safety matrix dataset according to BARI standard documentation, training the supervisor tree-classifier algorithm, and exporting the static model binary footprint (`pesticide_model.pkl`) [fao.org].
*   **⚙️ 2. High-Performance Backend Track (Person B):** Constructing the core application network endpoints using **FastAPI**, mapping incoming validation shapes using Pydantic, executing the model loading loop, and handling asynchronous query flows.
*   **🎨 3. Client Frontend Application Track (Person C):** Styling the public consumer dashboard using **HTML5, CSS3, and Modern JavaScript (ES6)**, writing asynchronous non-blocking networking scripts (`fetch` API), and updating dynamic safety alerts on screen.

---

## ⚙️ Tech Stack & Architecture

*   **Data Core:** Python 3.11+, `pandas`, `scikit-learn` (Random Forest Classifier).
*   **Backend:** FastAPI, Uvicorn, Pydantic Data Validation.
*   **Frontend:** Native HTML5, CSS3, Vanilla JavaScript (Web Fetch API).
*   **Infrastructure:** Git/GitHub Collaboration, Docker Containerization.
