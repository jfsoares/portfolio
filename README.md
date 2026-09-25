# Data & AI Engineering Portfolio Hub

Welcome to my portfolio! This repository serves as the **Central Presentation Hub** for my Data and AI Engineering portfolio, demonstrating my skills in building robust data pipelines, deploying machine learning models, and solving complex data problems.

## Purpose

The primary goal of this repository is to serve as a central hub presenting my extended CV, personal brand, and a showcase of my projects. We use a **Hub-and-Spoke (Multi-Repo) model** where this repository is the Hub, and each complex project has its own dedicated GitHub repository (the Spoke).

## Structure

- **assets/**: Contains shared assets like images and diagrams used across the portfolio.
- **index.md**: The main landing page for the GitHub Pages site, containing the CV and project cards.
- **_config.yml**: Configuration file for GitHub Pages (Jekyll).

## Multi-Repo Governance & Standards

To ensure seamless integration between this Central Hub and the child project repositories, all child repositories must adhere to the following standards:

### 1. Central Hub Badge
Each child repository's `README.md` must display a top badge linking back to the main site:
```markdown
[![Portfolio Hub](https://img.shields.io/badge/Portfolio-Central%20Hub-blue?style=flat-square)](https://jorge-soares235.github.io)
```

### 2. Root-Level Isolation
Every child project puts its configuration (e.g., `databricks.yml`, `Dockerfile`, `pyproject.toml`, `.github/workflows/`) directly at the repository root. This allows AI agents and CI runners to execute without working-directory overrides.

### 3. Cross-Referencing
Every project card on the Central Hub points directly to its corresponding child repository: `https://github.com/jorge-soares235/<repo-name>`.

Feel free to explore the site and reach out if you have any questions or collaboration ideas!
