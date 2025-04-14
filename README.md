# Trustworthy Federated Learning - Assignment 6

This repository contains solutions and experiments for **Assignment 6: Trustworthy Federated Learning**, focusing on enhancing the trustworthiness of FL systems by addressing explainability and privacy challenges.

---

## Overview

This assignment explores techniques to make Federated Learning (FL) systems more trustworthy by:

- Improving model explainability through subjective penalties.
- Analyzing privacy vulnerabilities in FL systems.

---

## Repository Structure

| File | Description |
|------|-------------|
| `Assignment6__Trustworthy_FL.ipynb` | Main notebook with implementations, experiments, and detailed analysis. |

---

## Topics Covered

### FedGD - Federated Gradient Descent
- Implementation of standard Federated Gradient Descent (FedGD) algorithm.

### FedGD with Subjective Explainability
- Adds a penalty term to encourage model interpretability.
- Calculates the gradient of the explainability penalty term.
- Reference: Section 8.4 from FLBook.

### Privacy Attack: "Where is Alice?"
- Demonstrates a privacy attack scenario.
- Analyzes how a malicious client (Bob) can infer private model parameters of another client (Alice).
- Applies `FedGD_zero_loss` strategy on an empirical graph `G_Alice_Bob`.

---

## Techniques Implemented

- Custom gradient calculation for subjective explainability.
- Privacy attack simulation in FL context.
- Data preparation using standardization for robust learning.

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/TrustworthyFL-Assignment6.git
cd TrustworthyFL-Assignment6
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

---

## Usage

Run the notebook:

```bash
jupyter notebook Assignment6__Trustworthy_FL.ipynb
```

---

## Results & Analysis

- Analysis of subjective explainability gradients.
- Evaluation of privacy vulnerabilities in FL.
- Insights into how explainability and privacy interact in FL systems.

---

## References

- *Federated Learning* by Jakub Konečný, H. Brendan McMahan, Daniel Ramage
- FLBook — Section 8.4
- Finnish Meteorological Institute (FMI) weather data

---


