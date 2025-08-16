# 🐝 Insect Population Forecasting & Classification

Prevedere e comprendere le popolazioni di insetti è un compito di primaria importanza. In ambito agricolo la previsione di parassiti e specie impollinatrici può migliorare la resa, ridurre l’uso di pesticidi e promuovere pratiche sostenibili. L’obiettivo principale di questa iniziativa è sviluppare un modello predittivo in grado di stimare con precisione il numero di insetti, utilizzando dati ambientali giornalieri relativi alla temperatura e all’umidità. 

## 📘 Documentazione Tecnica
- Consulta la [documentazione tecnica](./Documentazione.pdf) per ulteriori dettagli sul funzionamento del progetto.
- Consulta la [documentazione Power BI](./PowerBI.pdf) per approfondimenti sull'analisi dei dati e visualizzazioni.

---

## 🎯 Obiettivi

Il progetto si articola in **due task principali**:

1. [Regression Task](./Regressione-Cicalino.ipynb)
   - Prevedere il **numero totale di insetti catturati** in un determinato periodo.  
   - Dataset utilizzato: **Cicalino**  
   - Output: una **stima quantitativa** utile per analisi approfondite e pianificazione di interventi agricoli.

2. [Classification Task](./Classificazione-Imola.ipynb)
   - Identificare la **presenza di nuove catture** in un determinato periodo (variabile binaria: 1 = nuove catture, 0 = nessuna cattura).  
   - Dataset utilizzato: **Imola**  
   - Output: supporto per il **monitoraggio delle dinamiche di cattura** e l’individuazione di condizioni favorevoli/sfavorevoli.

---

## 🔄 Workflow del Progetto

Il lavoro è stato suddiviso nelle seguenti fasi principali:

1. **Data Loading and Inspection**  
   - Caricamento e analisi preliminare dei dati da file Excel.  
   - Identificazione di differenze temporali e disomogeneità tra dataset.  

2. **Exploratory Data Analysis (EDA)**  
   - **In Python**: utilizzo di librerie come *pandas, matplotlib, seaborn* per statistiche descrittive e visualizzazioni.  
   - **In Power BI**: analisi esplorativa dei dati tramite grafici e report interattivi, con l’obiettivo di individuare pattern, correlazioni e differenze tra variabili.

3. **Model Training**  
   - Utilizzo di **Modelli statistici** (ARIMAX)
   - Utilizzo di **Machine Learning Models** (Gradient Boosting e Random Forest)
   - Utilizzo di **Deep Learning Models** (Multi-Layer Perceptron)

4. **Results Visualization**  
   - Creazione di una **dashboard interattiva** con **Streamlit** per la consultazione dei risultati.  
---

## 🛠️ Tecnologie e Strumenti Utilizzati

- **Python** (pandas, scikit-learn, matplotlib, seaborn, TensorFlow/PyTorch per MLP)  
- **Google Colab** → per addestramento e sperimentazione con GPU  
- **Streamlit** → per dashboard interattiva dei risultati  
- **Power BI** → per EDA avanzata e visualizzazioni interattive  

---

## 👥 Contributors

- [@Vincenzo D'Angelo](https://github.com/vincenzodan)
- [@Giorgio Di Costanzo](https://github.com/GiorgioDiCostanzo)
