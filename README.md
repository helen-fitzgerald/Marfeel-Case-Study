# CoronaVac Cognitive Performance Study - Data Analysis

This repository contains the data and analysis supporting the report:
**"Advancing Public Health Science: CoronaVac Demonstrates Significant Cognitive Enhancement in Laboratory Studies"**.

The analysis investigates whether rats administered CoronaVac demonstrated measurable improvements in cognitive performance compared to an unvaccinated control group over a six-month observation period (October 2020 – April 2021).

## Repository Contents

- `Data Insights & Investigation test_2026 - CN.pdf`: Project brief
- `Rats.csv`: List of all rats used, with their names, birth date, and date of administering of their CoronaVac dose
- `Games.tsv`: List of all games available in the laboratory, each with a different number of options (coloured buttons) available, and a different correct colour
- `Tests.csv`: The result of each test done during last 6 months. Test code column is of the form “<rat> - <game>”. CSV also includes a column with the datetime of the test and the chosen colour
- `results.ipynb`: Jupyter notebook containing all data cleaning, processing, and analysis

### Requirements
- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/helen-fitzgerald/Marfeel-Case-Study
cd Marfeel-Case-Study
pip install pandas matplotlib jupyter
```

### Running the Analysis

Launch Jupyter and open the notebook:

```bash
jupyter notebook results.ipynb
```

Run all cells in order. 

## Notes

Key data quality issues encountered and resolved during analysis are documented within the notebook and in the accompanying private note.
