# CineMatch: Full-Stack Movie Recommendation System 🎬

CineMatch is a full-stack, machine learning-powered movie recommendation engine built using a decoupled architecture. The application processes a massive dataset of 45,000+ movies to deliver highly accurate, content-based recommendations in real time using vector similarity modeling.

🔗 **[Live Web Application](https://cinematch-fv58azmq8qpzys7mppmnwr.streamlit.app/)**

---

## 🚀 Key Features
* **Content-Based Filtering:** Recommends movies based on structural metadata, descriptions, and tag alignment using natural language processing (NLP).
* **Decoupled Architecture:** Built with a clean separation of concerns—a high-performance machine learning backend and an interactive web frontend.
* **Dynamic Poster Fetching:** Integrates with the official TMDb REST API to dynamically fetch and map asset graphics on the fly based on internal movie IDs.
* **Production Cloud Deployment:** Fully containerized and deployed across a distributed environment (FastAPI on Render, Streamlit UI on Streamlit Cloud).

---

## 🛠️ Tech Stack & Architecture

### **Architecture Overview**
```text
 [ User Browser ] 🡘 [ Streamlit Frontend ] 🡘 (REST API Calls) 🡘 [ FastAPI Engine ] 🡘 [ Vector/Pickle Data ]
