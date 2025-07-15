# Modeling and Simulation Projects

This repository contains three academic data modeling projects completed under Prof. Arnab Ray as part of the *Modeling and Simulation* course. The projects apply mathematical modeling and data science techniques to real-world economic, industrial, and financial datasets using Python.

---

## Projects Overview

### 1. Logistic Modeling of IBM’s Growth
- Modeled IBM’s annual revenue, employee count, and profit over 90+ years using logistic growth equations.
- Reproduced and improved plots from the reference paper to study growth dynamics.
- Tools Used: `NumPy`, `Pandas`, `Matplotlib`

### 2. GDP and Trade Modeling of Major Economies
- Analyzed GDP and trade data of the USA, China, Japan, India, UK, and Germany.
- Forecasted India’s GDP reaching $4T and $5T using parameter-based exponential models.
- Reproduced results from research papers and explored policy implications.
- Tools Used: `NumPy`, `Pandas`, `Matplotlib`

### 3. Stock Price Modeling using Bachelier-Wiener Process
- Modeled NIFTY stock index behavior using stochastic processes.
- Reproduced six figures from the paper, including price, fluctuations, log returns, and trade volume.
- Used statistical analysis and `scikit-learn` regression to fit models.
- Tools Used: `NumPy`, `Pandas`, `Matplotlib`, `Scikit-learn`

---

## Referenced Papers

- **IBM Growth Modeling**:
  - `Logistic modelling of economic dynamics by Arnab K. Ray` – provides theory and IBM data modeling.
- **GDP & Trade Modeling**:
  - `Logistic Forecasting of GDP Competitiveness by Arnab K. Ray`, `Global dynamics of GDP and Trade by  Abhin Kakkad and Arnab K. Ray`: Research papers discussing GDP-Trade modeling and forecasting.
- **Stock Price Modeling**:
  - `Regularities in stock markets by  Abhin Kakkad, Harsh Vasoya and Arnab K. Ray`: Paper explaining the stochastic process modeling of NIFTY data.

---

## File Structure

```plaintext
Modeling-Simulation-Projects/
│
├── IBM Growth Logistic Model/
│   ├── Data/
│   |   ├── growth_ibm.txt
│   |   └── profit_ibm.txt
|   ├── ibm_growth_modeling.ipynb
│   └── ibm_growth_modeling_report.pdf
│
├── GDP and Trade Modeling/
│   ├── Data/
│   |   ├── India_GDP_Trade.txt
│   |   ├── US_GDP.txt
│   |   ├── US_Trade.txt
│   |   ├── UK_GDP_Trade.txt
│   |   ├── Japan_GDP_Trade.txt
│   |   ├── China_GDP_Trade.txt
│   |   └── Germany_GDP_Trade.txt
│   ├── gdp_and_trade_modeling.ipynb
│   └── gdp_and_trade_modeling_report.pdf
│
├── Stock Price Modeling Bachelier/
│   ├── Data/
│   |   ├── fluctuations.txt
│   |   ├── gaussian.txt
│   |   ├── price.txt
│   |   ├── trade.txt
│   |   └── wiener.txt
│   ├── stock_price_simulation_bachelier_model.ipynb
│   └── stock_price_simulation_bachelier_model_report.pdf
|
├── requirements.txt
└── README.md
```
---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
---

## Reports
Each project includes a detailed PDF report with methodology, equations, plots, and key findings.

---
## How to Run the Code

Follow the steps below to set up and run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/kaushikatgithub/modeling-and-simulation-ds-projects.git
```
### 2. Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```
### 3. Install Dependencies

```bash
pip install -r requirements.txt
```
### 4. Run Notebooks 

```bash
jupyter notebook
```




