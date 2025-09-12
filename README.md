# SpecialProblem

This repository tracks my replication of:  
**“Empirical Analysis of Hierarchical Pathfinding in Lifelong Multi-Agent Pathfinding with Turns.”**  
DOI: https://doi.org/10.3390/systems13050331

## Dataset (from the paper’s Notes)
Primary sources used by the authors:
- League of Robot Runners: https://www.leagueofrobotrunners.org/
- MAPF Competition Benchmark Archive (2023): https://github.com/MAPF-Competition/Benchmark-Archive/tree/main/2023%20Competition
- MAPF Competition Code Archive – Team_JOliver (2023): https://github.com/MAPF-Competition/Code-Archive/tree/master/2023%20Competition/Team_JOliver

> Data Availability (paper): “Dataset available on request from the authors.”

## Replication Environment
Experiments here will run on a lower-specced laptop than the authors’ VM. Expect runtime differences; correctness and methodology matching are the priorities.

**My machine**
- OS: Linux Mint 22.2 Cinnamon  
- CPU: Intel Core i7-10510U (4C/8T) @ 1.80 GHz  
- GPU: NVIDIA GeForce MX230  
- RAM: 16 GB @ 2667 MT/s

## Repo Layout
- /docs → notes, protocol, paper excerpts
- /src → implementations and experiment runners
- /data → maps, scenarios, configs
- /results → logs, figures, tables

## Goals
1. Reproduce experimental setup and datasets.
2. Reimplement hierarchical pathfinding variants and SIPP baseline.
3. Compare outputs to the paper’s reported figures/tables.
