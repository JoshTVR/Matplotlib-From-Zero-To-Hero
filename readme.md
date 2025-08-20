# Matplotlib — From Zero to Hero

![Matplotlib Logo](https://matplotlib.org/stable/_static/logo2.svg)

> **Learn Matplotlib step by step** — A complete hands-on guide to mastering data visualization in Python.

---

## Overview

This repository is meant to be an **introductory and practical guide** to the Python library **Matplotlib**.
Here, you'll find **notebooks, scripts, datasets, images, and cheatsheets** that will help you learn how to create stunning **data visualizations** from scratch.

Whether you're a **beginner** or an **intermediate Python developer**, this repository will help you go **from zero to hero** in Matplotlib.

---

## 📂 Project Structure

```Matplotlib-From-Zero-To-Hero/
├── 📁 datasets/                # CSV files and datasets for exercises
│   └── pokemon.csv
├── 📁 imgs/                    # Images used in examples and notebooks
│   ├── axis_plot_parameter.png
│   ├── caterpie.png
│   └── charizard.png
├── 📁 scripts/                 # All Jupyter notebooks and Python scripts
│   ├── 📁 en/                  # English notebooks
│   │   ├── 01-line-plots.ipynb
│   │   ├── 02-bar-plots.ipynb
│   │   ├── 03-pie-chart.ipynb
│   │   ├── 04-subplots.ipynb
│   │   ├── 01-00-exercise-line-plot.ipynb
│   │   └── plot.py
│   ├── 📁 es/                  # Spanish notebooks
│   │   ├── 01-graficos-linea.ipynb
│   │   ├── 02-graficos-barras.ipynb
│   │   ├── 03-grafico-circular.ipynb
│   │   ├── 04-subplots.ipynb
│   │   ├── 01-00-ejercicio-grafico-linea.ipynb
│   │   └── plot.py
├── 📁 docs/                    # Documentation and cheatsheets
│   ├── cheatsheets-matplotlib.pdf
│   ├── 📁 en/
│   │   └── README.md
│   └── 📁 es/
│       └── README.md
├── .gitignore
└── README.md                  # Main README linking to translations
```

---

## Contents

### **Scripts & Notebooks**

- **01-Line-Plots.ipynb** → Learn how to create **basic line plots** and customize them.
- **02-Bar-Plots.ipynb** → Create **bar charts** with custom colors and labels.
- **03-Pie-Chart.ipynb** → Generate **pie charts** with percentage formatting.
- **04-Subplots.ipynb** → Master **subplots** and arrange multiple charts.
- **plot.py** → A Python script for quick visualizations.

---

## Getting Started

### **1️.- Clone the repository**

```bash
git clone https://github.com/JoshTVR/Matplotlib-From-Zero-To-Hero.git
cd Matplotlib-From-Zero-To-Hero
```

### **2️.- Create a virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate   # On Linux / Mac
venv\Scripts\activate      # On Windows
```

### **3️.- Install dependencies**

```bash
pip install -r requirements.txt
```

> If there’s no `requirements.txt` yet, you can install manually:

```bash
pip install matplotlib pandas numpy jupyter
```

### **4️.- Run the Jupyter notebooks**

```bash
jupyter notebook
```

---

## Resources

- [📄 Official Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [📘 Cheatsheet (included in `docs/`)](docs/cheatsheets-matplotlib.pdf)
- [🎨 Matplotlib Colormaps](https://matplotlib.org/stable/tutorials/colors/colormaps.html)

---

## Learning Goals

By the end of this repository, you will be able to:

- Create **line, bar, scatter, and pie charts**
- Customize **colors, labels, titles, and legends**
- Use **subplots** to organize multiple visualizations
- Export plots to **PNG, SVG, and PDF** formats
- Build professional-grade visualizations for **data analysis projects**

---

## Technologies Used

- **Python 3.10+**
- **Matplotlib** → Data visualization
- **NumPy & Pandas** → Data manipulation
- **Jupyter Notebook** → Interactive learning environment

---

## Contributing

Contributions are welcome!

1. Fork the project
2. Create a feature branch

   ```bash
   git checkout -b feature/new-feature
   ```

3. Commit your changes

   ```bash
   git commit -m "Add new visualization example"
   ```

4. Push to your fork

   ```bash
   git push origin feature/new-feature
   ```

5. Create a **Pull Request**

---

## License

This project is licensed under the **MIT License** — feel free to use, modify, and share.

---

## Support

If you find this repository useful, consider giving it a **⭐ star** to support my work!

---
