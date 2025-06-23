# Car Evaluation 🚗

[![License](https://img.shields.io/github/license/Skorpion02/Car_evaluation?style=flat-square)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/Skorpion02/Car_evaluation?style=flat-square)](https://github.com/Skorpion02/Car_evaluation/commits/main)
[![Issues](https://img.shields.io/github/issues/Skorpion02/Car_evaluation?style=flat-square)](https://github.com/Skorpion02/Car_evaluation/issues)
[![Stars](https://img.shields.io/github/stars/Skorpion02/Car_evaluation?style=flat-square)](https://github.com/Skorpion02/Car_evaluation/stargazers)

---

Welcome to the **Car Evaluation** project! This repository contains a tool for evaluating car acceptability based on multiple features using machine learning.

## 🚀 Features

- Predicts car acceptability: unacceptable, acceptable, good, very good, from key attributes.
- Uses a machine learning model trained on the [Car Evaluation Dataset](https://archive.ics.uci.edu/dataset/19/car+evaluation).
- Easy-to-use and extendable code.

## 📂 Dataset

The project uses the Car Evaluation Dataset from UCI, which contains attributes such as:

- Buying Price
- Maintenance Cost
- Number of Doors
- Number of Persons
- Luggage Boot Size
- Safety

---

## 🗂️ Project Structure

```
Car_evaluation/
├── Conjunto de datos (Adquisición de vehiculos).xlsx, car_evaluation.xlsx
├── Car_evaluation.pbix
└── README.md
```

---

## 🛠️ Installation

```bash
git clone https://github.com/Skorpion02/Car_evaluation.git
cd Car_evaluation
# Install dependencies (update this if you use Python or another language)
pip install -r requirements.txt
```

## 🚦 Usage

```bash
python car_evaluation.py
```
_or update with your main script/entry point._

## 📊 Example

Input features:
- Buying: high
- Maintenance: med
- Doors: 4
- Persons: 4
- Luggage: small
- Safety: high

**Output:** `good`

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br>
Feel free to check the [issues page](https://github.com/Skorpion02/Car_evaluation/issues).

## 📄 License

This project is [MIT Licensed](LICENSE).

---

> Made with ❤️ by [Skorpion02](https://github.com/Skorpion02)
