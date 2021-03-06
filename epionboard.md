
# tiny.cc/epionboard

# 1. GitHub
[Introduction to GitHub](https://lab.github.com/githubtraining/introduction-to-github) free short course<br>

One platform to store data (with PHI caveats), track code changes and version control, share code and results, write equations and papers, publish websites, share data and results, do project management, provide/request tech support, clone other's research, and even more.<br>

## Version control examples
[Demo code change](https://github.com/opioiddatalab/public/blob/master/epionboard/demoscript.do)<br>
[Demo data table change](https://github.com/opioiddatalab/public/blob/master/epionboard/demodatachange.csv)

# 2. Jupyter Notebooks

## Examples
1. [Equations on how to calculate milligrams of morphine equivalents](https://opioiddatalab.github.io/MMEequations/MMEequations.html)
1. [Dix Asylum historical ledger data cleaning and basic descriptives](https://opioiddatalab.github.io/public/DixAsylum/docs/Dix%20Hospital%20Ledger%20-%20data%20cleaning.html) (HTML version)
1. ICPE abstract: Do Early Prescribers Of New Drugs Have Different Risk Management Practices? [ipynb](https://github.com/opioiddatalab/PharmacistPrescriberSurveys/blob/050d94be74541a502130f4a8a223a80926b41074/earlyAdopters/ICPEabstractEarlyPrescribers.ipynb) | [HTML](https://opioiddatalab.github.io/PharmacistPrescriberSurveys/earlyAdopters/ICPEabstractEarlyPrescribers_submitted.html)
1. Submitted manuscript on [COVID social distancing using smartphone movement data](https://opioiddatalab.github.io/covid/locationcovid_exploratory.html)

## Pre-requisite: Python
While Jupyter runs code in many programming languages, Python is a requirement (Python 3.3 or greater, or Python 2.7) for installing the JupyterLab or the classic Jupyter Notebook.
[Download here](https://www.python.org/downloads/)

## Download and install Jupyter
[Install](https://jupyter.org/install) from a terminal window. Check the [Installation Guide](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) if you get stuck.

## R and Python
You're good to go!<br>

## SAS
SAS installation [overview](https://blogs.sas.com/content/sasdummy/2016/04/24/how-to-run-sas-programs-in-jupyter-notebook/) and [instructions](https://github.com/sassoftware/sas_kernel)<br>
SAS remote server [documentation](https://enterprise-docs.anaconda.com/en/docs-site-5.1.2/user-guide/projects/connect-sas-server.html). Step-by-step [instructions](https://ambermd.org/tutorials/analysis/tutorial_notebooks/remote_notebook/index.html). We have not yet tested this with the MarketScan data on the protected server, but if you're interested in exploring it, please let us know (nab@unc.edu). 

Once you get the general hang of things, you can also [configure](https://sassoftware.github.io/saspy/install.html#configuration) Jupyter to connect to remote server SAS, allowing you to keep data in secure environments.

## Stata
Standard installation uses the [Stata kernel](https://github.com/kylebarron/stata_kernel). But, if you want to run Python and Stata both in the same notebook, try the [ipystata](https://dev-ii-seminar.readthedocs.io/en/latest/notebooks/Stata_in_jupyter.html) kernel.

# Markdown
Markdown is a very simple syntax to help you generate text content without getting distracted by formatting. The text you generate is easily transferable to word processors and websites. Here's a [cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

# MathJax for Equations
MathJax is a standardized syntax for generating equations that can be displayed in web browsers, text documents, etc. [All the syntax](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference) is here. These will work in Jupyter Notebooks.

# Alternative Notebook Platforms
[Google Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb) is very easy if you are Python, and lets you run live code within the browser.
[R Markdown Notebook](https://rmarkdown.rstudio.com/lesson-10.html) built into RStudio [detailed guide](https://bookdown.org/yihui/rmarkdown/notebook.html)
[Apache Zeppelin](https://zeppelin.apache.org/) popular in cloud-based very big data settings using Spark, PostgreSQL, Angular, etc.

# FAQ
[What's the difference](https://towardsdatascience.com/jupyter-lab-evolution-of-the-jupyter-notebook-5297cacde6b) between JupyterLab versus Jupyter Notebook? Short answer: Go with JupyterLab because it is newer and easier to use, though a touch more complex to start with.

# 3. Containers
Containers are a key reproducibility tool. Here is a [plain language Docker startup guide](https://towardsdatascience.com/learn-enough-docker-to-be-useful-b7ba70caeb4b). 
