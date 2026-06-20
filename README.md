<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyQt5-41CD52?style=for-the-badge&logo=qt&logoColor=white" />
  <img src="https://img.shields.io/badge/Machine_Learning-FF6F00?style=for-the-badge&logo=scikit-learn&logoColor=white" />
</div>

# 🛒 JADE: An Innovative Product Hunting Tool for eCommerce Sellers

JADE is a powerful, desktop-based graphical application designed specifically for eCommerce sellers. Built primarily in Python utilizing PyQt5 for its graphical interface, JADE integrates Machine Learning heuristics to predict product viability, analyze market trends, and streamline the highly tedious process of product hunting on massive platforms like Amazon and eBay.

---

## 🌟 Key Features
- **Intuitive Desktop GUI:** A fully custom user interface built with `PyQt5`, providing sellers with a fast, native desktop experience.
- **Data-Driven Insights:** Automates the collection of crucial eCommerce metrics (prices, reviews, BSR) to assess product profitability.
- **Predictive ML Modeling:** Utilizes machine learning algorithms to provide a "viability score" for potential product launches.
- **Automated Scraping Links:** Generates and processes large datasets directly into actionable views.

---

## 📂 Project Structure
- **`Jade.py`**: The core application file. Contains the entire PyQt5 user interface logic, the data parsing mechanisms, and the underlying AI/ML prediction models.

---

## 🚀 Getting Started

### Prerequisites
To run this application locally, ensure you have Python 3.8+ installed along with the required desktop GUI libraries.

```bash
pip install PyQt5 pandas scikit-learn numpy
```

### Execution
Simply run the main Python file to launch the graphical user interface:

```bash
python Jade.py
```

*Note: Depending on your environment, you may need to install specific system dependencies for Qt5 (e.g., `libxcb` on Linux).*

---

## 🔒 Security & Data
This repository has been audited to ensure no sensitive API keys, database credentials, or personal configuration files are hardcoded. Any required API connections should be supplied via secure environment variables.
