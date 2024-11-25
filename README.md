# Social Network Analysis su Harry Potter

Questo progetto utilizza i dati del dataset ["Harry Potter Network Analysis"](https://github.com/gauthammk/Harry-Potter-Network-Analysis) per costruire e analizzare una rete sociale basata sui personaggi e le loro relazioni nei libri di Harry Potter. Il progetto esplora diverse metriche e tecniche per comprendere la struttura e la dinamica del grafo sociale.

---

## Descrizione del progetto

Il progetto si concentra sull'analisi delle relazioni tra i personaggi della saga di Harry Potter. Utilizzando i dati sui personaggi e sulle loro relazioni, è stato costruito un grafo che rappresenta la rete sociale. Sono stati poi applicati vari strumenti e tecniche di *Social Network Analysis (SNA)* per studiare:

- **Centralità**: Misure di degree, closeness, betweenness, ed eigenvector centrality.
- **Triadi e Clique**: Identificazione e analisi delle sottostrutture del grafo.
- **K-core decomposition**: Studio della coesione della rete.
- **Ego-network**: Analisi delle reti ego-centriche per i personaggi principali.

---

## Dataset

Il dataset è stato estratto da [Harry Potter Network Analysis](https://github.com/gauthammk/Harry-Potter-Network-Analysis) e include due file principali:

- **`characters.csv`**: Contiene informazioni sui personaggi, inclusi il nome e il ruolo (protagonista, antagonista, ecc.).
- **`relations.csv`**: Contiene le relazioni tra i personaggi, con peso che rappresenta l'importanza o la frequenza dell'interazione.

---

## Obiettivi del progetto

1. **Visualizzare la rete sociale**: Creare una rappresentazione grafica della rete dei personaggi.
2. **Calcolare metriche di centralità**:
    - **Degree centrality**: Per identificare i personaggi più connessi.
    - **Closeness centrality**: Per individuare i personaggi che possono raggiungere facilmente altri personaggi nella rete.
    - **Betweenness centrality**: Per identificare i "ponti" o mediatori nella rete.
    - **Eigenvector centrality**: Per individuare i personaggi più influenti nella rete.
3. **Analizzare triadi e clique**: Per comprendere la formazione di sottogruppi.
4. **Studiare il K-core**: Per analizzare le aree più dense e coese della rete.
5. **Ego-network analysis**: Per esplorare le reti locali intorno ai personaggi principali.
