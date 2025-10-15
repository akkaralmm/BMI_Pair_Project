# 🏥 BME Health Calculator Suite

This project is a comprehensive and practical health tracking application built entirely with Python and Gradio. It integrates three essential health management tools—a BMI calculator, a metabolic rate estimator, and a food log—into a single, clean, and interactive tabbed interface.# 🏥 BME Health Calculator Suite

This project is a comprehensive and practical health tracking application built entirely with Python and Gradio. It integrates three essential health management tools—a BMI calculator, a metabolic rate estimator, and a food log—into a single, clean, and interactive tabbed interface.

---

## 📝 Table of Contents
- [🚀 Getting Started](#-getting-started)
- [⬇️ Installation](#-installation)
- [▶️ Usage](#-usage-how-to-run-the-app)
- [✨ Features Overview](#-features-overview)
- [🛠️ Technical Overview](#-technical-overview)
- [🧑‍💻 Developers & License](#-developers--license)

---

## 🚀 Getting Started

Follow these steps to clone the repository and run the application locally.

### Prerequisites

You need Python 3.x installed on your system.

---

## ⬇️ Installation

**Clone the Repository:**
```bash
git clone [YOUR_GITHUB_REPO_LINK]
cd BMI_Pair_Project # Or your project's main folder name
```

**Install Dependencies:**  
Install all required Python packages:
```bash
pip install gradio pandas plotly
```

---

## ▶️ Usage (How to Run the App)

**Execute the Python File:**  
Run the main script from your terminal:
```bash
python [YOUR_MAIN_PYTHON_FILE_NAME.py]
```

**Access the Interface:**  
The application will automatically launch in your web browser. If not, open the URL provided in the terminal (typically http://127.0.0.1:7860).

---

## ✨ Features Overview

The application is split into three main tabs for a seamless user experience:

### 📊 BMI Calculator (Body Mass Index)
- Supports both Metric (cm, kg) and Imperial (in, lbs) units.
- Calculates BMI and provides a visual health category indicator (Underweight, Normal, Overweight, Obesity).
- Displays a Plotly chart of BMI history over time.

### 🔥 Metabolic Rate (BMR/TDEE)
- Calculates BMR (Basal Metabolic Rate) and TDEE (Total Daily Energy Expenditure) using user input (age, gender, height, weight, activity level).
- Provides suggested calorie targets for Weight Maintenance, Weight Loss, and Weight Gain.

### 🥗 Food & Calorie Tracker
- Allows logging of meals via a predefined dropdown of common foods or via manual input of food name and calories.
- Totals the day’s calorie intake and compares it directly to the TDEE target (if calculated).
- Shows a 7-day chart of calorie intake history for easy tracking.

---

## 🛠️ Technical Overview

| Component | Role |
|-----------|------|
| **Gradio** | Frontend and interactive framework (UI, Tabs, Event System). |
| **Pandas** | Data structure for state management (storing BMI history and food log). |
| **Plotly** | Generates the responsive and interactive data visualizations (charts). |

---

## 🧑‍💻 Developers & License

**Developers:**
- Akkara Lamaimas | Student ID: 6813400
- Nanticha Supmool | Student ID: 6813375

Course: EGBI  
Date: October 14, 2025

**License:**  
This project is for academic use.
