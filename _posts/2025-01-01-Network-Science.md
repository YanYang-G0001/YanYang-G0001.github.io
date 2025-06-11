---
layout: post
title: "Analysis of Software Dependency Networks"
type: post
date: 2025-01-01
tags:
  - code available
  - Network Analysis
  - Python
  - networkx
---
📂[GitHub Repository](https://github.com/YanYang-G0001/NetworkScience_Group15/blob/main/README.md)

This project investigates the structural and robustness properties of package dependency networks in **R**, **Python**, and **Java**. The analysis is guided by the following research questions:
1. How can the robustness of package dependency networks be quantified?
2. What are the structural characteristics of these networks across languages?
3. How resilient are they to random node failures?

### Methodology

Using datasets from the Colorado Index of Complex Networks (ICON), we construct directed graphs representing package dependencies. Robustness is assessed through:

- **Topological analysis**: Degree distribution, assortativity, and community structure
- **Resilience metrics**: Betweenness centrality, random attack simulations, dynamical importance
- **Proposed metric**: *Network Vulnerability Index (NVI)*, integrating local and global structure to evaluate network fragility

### Key Findings

The three ecosystems exhibit distinct structural features and varying degrees of robustness. Python's network is densely connected, Java shows modularity, and R is relatively sparse but more homogeneous in node roles.

### Contributions

I was responsible for:

- Data preprocessing and transformation
- Structural analysis (degree, assortativity, community detection)
- Robustness simulations and visualization



![Community structure sample](https://raw.githubusercontent.com/YanYang-G0001/github.io/master/img/community_structure_sample.png)
