# Societal Health Simulator — Black Mirror Tamagotchi Edition

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Interactive web-based simulator of a toy model of societal health. It is designed for **exploration, not forecasting**, and serves as a portfolio-grade example of AI-assisted research → simulation.

[wrightsocietalmodel.com](https://wrightsocietalmodel.com/)

---

## Model

The simulator is based on a simple scalar progress function:

**P(t) = [(R · E · C)^α] / [(I · D)^β]**

with the following drivers:

- **Fairness of Resources (R)** — how evenly food, housing, income, and healthcare are shared  
- **Education Quality (E)** — access to quality education and critical thinking  
- **Social Trust (C)** — how much people trust and work together  
- **Government Stability (I)** — higher = more chaotic/corrupt institutions  
- **Misinformation Level (D)** — higher = more fake news and propaganda  
- **α, β** — exponents tuning nonlinear sensitivity  

This is a **toy model** to surface intuitions about trade-offs — not a predictive macro model.

---

## Features

- Sliders for all five drivers (resources, education, trust, stability, misinformation)  
- Instant feedback on whether society is **stable, strained, or collapsing**  
- Simple historical presets (e.g., *Ancient Rome at Peak*, *Great Depression USA*)  

---

## Repository Layout

- `README.md` — this document  
- `LICENSE` — CC BY-NC-SA 4.0  
- `.gitignore` — Git ignore rules  

*(the deployed site runs from an internal app build; this repo hosts the license and project documentation)*  

---

## Citation

If you reference this simulator in academic or public work, please cite the repository.  
A `CITATION.cff` file will be added once the first archived release is created (Zenodo).

---

## License

This work is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International** license (CC BY-NC-SA 4.0).  
See `LICENSE` for details.

---

## Status

Prototype — live at [wrightsocietalmodel.com](https://wrightsocietalmodel.com).  