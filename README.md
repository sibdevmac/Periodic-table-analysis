# Periodic Table Data Analysis

On **6th March 1869**, **Dmitri Mendeleev** presented the first **Periodic Table of Elements** to the Russian Chemical Society. This historical contribution helped scientists understand patterns among chemical elements.

Inspired by this milestone, this project converts the **periodic table into a structured dataset** and analyzes the **hidden patterns using data analysis and visualization techniques**.

## Dataset

The dataset used for this analysis is available here:

Dataset Link:  
https://github.com/Bluegrams/periodic-table-data/blob/master/Periodica.Data/Data/ElementData.csv

This dataset contains multiple attributes of chemical elements such as:

- Atomic Number
- Electronegativity
- Atomic Radius
- Ionization Energy
- Density
- Melting Point
- Boiling Point
- Element Abundance
- Discoverer

These properties allow us to analyze patterns within the periodic table.

---

# Research Questions

## RQ1: How do atomic properties change across the periodic table?

To answer this question, the graphs **"Electronegativity vs Atomic Number"** and **"Atomic Radius Trend Across Elements"** were analyzed.

<img width="846" height="545" alt="image" src="https://github.com/user-attachments/assets/6e7e305b-4d73-4aca-8baf-ea4b0cec478f" />
<img width="850" height="545" alt="image" src="https://github.com/user-attachments/assets/f921f656-be66-4369-9e6b-f7bdc604e7a8" />

### Key Findings

- **Electronegativity and Ionization Energy** have a **strong positive correlation (0.91)**.
- Both **decrease as atomic radius increases**, meaning **smaller atoms attract and hold electrons more strongly**.
- Moving **left to right across a period**, the **atomic radius decreases**.
- Moving **down a group**, the **atomic radius increases**.

These findings align with the **fundamental periodic trends** observed in chemistry.

---

## RQ2: Which elements are most abundant in Earth's crust vs the universe?

The dataset also provides information about **element abundance in Earth's crust and the universe**.

### Earth's Crust (Most Abundant Elements)

| Element | Abundance |
|-------|-------|
| Oxygen | 461000 |
| Silicon | 282000 |
| Aluminium | 82300 |
| Iron | 56300 |
| Calcium | 41500 |

### Universe (Most Abundant Elements)

| Element | Abundance (%) |
|-------|-------|
| Hydrogen | 75% |
| Helium | 23% |
| Oxygen | 1% |
| Carbon | 0.5% |

### Insight

- **Earth’s crust is dominated by heavier rocky elements** like **Oxygen, Silicon, and Aluminium**.
- The **Universe is dominated by Hydrogen and Helium**, which formed after the **Big Bang expansion**.

---

## RQ3: How do physical properties influence the state of matter?

Two visualizations were used:

- **Melting Point vs Boiling Point by State**
<img width="859" height="545" alt="image" src="https://github.com/user-attachments/assets/1d3bce1c-8343-47a9-ade8-f10e951d0ab4" />
- **Density vs Melting Point**
<img width="859" height="545" alt="image" src="https://github.com/user-attachments/assets/d8852d8e-34a4-4066-acbf-8cf93734274d" />

### Key Observations

- Elements with **higher melting points tend to have higher boiling points**, meaning **stronger atomic bonds require more energy to break**.
- **Solids** generally have **high melting and boiling points**.
- **Liquids** have **moderate values**.
- **Gases** have **very low melting and boiling points**.

Additionally:

- The **Density vs Melting Point graph** shows that **denser elements often have higher melting points**.

This helps explain how **physical properties determine whether an element exists as a solid, liquid, or gas**.

---

# Element Classification Visualization

A **Tree Map visualization** was created to classify elements based on **their discoverers**. This helps illustrate the **historical contribution of scientists to the discovery of elements**.

---

# Conclusion

This project demonstrates how the **periodic table can be transformed into a structured dataset for data science analysis**. By applying visualization and correlation analysis, we can better understand:

- Periodic trends of atomic properties
- Element abundance in Earth vs the Universe
- Relationships between physical properties and states of matter

Such data-driven analysis helps reveal the **scientific patterns hidden within the periodic table**.

---

# Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly (Treemap Visualization)

---

# Author
Sibankar Saha
