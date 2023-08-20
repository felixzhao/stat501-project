# stat501-project

# Reporting

LaTeX files, complete with templates and samples for reporting, can be found in the **'report'** folder.

- Update the **stat501-project-report.tex** file for report contents.

- Modify **BIBTEX_GOF.bib** for references.

- Visual **Studio Code** can be used to generate a PDF from the LaTeX files.

# Notebooks

Kindly create and execute the code in Google Colab. Once completed, save it to this repository.

When working with notebooks, consider adhering to the following guidelines:

"We recommend two primary steps for effective notebook usage:

1. Adopt a naming convention that indicates the owner and the sequence in which the analysis was conducted. We suggest the format **'<step>-<ghuser>-<description>.ipynb'** (e.g., **'0.3-bull-visualize-distributions.ipynb'**).

2. Refactor valuable components. Avoid repeating the same task across multiple notebooks. If it's related to data preprocessing, incorporate it into the pipeline at **'src/data/make_dataset.py'** and retrieve data from **'data/interim'**. If it's essential utility code, move it to **'src'**."

Reference: [DrivenData's Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/)

# Data

- Store raw data in the **'data/raw'** folder.

- Save pre-processed data in the **'data/processed'** folder.

# Data Security

**NOTICE:** Ensure all cell outputs are cleared, and avoid committing any data into the repo. We must refrain from making any data public.

# reuseable code

Any code that may be reused across different notebooks should be placed in the **'src'** folder.
