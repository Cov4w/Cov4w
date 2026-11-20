<div align="center">

# Seunggyun Choi (`Cov4w`)

### AI & Software Developer

<p>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=AI+%26+Software+Developer;Connecting+AI+Models+to+Real-World+Systems;Machine+Learning+%C2%B7+Backend+Systems+%C2%B7+Robotics+%26+Edge+Vision" alt="Typing SVG" />
</p>

**Building software systems that bridge machine learning models, backend architectures, and real-world devices.**

</div>

---

## About Me

I am an **AI & Software Developer** focused on turning machine learning and computer vision models into usable software systems. Rather than treating AI modeling and application engineering as separate tracks, I work across the pipeline—from data preprocessing and model training to REST APIs, desktop/web clients, and real-time robotics control.

- **Core Focus:** Applied Machine Learning, Computer Vision (YOLO), Backend API Engineering, and Client-Server Applications
- **Integration Mindset:** Serving Python ML pipelines to C#/.NET and React clients, embedding LLM workflows into business backends, and streaming edge vision over WebRTC
- **Engineering Approach:** Validating ideas through working prototypes, structured experiments, and incremental system refactoring

---

## Tech Stack

> Listed technologies reflect hands-on implementation verified across public repositories. Areas currently under active study are listed separately below.

| Category | Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=3776AB) ![C# / .NET](https://img.shields.io/badge/C%23_%2F_.NET-161B22?style=flat-square&logo=dotnet&logoColor=9B72FF) ![TypeScript](https://img.shields.io/badge/TypeScript-161B22?style=flat-square&logo=typescript&logoColor=3178C6) ![C++](https://img.shields.io/badge/C%2B%2B-161B22?style=flat-square&logo=cplusplus&logoColor=4A9EFF) |
| **AI / Machine Learning** | ![PyTorch](https://img.shields.io/badge/PyTorch-161B22?style=flat-square&logo=pytorch&logoColor=EE4C2C) ![TensorFlow](https://img.shields.io/badge/TensorFlow-161B22?style=flat-square&logo=tensorflow&logoColor=FF6F00) ![Keras](https://img.shields.io/badge/Keras-161B22?style=flat-square&logo=keras&logoColor=D00000) ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-161B22?style=flat-square&logo=scikitlearn&logoColor=F7931E) ![XGBoost](https://img.shields.io/badge/ML-XGBoost-161B22?style=flat-square&labelColor=0D1117&color=1F6FEB) ![YOLO](https://img.shields.io/badge/YOLO_(Ultralytics)-161B22?style=flat-square&logo=yolo&logoColor=00FFFF) ![OpenCV](https://img.shields.io/badge/OpenCV-161B22?style=flat-square&logo=opencv&logoColor=818CF8) ![Pandas](https://img.shields.io/badge/Pandas-161B22?style=flat-square&logo=pandas&logoColor=E2E8F0) ![NumPy](https://img.shields.io/badge/NumPy-161B22?style=flat-square&logo=numpy&logoColor=4DABCF) |
| **Backend & Clients** | ![FastAPI](https://img.shields.io/badge/FastAPI-161B22?style=flat-square&logo=fastapi&logoColor=009688) ![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-161B22?style=flat-square&logo=dotnet&logoColor=9B72FF) ![WPF](https://img.shields.io/badge/Desktop-WPF_(.NET_8%2F9)-161B22?style=flat-square&labelColor=0D1117&color=512BD4) ![Flask](https://img.shields.io/badge/Flask-161B22?style=flat-square&logo=flask&logoColor=FFFFFF) ![Django REST](https://img.shields.io/badge/Django_REST-161B22?style=flat-square&logo=django&logoColor=44B78B) ![React](https://img.shields.io/badge/React-161B22?style=flat-square&logo=react&logoColor=61DAFB) ![Swagger](https://img.shields.io/badge/Swagger-161B22?style=flat-square&logo=swagger&logoColor=85EA2D) |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-161B22?style=flat-square&logo=mysql&logoColor=60A5FA) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-161B22?style=flat-square&logo=postgresql&logoColor=60A5FA) ![SQLite](https://img.shields.io/badge/SQLite-161B22?style=flat-square&logo=sqlite&logoColor=38BDF8) |
| **DevOps & Tools** | ![Git](https://img.shields.io/badge/Git-161B22?style=flat-square&logo=git&logoColor=F05032) ![GitHub](https://img.shields.io/badge/GitHub-161B22?style=flat-square&logo=github&logoColor=FFFFFF) ![Docker](https://img.shields.io/badge/Docker-161B22?style=flat-square&logo=docker&logoColor=2496ED) ![Nginx](https://img.shields.io/badge/Nginx-161B22?style=flat-square&logo=nginx&logoColor=009639) ![Linux](https://img.shields.io/badge/Linux-161B22?style=flat-square&logo=linux&logoColor=FCC624) |
| **Robotics & Edge Vision** | ![Unitree Go2](https://img.shields.io/badge/Robotics-Unitree_Go2-161B22?style=flat-square&labelColor=0D1117&color=1F6FEB) ![WebRTC](https://img.shields.io/badge/WebRTC-161B22?style=flat-square&logo=webrtc&logoColor=E2E8F0) ![Socket.IO](https://img.shields.io/badge/Socket.IO-161B22?style=flat-square&logo=socketdotio&logoColor=FFFFFF) ![NVIDIA CUDA](https://img.shields.io/badge/NVIDIA_CUDA-161B22?style=flat-square&logo=nvidia&logoColor=76B900) |

---

## Featured Projects

### 1. ChurnGuard — Customer Churn Prediction & Model Evaluation System `[Prototype]`
**Repositories:** [bitTask-ChurnGuard (ML API Server)](https://github.com/Cov4w/bitTask-ChurnGuard) · [bitTask-Churnguard-Client (WPF Client)](https://github.com/Cov4w/bitTask-Churnguard-Client)

- **Objective:** Build an end-to-end client-server ML workflow that predicts customer churn, compares classifiers under imbalanced data conditions, and supports retention-focused model selection.
- **Key Features:**
  - Automated preprocessing pipeline via `ColumnTransformer` (median/mode imputation, `StandardScaler`, `OneHotEncoder`, stratified split)
  - Side-by-side training and evaluation of 5 classifiers (Logistic Regression, SGD Classifier, Decision Tree, Random Forest, Gradient Boosting)
  - Interactive hyperparameter tuning (`POST /api/model-improvement`) and 5-Fold `GridSearchCV` report generation (`GET /api/model-report`) consumed by a C# WPF MVVM desktop client
- **Tech Stack:** `Python` `FastAPI` `Scikit-learn` `Pandas` `C#` `.NET 9` `WPF (MVVM)`
- **Engineering Focus:** Designed for imbalanced churn classification by selecting the winning estimator via F1-score and ROC-AUC (handling both `predict_proba` and `decision_function`), while decoupling ML training from desktop UI state over typed REST contracts.

---

### 2. THE BOOK ARCHIVE — AI-Assisted Book Shopping Application `[Team Project]`
**Repository:** [bit-midtermProject](https://github.com/Cov4w/bit-midtermProject)

- **Objective:** Develop a desktop e-commerce platform with clear client-server separation, administrative catalog controls, and LLM-powered reader assistance.
- **Key Features:**
  - **Customer workflows:** Account authentication, multi-filter book search (keyword, category, price), shopping cart, checkout, and order history
  - **Admin workflows:** Member and payment detail auditing, sale-status management, and external catalog sync via Kakao Book Search API
  - **AI integration:** OpenAI-compatible Chat API endpoints for structured book summarization, purchase-history reading tendency diagnostics, and conversational recommendations
- **Tech Stack:** `C#` `.NET 8` `WPF` `ASP.NET Core Web API` `MySQL` `Entity Framework Core (Pomelo)` `Swagger` `OpenAI SDK`
- **Engineering Focus:** Implemented clean REST boundaries between `BookShopping.Client` and `BookShopping.Server`, joined relational purchase history with EF Core to build grounded LLM prompts, and enforced explicit HTTP status-code error handling in `ApiService`.

---

### 3. Unitree Go2 Patrol & WebRTC Control System `[Team Prototype · v0.1.0]`
**Repositories:** [nCAGE (Packaged System)](https://github.com/Cov4w/nCAGE) · [cage-unitree-project (Team Workspace)](https://github.com/Cov4w/cage-unitree-project)

- **Objective:** Build a web-accessible remote monitoring and real-time vision pipeline for a **Unitree Go2** quadruped robot as part of a team patrol prototype (alongside teammates researching ROS2 SLAM/Navigation).
- **Key Features:**
  - Real-time camera streaming and low-latency robot motion/joystick control over **WebRTC (`aiortc`)** using `go2_webrtc_connect`
  - **Flask + Flask-SocketIO** control server bridging asynchronous WebRTC tracks and MJPEG video output via `multiprocessing.Queue`
  - Real-time **Ultralytics YOLO (`yolo11n` / custom `best.pt`)** inference for person detection and sustained high-confidence fire detection with alert throttling, plus LiDAR stream view switching in `nCAGE`
- **Tech Stack:** `Python` `Flask` `Flask-SocketIO` `WebRTC (aiortc)` `OpenCV` `Ultralytics YOLO` `Unitree Go2`
- **Engineering Focus:** Solved async-to-sync streaming bottlenecks between `asyncio` WebRTC frames and Flask HTTP/Socket.IO loops, reduced false fire alerts with continuous-duration threshold tracking, and refactored the initial prototype into an installable Python package (`pyproject.toml`).

---

### 4. Self-Evolving Crypto Auto-Trading System `[Personal System]`
**Repository:** [upbit-auto-trading-bot](https://github.com/Cov4w/upbit-auto-trading-bot)

- **Objective:** Design a full-stack algorithmic trading and backtesting platform combining ML signal generation, real-time monitoring, and automated risk controls.
- **Key Features:**
  - Multi-layer entry pipeline combining market/volume/trend filters with a 3-class **XGBoost / Scikit-learn** model and time-weighted retraining over recent trade history
  - Risk management engine with Maximum Drawdown (MDD) monitoring, trailing stops, flash-crash exits, and multi-coin historical backtesting
  - **FastAPI + WebSocket** backend with JWT authentication, **React + TypeScript** live dashboard, and containerized deployment via **Docker Compose** and **Nginx**
- **Tech Stack:** `Python` `FastAPI` `XGBoost` `Scikit-learn` `WebSockets` `React` `TypeScript` `SQLite` `Docker` `Nginx`
- **Engineering Focus:** Separated trading execution, capital management, and backtesting modules while exposing real-time position and model performance metrics through WebSockets and Dockerized services.

---

### 5. Machine Learning & Deep Learning Archive `[Study & Implementation Archive]`
**Repository:** [bit-MachineLearning-study](https://github.com/Cov4w/bit-MachineLearning-study)

- **Objective:** Maintain a reproducible reference repository pairing theoretical notes with working code across classical ML and modern deep learning architectures.
- **Key Topics Implemented:**
  - **Classical & Unsupervised ML:** Logistic Regression, Decision Trees, Stratified K-Fold Cross-Validation, Grid Search, K-Means Clustering, and PCA
  - **Neural Networks:** ANN, DNN, CNN (with filter & feature-map visualization), and sequence models (RNN, LSTM, GRU)
  - **Dual-Framework Practice:** Implemented core neural architectures in both **TensorFlow/Keras** and **PyTorch** to compare training loops and abstractions
- **Tech Stack:** `Python` `PyTorch` `TensorFlow` `Keras` `Scikit-learn` `NumPy` `Matplotlib`
- **Engineering Focus:** Built side-by-side Keras and PyTorch implementations to strengthen low-level understanding of forward/backward passes, regularization, and feature extraction rather than relying on black-box APIs.

---

## Currently Learning & Exploring

- **Deep Learning & Computer Vision:** Extending CNN and sequence modeling fundamentals toward custom object detection and edge inference optimization
- **Applied AI & RAG Systems:** Productionizing LLM and retrieval-augmented workflows (e.g., AWS Bedrock Knowledge Bases, FastAPI inference services)
- **Backend & Network Architecture:** Strengthening system-level fundamentals across ASP.NET Core, FastAPI, WebSockets, and C++ TCP socket programming (`bit-SocketStd-cpp`)
- **Edge AI & Robotics Integration:** Deepening practical experience in robotics middleware (ROS2 / SLAM concepts) and hardware-software interfacing

---

## GitHub Activity

<div align="center">

<p>
  <img height="175" src="https://github-readme-stats.vercel.app/api?username=Cov4w&show_icons=true&theme=github_dark&bg_color=0D1117&border_color=30363D&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" alt="Cov4w GitHub Stats" />
  <img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Cov4w&layout=compact&theme=github_dark&bg_color=0D1117&border_color=30363D&title_color=58A6FF&text_color=C9D1D9&langs_count=8" alt="Cov4w Top Languages" />
</p>

<p>
  <img src="https://streak-stats.demolab.com?user=Cov4w&theme=github-dark-blue&background=0D1117&border=30363D&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="Cov4w GitHub Streak" />
</p>

<p>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Cov4w&bg_color=0D1117&color=C9D1D9&line=58A6FF&point=FFFFFF&area=true&area_color=1F6FEB&border_color=30363D" alt="Cov4w Contribution Graph" />
</p>

</div>

---

## Contact

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Cov4w-161B22?style=for-the-badge&logo=github&logoColor=FFFFFF)](https://github.com/Cov4w)
[![Email](https://img.shields.io/badge/Email-xormr4596%40gmail.com-161B22?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:xormr4596@gmail.com)

</div>
