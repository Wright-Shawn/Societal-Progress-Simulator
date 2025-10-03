# Societal Health Simulator  

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)  

An **interactive, AI-assisted web tool** that explores a **toy model of societal health**.  
⚠️ This project is for **exploration and demonstration only — not forecasting or policy use.**  
It also serves as a **case study in reproducibility and validation** using the Aurora Workflow Orchestration (AWO) and Continuous Research Integration (CRI).  

[wrightsocietalmodel.com](https://wrightsocietalmodel.com/)  

---

## Model  

The conceptual model is based on a scalar progress function:  

**P(t) = (R × E × C)^α ÷ (I × D)^β**  

where:  
- **Fairness of Resources (R)** — distribution of food, housing, income, healthcare  
- **Education Quality (E)** — access to quality education and critical thinking  
- **Social Trust (C)** — cooperation and trust among people  
- **Government Instability (I)** — higher = more chaotic/corrupt institutions  
- **Misinformation (D)** — higher = more fake news and propaganda  
- **α, β** — exponents tuning nonlinear sensitivity  

📝 **Note:** The current web version implements a **simplified scoring system** (linear averages of positives and negatives). The full equation is reserved for future iterations.  

This deliberate imperfection demonstrates how AI-assisted work can be logged, validated, and iteratively improved.  

---

## Features  

- Interactive sliders for the five key drivers  
- Instant feedback on societal status (**thriving, struggling, or collapsing**)  
- Historical presets (*Ancient Rome at Peak*, *Great Depression USA*)  
- Designed as a **portfolio-grade example** of transparent AI+human orchestration  

---

*(The deployed site runs from an internal app build; this repo hosts documentation and licensing.)*  

---

## Citation  

If you reference this simulator in academic or public work, please cite the repository.  
A `CITATION.cff` file will be added once the first archived release is created (Zenodo).  

---

## Author  

**Shawn C. Wright**  
AI-Assisted Researcher | Developer of the Societal Health Simulator  

- ORCID: [0009-0006-6043-9295](https://orcid.org/0009-0006-6043-9295)  
- Email: (shawnkardin (at) gmail (dot) com)  

---

## License  

This work is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International** license (CC BY-NC-SA 4.0).  
See `LICENSE` for details.  

---

## Status  

**Prototype** — live at [wrightsocietalmodel.com](https://wrightsocietalmodel.com).  
Development is ongoing, with future work focusing on equation fidelity, dataset integration, and reproducibility testing under AWO/CRI.  
