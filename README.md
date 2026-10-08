# Social Search Project on r/advice 

<p align="center">8 July 2025</p>

## Overview

The **final project** for the course **Web and Social Networks Search and Analysis**, held by **Professor Marco Viviani** and **Professor Davide Mancino**.

The project focuses on the development of a **social search engine for Reddit**, using data collected from the `r/advice` community.

The main goal is to compare a traditional lexical retrieval approach, **BM25**, with a neural **Bi-Encoder** model for ranking comments according to their relevance to advice-seeking posts.

---

## Objectives

- Build a dataset of Reddit posts and associated comments
- Define relevance judgments for the retrieved comments
- Implement and compare **BM25** and a **Bi-Encoder**
- Evaluate retrieval performance using **Precision, Recall, MAP, and nDCG**

---

## Project Structure

The project is organized into the following main steps:

- Reddit dataset construction
- Creation of relevance judgments using the **Wilson score**
- Retrieval using **BM25**
- Neural retrieval using a **Bi-Encoder**
- Evaluation and comparison of the two approaches

---

## Repository Contents

- `NOTEBOOK_Course_Project.ipynb` — complete implementation and analysis
- `datasets/` — posts and comments datasets
- `REPORT_Course_Project.pdf` — detailed project report
- `PPT_Course_Project.pdf` — project presentation
