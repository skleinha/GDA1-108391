# Grundlagen der Anwendungsentwicklung A4
## Introduction to Pandas DataFrames – Replicating an Article in Markdown

### Repository Structure

**Root Folder:** */GDA1-108391/*
- `Pandas.ipynb`
- `Pandas.webp`

**Subfolder:** */.../dist/*
- `Pandas.html`
- `Pandas.webp`

**Subfolder:** */.../ipynb_checkpoints/*  
_Backup folder automatically created by Jupyter Notebook while working on `.ipynb` files._

---

### Abstract

The goal of Task 4 was to create a Jupyter Notebook (`Pandas.ipynb`) that imitates the layout and content of a given website (`pandasintroduction.html`) using Markdown syntax. Additionally, the listed Python code statements will be executed within the notebook. The focus was to apply the Markdown format correctly on the strings and to structure the text.

---

### File description

- `Pandas.ipynb` 
This notebook contains my solution to Task 4. The task was to rebuild a website using Markdown syntax and executing the Python code examples listed on that site. The notebook consists of two types of cells:

    - *Code cells:*  
       Those cells contain the executable Python code, which is being processed by the IPython kernel during the runtime. The output (e.g. queries, calculations/results, lists) is displayed directly below each cell.

    - *Markdown cells:*  
       Those cells contain the formatted text using Markdown-syntax, which is also being displayed within the notebook during the runtime.

---

- `Pandas.webp` 
An image embedded in the notebook (`Pandas.ipynb`). It is placed in the same folder with the notebook file on purpose. So it was not necessary to set relative or absolute paths within the notebook. Therefore a copy of the image also exists in the */dist/* folder, in order to be embedded in the exported HTML file.

---

- `Pandas.html`  
This is the final version of the notebook, which has been exported to HTML using Jupyter Notebook’s "Save and Export" feature. It represents the Markdown content and code output from the notebook. Note: Due to troubles with the conversion from Markdown to HTML possible formatting inconsistencies may occur that are not present in the original `.ipynb` file.
