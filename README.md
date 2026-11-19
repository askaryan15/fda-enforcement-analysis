# FDA Enforcement Analysis
**Does FDA enforcement follow product-safety risk?**

BA780 Team Project · Boston University Questrom School of Business · MS in Business Analytics · Fall 2026

## Business Question
When products are recalled for safety problems, does the FDA respond with stronger compliance actions such as warning letters, seizures and injunctions? This project explores whether FDA enforcement lines up with product-safety risk across product types, firms, locations and time.

## Why It Matters
- **Regulators:** shows whether enforcement resources are going where the risk is highest
- **Companies:** shows how recall history relates to the chance of regulatory action
- **Consumers:** gives a view of how well product-safety oversight works in practice

## Data
- **Source:** FDA Data Dashboard: Recalls and Compliance Actions datasets
- **Key fields:** product type, recall classification (Class I, II, III), firm, location, date and action type

## Approach
1. Cleaned and standardized the recalls and compliance actions data
2. Explored patterns by product type, firm, location and year
3. Compared how often and how severely products are recalled against how often enforcement actions follow
4. Built visualizations to summarize the patterns

## What We Explored
- Which product types have the most recalls and the most enforcement actions
- Whether more serious recalls (Class I) are linked to stronger follow-up enforcement
- How recalls and enforcement actions have changed over time
- Whether certain firms or locations show up repeatedly

## Tools
Python · pandas · NumPy · Matplotlib · Google Colab · Jupyter Notebook

## Repository Contents
| File | Description |
|---|---|
| `A06_FDA_Regulatory_Action_Analysis (7).ipynb` | Full exploratory data analysis notebook |
| `README.md` | Project overview |

## Limitations and Next Steps
- Matching firms across the two datasets is imperfect because names are recorded differently
- The analysis is exploratory and shows patterns, not causes
- Next step: build a model to predict whether a recall leads to an enforcement action

## Team
Aryan Bajaj, Filip, Malak, Rislyn and Fan-yu (David) Chiu
