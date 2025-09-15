# Monte Carlo Retirement Simulator

## Project Overview
This project is a demonstration of how Monte Carlo simulation can be applied to retirement planning. Instead of assuming a fixed return annually, returns are treated randomly, drawn from a distribution. This allows us to generate thousands of possible futures, so we can estimate:
* The probability of reaching a retirement savings target
* The range of possible outcomes
* How changing assumptions impacts results

## Key Features
* Monte Carlo Simulation Engine: Modelling savings with contributions, growth and volatility
* Trajectory Predictor Plot: Demonstrating median projection and undertainty range
* Outcome Distribution: Producing a histogram of final balances
* Interactive Widgets: Adjust assumptions and see the changes in real-time

## How To Run
1. Clone the repo
```bash
git clone https://github.com/LeoGaunt/monte-carlo-simulator.git
cd monte-carlo-simulator
```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Open the notebook
```bash
jupyter notebook simulator.ipynb
```
4. Run all cells to create results

## Dependencies
* Python 3.8+
* NumPy
* Matplotlib
* ipywidgets
* Jupyter Notebook

## Why this project
I personally chose this project as I have an interest in how technology can be implemented in the financial sector and I wanted to create a tool that could be both useful for me, and explored maths in a way I hadn't explicitly looked at before (Monte Carlo Simulations)