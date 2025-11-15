This project is a **Machine Learning–based URL Classification Plugin** that helps users identify whether a given URL is *benign* or *malicious*. In addition to detecting malicious links, the system also **classifies the threat type** into one of four categories:

* **Phishing**
* **Defacement**
* **Malware**
* **Spam**

The plugin integrates an **Explainable AI (XAI) component** that shows users *why* a URL was classified a certain way by highlighting the most influential features.

---

## Features

### URL Classification

* Detects if a URL is **safe** or **dangerous**.
* Malicious URLs are categorized into: *phishing, defacement, malware, or spam.*

### Machine Learning Models

* **Random Forest (RF)** – Best performing model in this project
* **LSTM Model** – Implemented for comparison

### Explainable AI (XAI)

* Displays feature importance to help users understand *how the model made a decision*
* Enhances trust, clarity, and transparency

### Browser Plugin Interface

* Clean UI to enter or capture URLs
* The backend automatically extracts URL features and performs real-time classification
* Provides warnings and risk explanations to the user

---

## System Architecture

1. **Browser Plugin**

   * Frontend interface for inputting URLs
   * Displays results + explanations

2. **Backend (Python/Flask/Django)**

   * URL feature extraction
   * Model inference (Random Forest / LSTM)
   * XAI explanation generator

3. **ML Pipeline**

   * Dataset preprocessing
   * Feature engineering
   * Model training and evaluation
   * Explainability module (e.g., SHAP)

---

## Tech Stack

* **ML Models:** Random Forest, LSTM
* **Backend:** Python (Flask)
* **Frontend:** Browser extension (Chrome)
* **XAI:** SHAP
* **Deployment:** Packaged as a browser plugin

---

## Future Improvements

* Add support for real-time scanning of every URL visited
* Integrate deep learning-based feature extraction
* Improve LSTM performance with a larger dataset
* Add a cloud-based scanning API
* Expand to mobile browsers

---



