# KDD-Enade-UFPA-Courses

This repository contains code and resources for conducting data analysis on microdata from the Brazilian National Exam of Student Performance (ENADE). This project aims to provide insights and visualizations that can help researchers and higher education coordinators and principals better understand student performance and educational trends.

## Table of Contents

- [About ENADE](#about-enade)
- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
  - [Running on Google Colab](#running-on-google-colab)
- [Usage](#usage)
  - [Data Preparation](#data-preparation) 
  - [Visualization](#visualization)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## About ENADE <a name="about-enade"></a>


The National Exam of Student Performance (ENADE) is a standardized assessment in Brazil that evaluates the performance of undergraduate students in various fields of study. It plays an important role in assessing the quality of higher education institutions and providing data for educational improvement.

## Project Overview <a name="project-overview"></a>

This project focuses on analyzing Enade microdata to extract meaningful insights and trends related to student performance through the discovery of useful and non-trivial patterns in the exam's data. By using this repository, it is possible to explore performance across subjects and understand correlations between student grades and factors such as family income and weekly study hours. By inputing the code of the course on which the analysis is to be performed, the code automatically pre-process and selects the data attributes that are relevant to the analysis and displays the results through graphs and tables visualizations.

## Getting Started <a name="getting-started"></a>

### Running on Google Colab <a name="running-on-google-colab"></a>

The code is designed to be run on Google Colab, removing the need for manual modules installations. However, it can also be run on Jupyter Notebook, as long as all the required dependencies are properly installed. Follow these steps to get started:

1. Open Google Colab: https://colab.research.google.com/
2. Navigate to `File` > `New Notebook`.
3. Copy and paste the code from the provided notebooks in this repository.
4. Adjust paths and file locations if necessary.
5. Run each cell to execute the code.

## Usage <a name="usage"></a>

Follow these steps to conduct the microdata analysis:

### Data Preparation <a name="data-preparation"></a>

- Place the raw ENADE microdata files and the higher educatation instituitions code-name dictionaries (both in .csv format) in any directories, and adjust their paths in the code accordingly.
- Run the provided notebook to preprocess the data, handle missing values, and generate the results by inputing the [e-mec code](https://emec.mec.gov.br/) of the course you want to perform the data analysis on.

### Visualization <a name="visualization"></a>

- Generate graphs and table visualizations within the Google Colab environment by running the driver code. One can also export the graphs (PDF format) and tables ($\LaTeX$ format) for personal use.

## Contact <a name="contact"></a>

If you have any questions or suggestions, please feel free to contact me at [eudemonteirodahora@gmail.com](mailto:eudemonteirodahora@gmail.com).

## Acknowledgements <a name="acknowledgements"></a>

This repository was developed as a research project at the Universidade Federal do Pará, with the guidance of Professor [Reginaldo Santos](https://www.escavador.com/sobre/5457885/reginaldo-cordeiro-dos-santos-filho)

---
