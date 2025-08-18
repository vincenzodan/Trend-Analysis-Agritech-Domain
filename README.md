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

<table>
  <tr>
    <td align="center">
      <a href="https://www.python.org/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="50" height="50" style="vertical-align: middle;"/><br>
        Python
      </a>
    </td>
    <td align="center">
      <a href="https://pandas.pydata.org/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" width="50" height="50" style="vertical-align: middle;"/><br>
        Pandas
      </a>
    </td>
    <td align="center">
      <a href="https://scikit-learn.org/" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/scikitlearn/scikitlearn-original.svg" width="50" height="50" style="vertical-align: middle;"/><br>
        scikit-learn
      </a>
    </td>
    <td align="center">
      <a href="https://matplotlib.org/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg" width="50" height="50" style="vertical-align: middle;"/><br>
        Matplotlib
      </a>
    </td>
    <td align="center">
      <a href="https://colab.research.google.com/" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/googlecolab/googlecolab-original.svg" width="50" height="50" style="vertical-align: middle;"/><br>
        Google Colab
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://streamlit.io/" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/streamlit/streamlit-original.svg" width="50" height="50" style="vertical-align: middle;"/><br>
        Streamlit
      </a>
    </td>
    <td align="center">
      <a href="https://powerbi.microsoft.com/" target="_blank">
        <img width="50" height="50" alt="New_Power_BI_Logo" src="https://github.com/user-attachments/assets/4a645611-aa6a-441c-9b3a-6ec848aa7afd" style="vertical-align: middle;"/><br>
        Power BI
      </a>
    </td>
    <td align="center">
      <a href="https://seaborn.pydata.org/" target="_blank">
        <img width="50" height="50" alt="Seaborn_Logo" src="https://github.com/user-attachments/assets/1be9f727-13ea-4ef0-b560-6363da8890e0" style="vertical-align: middle;"/><br>
        Seaborn
      </a>
    </td>
    <td align="center">
      <a href="https://www.tensorflow.org/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" width="50" height="50" style="vertical-align: middle;"/><br>
        TensorFlow
      </a>
    </td>
    <td align="center">
      <a href="https://pytorch.org/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" width="50" height="50" style="vertical-align: middle;"/><br>
        PyTorch
      </a>
    </td>
  </tr>
</table>



---

## 👥 Contributors

- [@Vincenzo D'Angelo](https://github.com/vincenzodan)
- [@Giorgio Di Costanzo](https://github.com/GiorgioDiCostanzo)
