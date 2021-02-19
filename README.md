# Open Data Analysis on AgeGuess Public Data Set

## Data source

#### Introduction of the data 

"AgeGuess.org is a simple on-line game using biological and perceived age as biomarkers to address scientific questions related to aging in humans. The AgeGuess project updates the AgeGuess.org Public Data Set every three months." ([via](https://www.ageguess.org/download))

#### Download the data

- Download the latest data set from here: [https://www.ageguess.org/download](https://www.ageguess.org/download). The default encoding of the data set is ISO-8859-1.

- Download the data set which I manipulated from this page, there are 5 csv files: ag_gamers.csv, ag_guess.csv, ag_photos.csv, ag_quality,csv, ag_report.csv. I converted the encoding of csv from ISO-8859-1 to UTF-8.

#### Download the paper

Download and read the paper ***The AgeGuess database, an open online resource on chronological and perceived ages of people aged 5–100***, you will find the details of the game and the data, for example the meaning of every column. [https://www.nature.com/articles/s41597-019-0245-9](https://www.nature.com/articles/s41597-019-0245-9). 

## Installation

#### System requirements

- 32-bit or 64-bit computer.
- For Miniconda---400 MB disk space.
- For Anaconda---Minimum 3 GB disk space to download and install.
- Windows, macOS, or Linux.

#### Install Miniconda and Jupyter Notebook

1. "Miniconda is a free minimal installer for conda. It is a small, bootstrap version of Anaconda that includes only conda, Python, the packages they depend on, and a small number of other useful packages, including pip, zlib and a few others." ([via](https://docs.conda.io/en/latest/miniconda.html))

- Download miniconda for your computer from here: [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)

2. "The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text."([via]()) 

- Install Jupyter Notebook with conda after installing miniconda.

> conda install -c conda-forge jupyterlab

#### Install Python libraries

The Python libraries will be used are: pandas, numpy, matplotlib, seaborn, sklearn.

> conda install -c anaconda pandas

> conda install -c anaconda numpy

> conda install -c anaconda matplotlib

> conda install -c anaconda seaborn

> conda install -c anaconda sklearn

## Licensing

#### Licensing of the AgeGuess Public Data Set

AgeGuess Public Data Set is licensed under a **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**, it means you are free to:

- **Share** — copy and redistribute the material in any medium or format

- **Adapt** — remix, transform, and build upon the material

Under the following terms:

- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

- **NonCommercial** — You may not use the material for commercial purposes.

- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

#### Licensing of this study

As mentioned above, I must use the same licensing with the AgeGuess Public Data Set, so this study is also under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.
