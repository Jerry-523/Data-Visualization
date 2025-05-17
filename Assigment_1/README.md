# 📘 Markov Chain & Visualization Critique Assignment

This repository contains solutions to two assignments from the Data Visualization course:

1. A programming-based simulation of Markov Chains
2. A critique and redesign of flawed real-world visualizations

---

## 📊 Assignment 1 – Visualization Critique & Redesign

### ✅ Task Summary

- Analyze 2 different flawed visualizations
- Identify 3 unique faults per visualization
- Redesign each visualization in Python/Matplotlib
- Explain how the new design solves the issues

---

### 📉 Visualization 1 – Overloaded Pie Chart

**Source:** Wikipedia ([Pie chart limitations](https://en.wikipedia.org/wiki/Pie_chart#Limitations))

**Faults Identified:**

1. Too many categories – hard to compare slices
2. Poor or missing labels
3. Inefficient format – pie charts aren't good for close comparisons

**Fix:**

- Replaced pie chart with a sorted bar chart
- Added labels and a clear axis
- Color chosen for readability

📎 Output: `redesign_visualizacao1.png`

---

### 🌍 Visualization 2 – Gradient of Voting Intensity

**Source:** Simulated data inspired by election maps

**Faults Identified:**

1. Binary color schemes hide voting intensity nuances
2. Lack of gradient to show close races
3. Geographic size overemphasizes less populous areas

**Fix:**

- Continuous color gradient centered at 50%
- Diverging colormap (blue-white-red) to show intensity
- Clear legend and uncluttered map visualization

📎 Output: `redesign_visualizacao2.png`

---

## 📦 Files Included

- `redesign_visualizacao1.png` – Redesign of pie chart
- `redesign_visualizacao2.png` – Redesign of COVID heatmap
- `requirements.txt` – Python packages
- `Markov_Chain_Assignment.ipynb` – Full simulation notebook
- `README.md` – This file

---

## 🛠 Installation

```bash
pip install -r requirements.txt
```
