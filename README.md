# DAI Assignment 3

<p align="center">
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge" />
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge" />
  <img alt="Pandas" src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge" />
  <img alt="Data Science" src="https://img.shields.io/badge/Data%20Science-1F77B4?style=for-the-badge" />
</p>

<p align="center">
  <strong>A structured data-analysis notebook focused on reproducible exploration, modeling, and interpretation.</strong>
</p>

DAI Assignment 3 is documented as a compact analytical project with a notebook-first workflow. The README frames the project professionally so reviewers can understand the objective, execution flow, and expected environment before opening the notebook.

## Core Capabilities

- Captures the full analytical workflow in a Jupyter notebook.
- Supports exploratory data analysis and model-oriented experimentation.
- Provides a clean setup path for reproducible execution.
- Documents the repository for review and portfolio presentation.

## Technical Architecture

The repository uses a single-notebook structure. This is appropriate for assignment-style analysis where the notebook contains the full sequence of loading, exploration, transformation, modeling, and conclusions.

## Architecture Diagram

```mermaid
%%{init: {"flowchart": {"nodeSpacing": 55, "rankSpacing": 70, "curve": "basis"}, "themeVariables": {"fontSize": "16px", "fontFamily": "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"}}}%%
flowchart TD
  Dataset["Assignment Dataset"] --> Notebook["Analysis Notebook"]
  Notebook --> Clean["Data Cleaning"]
  Clean --> Explore["Exploratory Analysis"]
  Explore --> Model["Modeling or<br/>Analytical Method"]
  Model --> Findings["Documented Findings"]

  classDef inputs fill:#FEE2E2,stroke:#DC2626,color:#7F1D1D,stroke-width:2.5px;
  classDef process fill:#ECFCCB,stroke:#65A30D,color:#365314,stroke-width:2.5px;
  classDef data fill:#DBEAFE,stroke:#2563EB,color:#1E3A8A,stroke-width:2.5px;
  classDef agent fill:#FAE8FF,stroke:#C026D3,color:#701A75,stroke-width:2.5px;
  classDef output fill:#DCFCE7,stroke:#16A34A,color:#14532D,stroke-width:2.5px;
  class Dataset inputs;
  class Notebook,Clean,Explore,Findings process;
  class Model agent;
  linkStyle default stroke:#52525B,stroke-width:2.5px;
```

## Technology Stack

- Jupyter notebook execution.
- Python data-analysis workflow.
- Pandas, NumPy, and visualization-ready environment.
- Extensible structure for adding source data and reports.

## Repository Structure

- `dai-assignment3.ipynb` - Primary analysis notebook.

## Getting Started

```bash
python -m venv .venv
source .venv/bin/activate
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

```bash
jupyter notebook dai-assignment3.ipynb
```

## Professional Context

This project demonstrates disciplined notebook organization, data-analysis fundamentals, and reproducible academic project presentation.
