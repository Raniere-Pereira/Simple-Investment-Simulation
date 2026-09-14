
# 📊 Simple Investment Simulation — REITs

An **Excel-based tool** for investment planning and simulation focused on **Real Estate Investment Trusts (REITs)**.

The project allows users to simulate portfolio growth based on monthly contributions, estimate potential dividend income, and compare different investment horizons.

## 🎯 Features

* Portfolio growth simulation
* Estimated monthly dividend income
* **2, 5, 10, 20, and 30-year** scenarios
* Monthly investment calculation
* Contribution allocation by REIT type
* Investment profiles:

  * Conservative
  * Moderate
  * Aggressive
* REIT classification by segment

## 📈 Methodology

The projection uses the **Future Value (FV)** concept, considering:

* Monthly contribution
* Monthly return rate
* Investment period
* Reinvestment of returns

The calculation follows the structure:

```text
Future Value = FV(monthly rate, period, monthly contribution)

Dividends = Portfolio Value × monthly return
```

## 🏢 REIT Segments

The tool considers the following REIT categories:

* Paper
* Brick-and-mortar
* Hybrid
* FOFs
* Development
* Hospitality

Allocation percentages are defined according to the selected investment profile.

## 📂 Project Structure

```text
Investment-Simulation/
│
├── Investment Simulation.xlsx
└── README.md
```

### Worksheets

**Data**
Contains parameters, simulations, investment scenarios, and financial projections.

**Planilha2**
Contains REIT allocation percentages by investor profile.

## 🛠️ Technology

* Microsoft Excel
* Financial formulas
* Lookup functions
* Scenario modeling
* Investment simulation

## ⚠️ Disclaimer

This project is intended for **educational and financial planning purposes**. 
