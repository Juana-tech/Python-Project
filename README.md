1 This repository presents a comprehensive analysis of global COVID-19 trends—tracking cases, deaths, and vaccination progress—implemented as a Python script optimized for Visual Studio Code (VS Code). Designed for data professionals who prefer script-based workflows over traditional notebooks, this project combines:

- **Reproducible analysis via modular Python code (with Jupyter-like cell execution)

- Interactive debugging capabilities unique to VS Code

- Publication-ready visualizations (static and interactive)

- Version-control-friendly structure (avoiding .ipynb merge conflicts)**

2 Built on the rigorously maintained Our World in Data dataset, this analysis reveals temporal patterns, cross-country disparities, and vaccine rollout efficacy through:
- Time-series decomposition of infection waves

- Comparative metrics (cases/deaths per capita, vaccination rates)

- Geospatial intelligence via choropleth mapping

3  Running the Analysis
Open the script in VS Code:

bash
code ./src/covid_analysis.py
Execute cells sequentially:

Click the ▶ Run Cell button above each # %% section

Or use Shift + Enter with cursor in the cell

4 Advantages of VS Code Implementation
Debugging: Step-through execution of data cleaning pipelines

Performance: Handles larger datasets than Jupyter (no browser overhead)

Collaboration: .py files simplify Git merges

Trade-offs
Learning curve: Requires familiarity with VS Code’s interactive window

Notebook features: No native Markdown integration between cells
