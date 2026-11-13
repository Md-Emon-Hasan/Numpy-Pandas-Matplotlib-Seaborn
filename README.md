# NumPy, Pandas, Matplotlib & Seaborn

A hands-on collection of Jupyter notebooks for learning Python data analysis and visualization. The repository brings together practice material for **NumPy**, **Pandas**, **Matplotlib**, and **Seaborn**, with CSV and Excel files used by the examples.

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge" alt="Apache 2.0 license"></a>
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3">
  <img src="https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter notebooks">
</p>

## About

This is a practical learning repository: work through notebooks, run the examples, and adapt them to your own datasets. It covers foundational array operations, tabular data preparation, and common chart types, progressing from library basics to complete visualization examples.

## Contents

| Folder | What you will find |
| --- | --- |
| [`Numpy/`](Numpy/) | Array creation and indexing, array operations, mathematics, linear algebra, statistics, reshaping, and file loading. |
| [`Pandas/`](Pandas/) | Series and DataFrames, reading and writing files, indexing, sorting, filtering, missing values, and basic data inspection. |
| [`Matplotlib/`](Matplotlib/) | Plot styling and customization, line and bar charts, histograms, pie charts, and examples using gas-price and FIFA data. |
| [`Seaborn/`](Seaborn/) | Distribution, categorical, matrix, regression, and grid plots, plus styling and palette examples. |

### Notebooks

- **NumPy:** [`Numpy from FreeCodeCamp.ipynb`](Numpy/Numpy%20from%20FreeCodeCamp.ipynb), [`Numpy from Harry.ipynb`](Numpy/Numpy%20from%20Harry.ipynb)
- **Pandas:** [`Pandas Code with Harry.ipynb`](Pandas/Pandas%20Code%20with%20Harry.ipynb)
- **Matplotlib:** [`Matplotlib by FreeCodeCamp.ipynb`](Matplotlib/Matplotlib%20by%20FreeCodeCamp.ipynb)
- **Seaborn:** [`SB Tut.ipynb`](Seaborn/SB%20Tut.ipynb), [`Seaborn full course.ipynb`](Seaborn/Seaborn%20full%20course.ipynb)

## Quick start

### Requirements

- Python 3
- Jupyter Notebook or JupyterLab
- NumPy, Pandas, Matplotlib, Seaborn, and `openpyxl` (for the Excel example)

### Set up

Clone the repository and move into its folder:

```bash
git clone https://github.com/Md-Emon-Hasan/Numpy-Pandas-Matplotlib-Seaborn.git
cd Numpy-Pandas-Matplotlib-Seaborn
```

Create and activate a virtual environment (recommended), then install the notebook dependencies:

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

macOS / Linux:

```bash
source .venv/bin/activate
```

Install the packages:

```bash
python -m pip install --upgrade pip
python -m pip install numpy pandas matplotlib seaborn jupyter openpyxl
```

Open a terminal in the folder containing the notebook you want to run (for example, `Matplotlib/` or `Seaborn/`) and launch `jupyter notebook` there. Several notebooks load datasets by relative filename, so starting Jupyter in the notebook folder lets those paths resolve correctly. Run the cells in order.

## Data files

Sample datasets are kept alongside the notebooks that use them. For example, Matplotlib examples read `gas_prices.csv` and `fifa_data.csv`, while Seaborn examples use CSV and Excel files in `Seaborn/`. Keep these files in their current folders when running the examples. The FIFA dataset is relatively large, so its first load may take a little longer.

## Learning path

1. Practice arrays and numerical operations with **NumPy**.
2. Load, inspect, clean, and transform tables with **Pandas**.
3. Build and customize charts with **Matplotlib**.
4. Explore statistical and categorical visualizations with **Seaborn**.

## Contributing

Suggestions, corrections, and additional examples are welcome. To contribute:

1. Fork the repository and create a feature branch.
2. Make a focused change and include any required sample data.
3. Open a pull request describing the change.

Please keep examples beginner-friendly and make sure notebook file paths work from the repository root.

## License

This project is distributed under the [Apache License 2.0](LICENSE).

## Connect with me

- 🌐 **Portfolio:** [emonlabs-ai.hitechparks.com](https://emonlabs-ai.hitechparks.com)
- 💻 **GitHub:** [Md-Emon-Hasan](https://github.com/Md-Emon-Hasan)
- 💼 **LinkedIn:** [Md Emon Hasan](https://www.linkedin.com/in/md-emon-hasan-695483237/)
- 🤗 **Hugging Face:** [emonHasan01](https://huggingface.co/emonHasan01)
- 📧 **Email:** [emon.mlengineer@gmail.com](mailto:emon.mlengineer@gmail.com)
- 📱 **WhatsApp:** [+880 1834-363533](https://wa.me/8801834363533)

---

<p align="center">Made by <a href="https://github.com/Md-Emon-Hasan">Md Emon Hasan</a></p>
