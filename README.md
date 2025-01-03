# Multi-Criteria Decision Making (MCDM) ![license](https://img.shields.io/github/license/Pegah-Ardehkhani/Multi-Criteria-Decision-Making.svg)

<p align="center"> 
  <img width="700" height="400" src="https://i.ytimg.com/vi/7OoKJHvsUbo/maxresdefault.jpg"> 
</p>

This repository provides various algorithms and methods for Multi-Criteria Decision Making (MCDM), which is a set of approaches used to evaluate and prioritize alternatives based on multiple, often conflicting, criteria. These methods are commonly used in fields such as business, engineering, economics, healthcare, and environmental management, where decisions need to account for various factors.

## Table of content ✍️

- [01. TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)](https://github.com/Pegah-Ardehkhani/Multi-Criteria-Decision-Making/tree/main/01.%20TOPSIS) <a href="https://colab.research.google.com/github/Pegah-Ardehkhani/Multi-Criteria-Decision-Making/blob/main/01.%20TOPSIS/TOPSIS.ipynb" target="_parent\"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> [![nbviewer](https://img.shields.io/badge/render-nbviewer-orange.svg)](https://nbviewer.org/github/Pegah-Ardehkhani/Multi-Criteria-Decision-Making/blob/main/01.%20TOPSIS/TOPSIS.ipynb)
- [02. VIKOR (VlseKriterijumska Optimizacija I Kompromisno Resenje)](https://github.com/Pegah-Ardehkhani/Multi-Criteria-Decision-Making/tree/main/02.%20VIKOR) <a href="https://colab.research.google.com/github/Pegah-Ardehkhani/Multi-Criteria-Decision-Making/blob/main/02.%20VIKOR/VIKOR.ipynb" target="_parent\"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> [![nbviewer](https://img.shields.io/badge/render-nbviewer-orange.svg)](https://nbviewer.org/github/Pegah-Ardehkhani/Multi-Criteria-Decision-Making/blob/main/02.%20VIKOR/VIKOR.ipynb)
- [03. AHP (Analytic Hierarchy Process)](https://github.com/Pegah-Ardehkhani/Multi-Criteria-Decision-Making/tree/main/03.%20AHP) <a href="https://colab.research.google.com/github/Pegah-Ardehkhani/Multi-Criteria-Decision-Making/blob/main/03.%20AHP/AHP.ipynb" target="_parent\"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> [![nbviewer](https://img.shields.io/badge/render-nbviewer-orange.svg)](https://nbviewer.org/github/Pegah-Ardehkhani/Multi-Criteria-Decision-Making/blob/main/03.%20AHP/AHP.ipynb)
- [04. SAW (Simple Additive Weighting)](https://github.com/Pegah-Ardehkhani/Multi-Criteria-Decision-Making/tree/main/04.%20SAW) <a href="https://colab.research.google.com/github/Pegah-Ardehkhani/Multi-Criteria-Decision-Making/blob/main/04.%20SAW/SAW.ipynb" target="_parent\"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> [![nbviewer](https://img.shields.io/badge/render-nbviewer-orange.svg)](https://nbviewer.org/github/Pegah-Ardehkhani/Multi-Criteria-Decision-Making/blob/main/04.%20SAW/SAW.ipynb)

## Introduction

Multi-Criteria Decision Making (MCDM) is essential when faced with decisions that involve multiple criteria, some of which may conflict with each other. This repository includes implementations of several popular MCDM techniques to help users systematically evaluate and rank alternative solutions based on multiple criteria.

The methods in this repository allow you to:

- Assign weights to criteria.
- Evaluate alternatives based on different factors.
- Rank alternatives to aid in decision-making.

## Methods

Below are some commonly used MCDM methods:

1. **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution):**
 - A method that ranks alternatives based on their distance from an ideal solution (best case) and a negative-ideal solution (worst case), aiming to find the alternative closest to the ideal and farthest from the negative-ideal.

2. **VIKOR (VlseKriterijumska Optimizacija I Kompromisno Resenje):**
 - VIKOR is a Multi-Criteria Decision Making method that seeks to find a compromise solution by ranking alternatives based on their proximity to the ideal solution, while considering the balance between the best and worst performances across all criteria.

3. **AHP (Analytic Hierarchy Process):**
 - A method that uses pairwise comparisons and a hierarchical structure to prioritize alternatives.

4. **SAW (Simple Additive Weighting)**
 - A method where alternatives are ranked by summing the weighted normalized values of each criterion, making it easy to apply and interpret.
   
5. **WSM (Weighted Sum Model):**
   - A linear aggregation method where alternatives are scored by summing the weighted values of each criterion.

6. **Elimination and Choice Translating Reality (ELECTRE):**
   - A family of methods used to solve multi-criteria decision problems by eliminating inferior alternatives.

7. **PROMETHEE (Preference Ranking Organization Method for Enrichment Evaluations):**
   - A pairwise comparison method based on the preferences of decision-makers.
