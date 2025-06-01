# Graph-Based ANNS Indexes of High-Dimensional Vectors (COMP5311 Project)

This repository contains the survey paper titled "Graph-Based ANNS Indexes of High-Dimensional Vectors," completed for the **COMP5311 Database Architecture and Implementation** course at the Hong Kong University of Science and Technology (HKUST) during the 2024-2025 Spring semester. 

The objective was to investigate an advanced topic in data management through the study of research papers, develop a deep understanding of the chosen topic, and present the findings in a survey report and presentation.

## Authors

* Elton Chun-Chai Li
* Jimmy Kwun-Hang Lau
* Zhaoteng YE
* Sirui Han
* Jiahao Zhan

## Abstract

Efficient similarity search in high-dimensional data is crucial for numerous applications, driving the development of graph-based Approximate Nearest Neighbor (ANN) search techniques. This survey offers a comprehensive exploration of this prominent field. It begins with the fundamental principles of organizing data points into proximity graphs for efficient neighbor retrieval and then traces the evolution of core graph-based algorithms. The evolution spans from early Navigable Small World (NSW) graphs to advanced hierarchical and refined graph structures like HNSW and NSG. The construction and search mechanisms of these algorithms are examined, analyzing their underlying principles and inherent trade-offs in search accuracy, efficiency, and scalability. Furthermore, the survey investigates the adaptation of graph-based ANN search to multi-modal data, addressing the challenges and solutions for cross-modal similarity search. The problem of query hardness is also addressed, analyzing how query difficulty varies and exploring methods to measure and mitigate its impact on search performance. The survey concludes by outlining open challenges and future research directions in graph-based ANN search.

## Survey Structure

The survey is structured as follows:
1.  **Introduction**: Overview of graph-based ANN search.
2.  **Background**: Essential background on the ANN search problem and evaluation metrics.
3.  **Graph-Based Index ANNS**: Core graph-based ANN algorithms, tracing their evolution from early foundations (like NSW) to modern construction and search techniques (including HNSW, NSG, Vamana/DiskANN), and evaluation frameworks.
4.  **Multi-Modal Graph-Based Index**: Exploration of key extensions enabling multi-modal search and the RoarGraph approach.
5.  **Query Hardness Analysis**: Analysis of the practical challenge of query hardness, common hardness measures, and graph-native measures like Steiner-Hardness.
6.  **Open Challenges and Future Directions**: Synthesis of major open challenges and future research avenues.
7.  **Conclusion**: Summary of the survey.

## Core Algorithms and Concepts Discussed

* Navigable Small World (NSW) graphs
* Hierarchical Navigable Small World (HNSW) graphs
* Navigating Spreading-out Graph (NSG)
* Vamana (DiskANN)
* Proximity Graph Construction Principles
* Core Search Mechanisms (Greedy Search, Beam Search)
* Cross-Modal ANNS and the OOD (Out-of-Distribution) challenge
* RoarGraph for cross-modal search
* Query Hardness Measures (Relative Contrast, LID, Query Expansion, e-Hardness, Steiner-Hardness)

## Files in this Repository

* `COMP5311.pdf`: The full survey report.

---
