# Social Network Analysis on Harry Potter

This project uses data from the ["Harry Potter Network Analysis"](https://github.com/gauthammk/Harry-Potter-Network-Analysis) dataset to build and analyze a social network based on characters and their relationships in the Harry Potter books. The project explores various metrics and techniques to understand the structure and dynamics of the social graph.

## Project Description
The project focuses on analyzing relationships between characters in the Harry Potter saga. Using data about characters and their relationships, a graph representing the social network was constructed. Various *Social Network Analysis (SNA)* tools and techniques were then applied to study:
- **Centrality**: Measures of degree, closeness, betweenness, and eigenvector centrality.
- **Triads and Cliques**: Identification and analysis of graph substructures.
- **K-core decomposition**: Study of network cohesion.
- **Ego-network**: Analysis of ego-centric networks for main characters.
---
## Dataset
The dataset was extracted from [Harry Potter Network Analysis](https://github.com/gauthammk/Harry-Potter-Network-Analysis) and includes two main files:
- **`characters.csv`**: Contains information about characters, including name and role (protagonist, antagonist, etc.).
- **`relations.csv`**: Contains relationships between characters, with weights representing the importance or frequency of interaction.
---
## Project Objectives
1. **Visualize the social network**: Create a graphical representation of the character network.
2. **Calculate centrality metrics**:
    - **Degree centrality**: To identify the most connected characters.
    - **Closeness centrality**: To identify characters who can easily reach other characters in the network.
    - **Betweenness centrality**: To identify "bridges" or mediators in the network.
    - **Eigenvector centrality**: To identify the most influential characters in the network.
3. **Analyze triads and cliques**: To understand the formation of subgroups.
4. **Study K-core**: To analyze the densest and most cohesive areas of the network.
5. **Ego-network analysis**: To explore local networks around main characters.
