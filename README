# Food Consumption Patterns across Europe

Project overview
- This project develops models to explore and understand food consumption patterns across European countries. It addresses the high-dimensional nature of dietary data and uses multivariate/statistical techniques to summarize patterns, including clustering and latent class models.

Key aims
- Identify common dietary patterns across countries using dimension reduction and clustering.
- Provide interpretable summaries of consumption patterns and associate them with covariates (e.g., demographics).
- Offer reproducible notebooks demonstrating data processing, modeling, and visualization.

Repository structure
- notebooks/ — Jupyter notebooks with the full pipeline from raw data to results.
- data/ — raw and processed datasets or instructions on how to obtain them.
- outputs/ — figures and tables summarizing key findings.

Data
- The project likely uses dietary survey data or aggregated recipe/consumption datasets that map foods to consumption frequencies across countries.
- Expected data format: subject-level or country-level consumption frequencies for various food items.

Getting started
1. Clone the repository:
   git clone https://github.com/<owner>/-Food-Consumption-Patterns-across-Europe.git
2. Create an environment:
   python -m venv .venv
   source .venv/bin/activate
3. Install dependencies:
   pip install -r requirements.txt
4. Place datasets in data/raw/ and run notebooks via:
   jupyter lab

Analytic approach
- Data cleaning: handle missingness, harmonize food item taxonomy.
- Dimensionality reduction: PCA or correspondence analysis for compositional data.
- Clustering: k-means, hierarchical clustering, or latent class analysis for discrete pattern discovery.
- Modeling: regress identified patterns on covariates to assess associations (e.g., demographics, health outcomes).

Notebooks
- 01-data-prep.ipynb — cleaning and harmonizing food variables.
- 02-dimred-and-visualization.ipynb — PCA, biplots, and country maps.
- 03-clustering-and-lca.ipynb — cluster analyses and latent class modeling.
- 04-association-analysis.ipynb — regressions linking dietary patterns to outcomes.

Methods notes
- Latent class analysis (LCA) may be performed in Python (mixture models) or in R (poLCA). Where appropriate, notebooks include guidance for both.
- For compositional data, consider log-ratio transforms (e.g., CLR) before PCA/regression.

Reproducibility
- Seed randomness for clustering and model initialization.
- Save processed data and model outputs in data/processed/ to speed re-runs.

License & ethics
- Add a LICENSE file.
- Document data provenance and any use restrictions.

Contact & contributions
- Contributions welcome (improved models, alternative transforms, or additional visualizations).
- Open issues for collaboration or reproducibility questions.
