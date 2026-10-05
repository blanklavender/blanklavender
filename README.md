# 👋 Hi, I'm Mahima Rudrapati

I'm a **Software Engineer and Computer Vision researcher** who likes the place where algorithms meet messy, real-world data: **3D perception, machine learning, and the systems** that keep them fast and dependable.

Currently finishing my **M.S. in Computer Science** at **UC Davis** (Dec 2026), I work at the **[HRVIP Lab](https://hrvip.ucdavis.edu/)** in the Center for Spaceflight Research as a **Graduate Student Researcher**, building the perception pipeline for **[REPAS](https://repashrvip.wordpress.com/)**, a robot that farms plants on its own inside a space habitat.

---

## 💡 What I Do
- 👁️ **Computer Vision & 3D Perception:** RGB-D pipelines for localization, pose estimation, depth-based measurement and 3D reconstruction with **OpenCV**, **Open3D** and **C++**.
- 🧠 **Machine Learning:** Training, fine-tuning and evaluating models with **PyTorch**, from LSTMs to **LoRA/QLoRA** fine-tuning of 7B LLMs.
- 🌍 **Full-Stack Engineering:** Web apps and dashboards with **React**, **Node.js**, **Flask**, **FastAPI** and **PostgreSQL**.
- 📊 **Data & Visualization:** Scraping pipelines, recommendation systems and interactive **D3.js** dashboards over large datasets.

---

## 🏆 Research & Recognition
- 📄 **First-author paper — [Restaurant Recommendation System Based on ML Algorithms and Real-Time Web Scraping](https://ieeexplore.ieee.org/document/10919373)** (DABCon 2024, IEEE Xplore)
- 🥇 **Winner, HackDavis 2026** — among 428 participants
- 🎤 **Top 5 finalist**, Thesis Lightning Talk Competition, UC Davis CS (2026)
- 🌱 **Leaders for the Future Fellow**, UC Davis (2025)
- 📈 **Top 5 project**, ECS 272 Information Visualization, UC Davis (Fall 2024)

---

## 🛠️ Tech Stack

**Languages:**
![Python](https://img.shields.io/badge/Python-3670A0?logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?logo=html5&logoColor=white)

**ML & Computer Vision:**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![Open3D](https://img.shields.io/badge/Open3D-1A1A1A)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)

**Frameworks & Libraries:**
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?logo=d3dotjs&logoColor=white)

**Databases & Cloud:**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

**Core Areas:**
Computer Vision · 3D Reconstruction · Pose Estimation · Camera Calibration · Machine Learning · LLM Fine-Tuning & Evaluation · Recommendation Systems · Full-Stack Development · Data Visualization

---

## 🚀 Featured Projects

### 🔹 [CV Pipeline for Autonomous Space Farming](https://repashrvip.wordpress.com/)
*Robot vision for tracking plant growth in a space habitat, HRVIP Lab, UC Davis*
- Estimated plant canopy height from depth and geometry alone, reaching **under 2 cm** error, with **Meta SAM** segmentation so each plant is followed as it grows.
- Reconstructed hydroponic trays in 3D from multiple RGB-D views with **over 95%** alignment between captures, and built visual localization with **AprilTags** and **NVIDIA FoundationPose**, with cameras calibrated to **under 0.2 px** reprojection error.

### 🔹 [Restaurant Recommendation System](https://ieeexplore.ieee.org/document/10919373)
*ML-driven recommendations from live-scraped reviews, first-author IEEE paper*
- Led a team of four for about a year; built scraping pipelines with **Selenium** and later **Botasaurus**, running **75% faster** and fast enough to scrape while the user waits, over **10K+** restaurant and review records.
- Combined collaborative and content-based filtering with an **NLP** opinion-mining pipeline that weights reviewers by reliability, served through a **Flask + PostgreSQL** API and a **React** UI.

### 🔹 [PitchSlapped](https://github.com/blanklavender/pitch-slapped)
*A virtual Shark Tank: pitch out loud to three AI judges and get a scored report card*
- Real-time voice over an **ElevenLabs Conversational AI** WebSocket, with one agent role-playing all three judges through speaker tags parsed on the frontend.
- **Claude API** keeps a running pitch summary and generates the structured report card; **React + Vite** frontend and a **Node/Express** server that mints tokens and proxies evaluation requests.

### 🔹 [Industry Emissions Dashboard](https://github.com/blanklavender/IndustryEmissionsDash)
*Interactive D3.js story over 500K+ industrial CO₂ emission records*
- Built drill-down analytics (hierarchical bubbles, stacked bars, pie charts) so a reader can move from the big picture to a single sector.
- Placed in the **top 5 projects** of ECS 272 Information Visualization at UC Davis.

---

## 📚 Experience Snapshot
- 🔬 **Graduate Student Researcher, UC Davis — HRVIP Lab (2025–Present)** – Building the RGB-D perception pipeline for REPAS: localization, canopy measurement and 3D reconstruction.
- 🤖 **Intern, Pilotcrew AI (Summer 2025)** – Built LLM evaluation infrastructure on AWS.
- 👩‍🏫 **Teaching Assistant, UC Davis (4 quarters)** – Helped 100+ students through C++, data structures and object-oriented programming.
- 💼 **Web Development Intern, Skrapnest (2023)** – Built the full-stack MVP of a scrap-collection marketplace connecting 20+ dealers; the startup went on to raise $5K in seed funding.

---

## 📍 Right Now
- 🔨 Building 3D perception for autonomous plant care in a space habitat at the HRVIP Lab
- 📖 Finishing my MS thesis at UC Davis (December 2026)
- 🎯 Open to full-time Software Engineer, ML Engineer and Perception Engineer roles starting December 2026

---

## 🌐 Connect With Me
[![Portfolio](https://img.shields.io/badge/Portfolio-mahimarudrapati.dev-2a2a2a?logo=googlechrome&logoColor=white)](https://mahimarudrapati.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://linkedin.com/in/mahima-rudrapati)
[![GitHub](https://img.shields.io/badge/GitHub-100000?logo=github&logoColor=white)](https://github.com/blanklavender)
[![Email](https://img.shields.io/badge/Email-rmahimaa927%40gmail.com-red?logo=gmail&logoColor=white)](mailto:rmahimaa927@gmail.com)

---
