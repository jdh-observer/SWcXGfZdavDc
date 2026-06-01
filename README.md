# Senatorial Worlds Between Absolutism and Democracy, 1848–1946

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jdh-observer/SWcXGfZdavDc/main?filepath=article.ipynb)

The Italian Senate under the Statuto Albertino (1848–1946) presents a constitutional paradox: a chamber endowed with co-equal legislative authority yet never formally reformed, whose composition registered a century of profound political transformation through channels of recruitment that remained textually unchanged. Existing scholarship has approached the Senate primarily through legal-institutional or biographical lenses, without systematically reconstructing its evolving prosopographical profile across successive regime phases. This article adopts a hybrid digital history methodology, combining web scraping of approximately 2,300 biographical records from the senato.it platform with structured prosopographical analysis within a reproducible JupyterLab environment. We hypothesise that the Senate functioned as an apparatus for controlled elite reproduction, periodically recalibrated through strategic nomination waves that absorbed new social material while preserving older hierarchies of wealth, office, and distinction. The findings confirm that the parliamentary route, the aristocratic dimension, and the macro-professional composition of the chamber evolved unevenly across five periods, revealing a logic of managed inertia through which the constitutional form outlived the political orders that had created it.

## Reproducibility note

The original prosopographical dataset was constructed through automated retrieval of biographical records from the historical database of the Italian Senate (`senato.it`). At the time of data collection, the automated procedure documented in the notebook ran successfully and was used to build the database analysed in the article.

Since then, the website has introduced a bot/human-verification mechanism that prevents the initial data-retrieval stage from being executed automatically under the current access conditions. The scraping section is therefore retained in the notebook as documentation of the original data-collection procedure.

To ensure the reproducibility of the subsequent data-processing and analytical stages, the output of the original retrieval process is provided in this repository as:

```text
script/senatori_regno_1848_1943_bio.xlsx
```

The analytical workflow can therefore be executed from the deposited dataset even though the original automated retrieval from `senato.it` is no longer directly reproducible.

## Requirements

The Python packages required to execute the notebook are listed in `requirements.txt`. They can be installed with:

```bash
pip install -r requirements.txt
```
