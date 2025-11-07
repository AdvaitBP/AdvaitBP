# Hi, I’m Advait

I like building useful things with data—especially when the outcome touches land, water, or energy.  
Most of my work turns messy, real-world inputs (documents, maps, sensors) into tools that help people decide faster and better.

- Duke University ’27 — Math & CS, minor in Environmental Science  
- Looking for Summer ’25 internships in data/ML/SWE  
- Based in Durham, NC • open to remote

## What I’m building now
- **County solar-ordinance pipeline → map.** Scrape + OCR public documents, classify them, load to Postgres, and serve a Leaflet map for analysts. Built so non-engineers can run a county in minutes.
- **Protected-area impact on deforestation.** Clean spatial layers (Hansen, WDPA, GPWv4, OSM), do matching/ATT, and report effect sizes with proper balance checks.
- **Coastal marsh remote sensing.** Small, reproducible subset of our SatMAE/DINO/ViT experiments; tiling, training, and error analysis you can actually run.

## Selected projects
- **Strata ordinances → Postgres → Flask/Leaflet** · end-to-end ETL, restartable jobs, small demo dataset.  
  Repo: `strata-ordinances-pipeline` (sanitized public version)
- **Causal impact of protected areas** · matching, randomization inference, ATT with clear assumptions.  
  Repo: `deforestation-causal-inference`
- **Spartina remote sensing** · lightweight subset of our models and evaluation figures.  
  Repo: `spartina-remote-sensing`
- **Air quality forecasting** · API ingestion → SQL store → TF/PyTorch models with alerts.  
  Repo: `air-quality-forecasting`
- **Met coal sentiment vs. prices** · scraper → sentiment → simple regressions and caveats.  
  Repo: `met-coal-sentiment`
- **Cervical-imaging curation** · Mongo schema, validation, and de-dup checks with sample JSON.  
  Repo: `cervical-imaging-mongo-curation`

> I keep repos small, runnable, and honest about limits. If something requires private data, I publish a clear, reproducible slice with synthetic or public samples.

## How I work
- Python first (Pandas/NumPy/PyTorch/TensorFlow), Postgres/Mongo when it helps, and simple web backends (Flask/FastAPI) to put results in front of people.
- Maps when the question is spatial; tests and small CI so things don’t break on a Tuesday.
- Bias toward shipping: a working demo beats a perfect diagram.

## Contact
- **Email:** advait.bhaskarpandit@duke.edu  
- **LinkedIn:** /in/advait-bhaskarpandit  
- **GitHub:** @AdvaitBP

_If you’re building climate, conservation, or public-health tech and need someone who can take a problem from “we have some data” to “here’s the tool,” I’d love to talk._
