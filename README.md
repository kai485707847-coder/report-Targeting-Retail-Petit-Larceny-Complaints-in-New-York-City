# NYC Retail Petit Larceny Analysis

[View the live report](https://kai485707847-coder.github.io/report-Targeting-Retail-Petit-Larceny-Complaints-in-New-York-City/)

## Overview

An academic data analysis project exploring **136,022 cleaned NYPD complaint records** from **October–December 2024**. It compares retail theft patterns across premise types, boroughs and hours to inform a proposed 90-day retail support pilot.

The project includes data cleaning, offence comparisons, a proportion hypothesis test, a borough map, heatmaps and hourly charts. Results and limitations are presented in a self-contained HTML report.

## Technologies

- **R and tidyverse:** data cleaning, analysis and visualisation.
- **jsonlite, scales and knitr:** geographic data, formatting and tables.
- **Quarto, HTML, CSS and JavaScript:** report generation and presentation.
- **GitHub Pages:** static website hosting.

## How to run

**View:** open the live report above, or download `index.html` and open it in a browser. No installation, dataset or server is needed to view the saved results.

**Rebuild (optional):** requires R, Quarto, the source `.qmd`, its R packages and the referenced CSV, GeoJSON and portrait files. With a reviewed source copy named `report.qmd` and its input paths configured, run:

```bash
quarto render report.qmd --to html --output index.html
```

## Data and notes

Data come from [NYPD Complaint Data Historic](https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i/about_data) and [NYC Borough Boundaries](https://data.cityofnewyork.us/resource/gthc-hcne.geojson?$limit=5000). Complaint counts do not measure all theft or risk per visitor, and the analysis does not establish causation.

No school-provided starter code was used. AI assistance and third-party sources are acknowledged in the report. Public releases should exclude personal identifiers and private course materials.
