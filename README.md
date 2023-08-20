# stat501-project

# Reporting

Latex files with template and sample for reporting is under report folder.
Update stat501-project-report.tex file for report contents.
Update BIBTEX_GOF.bib for reference.
Vistual Code can used to generate pdf from latex file.

# Notebooks

Please create and run code in Google Colab, then save to this repo after finished it.

Suggesting to following below rule when working with notebooks


"There are two steps we recommend for using notebooks effectively:

Follow a naming convention that shows the owner and the order the analysis was done in. We use the format <step>-<ghuser>-<description>.ipynb (e.g., 0.3-bull-visualize-distributions.ipynb).

Refactor the good parts. Don't write code to do the same task in multiple notebooks. If it's a data preprocessing task, put it in the pipeline at src/data/make_dataset.py and load data from data/interim. If it's useful utility code, refactor it to src."

reference : https://drivendata.github.io/cookiecutter-data-science/

# Data

Raw Data can save in data/raw folder
pre-processed data please save in data/processed folder

# Data Security

NOTICE: Please clear all cells output, and do not commint any data into repo.
We should not publish any data to public.

# reuseable code

Any code need to reused in different notebook should create under src folder.
