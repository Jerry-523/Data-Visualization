
# 🛡️ Assignment 2 – Cybersecurity Visualization Project

**Title:** Mapping the Landscape of Cyber Attacks  
**Theme:** Types of Cyberattacks and Their Targets

---

## 📌 1. Challenge Description

**Data Source:**  
- ENISA Threat Landscape Reports (European Union Agency for Cybersecurity)  
- MITRE ATT&CK Framework  
- Statista (visual counts of incidents)  
- Supplemented with fictional/simulated data for academic visualization

**Motivation:**  
- Help non-technical audiences understand the growing landscape of cyber threats  
- Clarify the differences between attack types and their usual targets  
- Reveal trends and vulnerabilities that require urgent attention

**Audience:**  
- University students in tech and non-tech fields  
- IT policy makers and business decision-makers  
- General public with interest in cybersecurity

**Context:**  
- Educational settings: lectures, awareness campaigns  
- Security newsletters or internal training materials in companies

**Design Implications:**  
- Must be readable without technical jargon  
- Use icons and clear categorization to help identify attack types  
- Highlight scale and frequency using size/color/intensity  
- Group related attack families and simplify MITRE matrix structure

---

## 📊 2. Visualization Exploration

### 📈 Visual 1 – Bar Chart: Number of Incidents by Attack Type  
- Type: Horizontal bar chart  
- Version 1: Simple bars, ordered alphabetically  
- Version 2: Sorted by frequency, with color-coded categories (e.g., malware, social engineering, etc.)

### 🌍 Visual 2 – Network Graph: Attack Vectors and Targets  
- Type: Force-directed graph  
- Version 1: Each attack linked to a general target (e.g., phishing → individual)  
- Version 2: More granular with layered targets (e.g., ransomware → SMBs, healthcare)

### 🧱 Visual 3 – Matrix Overview: Tactics vs Techniques (inspired by MITRE ATT&CK)  
- Type: Grid layout  
- Version 1: Tactics on columns, simplified techniques as rows  
- Version 2: Heatmap cells showing prevalence (fictional count or %)

---

## 🧩 3. Final Design Description

**Chosen format:** Infographic (A3 landscape)  

**Included Elements:**  
- 3 visualizations: Bar chart, force-directed graph, matrix  
- Custom icons representing attack types (e.g., bug, lock, envelope)  
- Title: “The Cyber Threat Map”  
- Subtitle: “A visual overview of attack types and their primary targets”  
- Annotations explaining categories and techniques  
- Color palette: blue (technical), red (attacks), gray (neutral)

**Design Rationale:**  
- Simplified MITRE mapping to avoid overwhelming viewers  
- Used color and shape coding for better scan-ability  
- Balanced layout: left (summary), center (core visuals), right (impact + legend)

---

## 💬 4. Feedback Summary

**Participants:**  
- Alice (CS graduate), Bruno (business student), Carla (HR officer)  

**Main Feedback:**  
- Alice: Loved MITRE grid, suggested simplifying names even more  
- Bruno: Bar chart was clear, but graph edges were confusing  
- Carla: Requested icon glossary and color-blind-safe palette

**Changes made:**  
- Replaced full MITRE technique names with icons and short terms  
- Added legend below each chart  
- Modified colors for higher contrast and accessibility

---

## 🛠️ 5. Tool Critique

### 📊 Tool 1 – Tableau Public  
- Goal: General-purpose BI dashboard with drag-and-drop interface  
- Pros: Easy learning curve, rich built-in visuals  
- Cons: Limited for custom interactions, free version lacks privacy  
- Useful for: Bar chart and matrix prototyping  
- Improvements: More open export options for D3 or web embedding

### 💻 Tool 2 – D3.js  
- Goal: JavaScript library for creating custom visualizations in the browser  
- Pros: Fully customizable, supports force-directed graphs and SVG  
- Cons: Steep learning curve, requires HTML/JS/CSS skills  
- Useful for: Building the interactive version of the network graph  
- Improvements: Better onboarding via templates or UI builder

---

## 📎 Final Notes

- The infographic version is exportable as PNG, PDF, or poster-ready layout.  
- Data was partially simulated for demonstration.  
- See `visualization_drafts/` folder for sketches and iterations.
