# Societal Progress Simulator — Black Mirror Tamagotchi Edition

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Interactive simulator of a simple, tunable model of societal progress. It is designed for exploration, not forecasting, and serves as a portfolio‑grade example of AI‑assisted research → simulation.

Planned deployment:
[https://wrightsocietalmodel.com/]

---

## Model

We define a scalar progress function:

**P(t) = [(R(t) · E(t) · C(t))^α] / [(I(t) · D(t))^β]**

where:

- **R(t)** — resource equity / distribution  
- **E(t)** — education / capacity  
- **C(t)** — collective cohesion / trust  
- **I(t)** — institutional entropy / bureaucratic drag  
- **D(t)** — disinformation / noise  
- **α, β** — nonlinearity exponents

This is a controllable toy model intended to surface intuitions about trade‑offs, interventions, and sensitivity — not a predictive macro model.

---

## Features

- Sliders for initial conditions and exponents (α, β)
- Time‑evolution with optional noise
- Plots of P(t) and driver trajectories
- CSV export of the simulated time series

**Roadmap (short horizon):** scenario presets; timed interventions; run comparison; Monte Carlo bands; shareable links; PNG export; simple explainability card.

---

## Quickstart (local)

Prerequisites: Python 3.10+

```bash
# create a working directory and place the repo files in it
pip install -r requirements.txt
streamlit run app.py
```

The app will open in your browser (or at http://localhost:8501).

---

## Repository Layout

- `app.py` — Streamlit UI (sliders, plots, downloads)
- `model.py` — simulation core, deterministic + noisy paths
- `requirements.txt` — Python dependencies
- `README.md` — this document
- `CITATION.cff` — citation metadata (DOI to be added after first release archive)
- `LICENSE` — CC BY‑NC‑SA 4.0

---

## Citation

If you use or reference this simulator in academic or public work, please cite the repository. A `CITATION.cff` file is provided; a DOI will be added after the first archived release (Zenodo).

---

## License

This work is licensed under the **Creative Commons Attribution‑NonCommercial‑ShareAlike 4.0 International** license (CC BY‑NC‑SA 4.0).  
You may not use this work for commercial purposes. See `LICENSE` for terms.

---

## Status

Prototype. Functionally useful for exploration; expect iteration as scenarios and interventions are added.
