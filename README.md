# The Network of Network Science: An Analysis of Co-Authorship

## Overview

This is a project submission for the course "Socioeconomic Network Analysis" under the supervision of Dr. Giordano de Marzo during the winter semester of 2025/2026 at the university of Konstanz.

This project investigates the structure of the academic field of network science using a co-authorship network. The goal is to understand how researchers collaborate, how scientific communities form, and which researchers play a key role in connecting the field.

## Methods

The following analysis was perfomed

- Network structure: Degree distribution, density, clustering, and path lengths
- Centrality: Degree, betweenness, closeness, and eigenvector centrality
- Robustness: Network resilience to random failures and targeted attacks
- Community detection: Identification of research communities using the Leiden algorithm

## Key Findings

The network exhibits small-world characteristics and a degree distribution consistent with a scale-free structure, however we could not statistically verify this property making this finding tentative. 
Researchers form tightly connected communities linked by a small number of important researchers.
The network is relatively robust to random node removal but vulnerable to targeted attacks on key connecting researchers.
Community detection identifies 19 distinct research communities.

## Tools & Data

The analysis uses the co-authorship network provided by Rossi and Ahmed (2015) through the Network Data Repository.

## Reference

Thiele, J. (2026). The Network of Network Science: An Analysis of Co-Authorship.
