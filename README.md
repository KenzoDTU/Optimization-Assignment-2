# Optimization-Assignment-2

## Installation

Install the required dependencies: ipywidgets, plotly, numpy, copy, gurobipy

**Note**: Gurobi requires a valid license. Install via:
- Academic license: [gurobi.com/academia](https://www.gurobi.com/academia)
- `conda install -c gurobi gurobi` (if using conda)

## Running the Models

1. Open `Models-FRAN.ipynb` in **VS Code** (with Jupyter extension), **JupyterLab**, or **Jupyter Notebook**
2. Press **Run All** (Ctrl+F9 in VS Code / Run → Run All Cells in Jupyter)
3. Interactive dashboards for Models 1-3 will appear with sliders and plots

## Expected Output

- **Model 1**: Baseline cost ~26.1M DKK/year, investment x=1
- **Model 2**: Baseline invests in t=2, total cost ~116M DKK  
- **Model 3**: Stochastic baseline invests in t=1, expected cost ~115M DKK
- Interactive plots showing dispatch, flows, LMPs, and parameter scans
- **Experiments**: shown at the bottom of the jupyter notebook

## Files

- `Models-FRAN.ipynb` - Complete implementation (Models 1-3 + dashboards)
- This `README.md` - Reproduction instructions

**Ready in <2 minutes after dependencies!**

Please note that Model 4 in the code is Model 3 in the report, but as model 3 was deleted at some point, it is possible it is still refered to as model 4 in the markdowns or elsewhere.

AI assisted in creating this readme.

