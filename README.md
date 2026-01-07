# Amazon E-commerce Analysis 📊
Analisi completa su 6.355 prodotti Amazon, focalizzata sulla redditività delle categorie e sulla Sentiment Analysis per guidare decisioni di investimento.

## 📂 Tabella dei contenuti
- [Descrizione](#-descrizione)
- [Obiettivi Finali](#-obiettivi-finali)
- [Technical Stack](#-technical-stack)
- [Installazione e Uso](#️-installazione-e-uso)
- [Struttura Dataset](#-struttura-dataset)
- [Pipeline dei dati (ETL)](#-pipeline-dei-dati-etl)
- [Contatti & Link](#-contatti--link)

## 📝 Descrizione
Questo progetto esplora un dataset di oltre 6.000 prodotti con l'obiettivo di identificare:
* **Investimenti sicuri**: Brand e categorie con alto volume di vendite e sentiment positivo.
* **Zone di rischio**: Segmenti di mercato con recensioni negative dove il capitale è a rischio.

## 🎯 Obiettivi Finali
* **Brand Insights**: Identificare dove investire (Sentiment +) e dove evitare (Sentiment -).
* **Performance Categorie**: Calcolo del fatturato totale e popolarità per categoria.
* **Product Analysis**: Analisi dei prodotti leader e degli "outlier" negativi.

## 🛠 Technical Stack

Il progetto utilizza le versioni più recenti delle librerie core per la Data Science (aggiornate al 2026) per garantire performance e stabilità.

*   **Linguaggi:** 
    *   Python 3.12+
    *   SQL (MariaDB / MySQL)
*   **Gestione Database:** [phpMyAdmin](https://www.phpmyadmin.net) (per lo storage iniziale, la pulizia e l'export dei dati).
*   **Qualità del Codice:** 
    *   [Ruff](github.com) (Linter & Formatter | standard PEP 8).
*   **Librerie Core:**
    *   `pandas` (v2.3.3) [[Doc](pandas.pydata.org)] — Manipolazione e analisi dei dati.
    *   `numpy` (v2.3.5) [[Doc](numpy.org)] — Calcoli numerici.
    *   `matplotlib` (v3.10.7) & `seaborn` (v0.13.2) — Data Visualization.
*   **Reporting:** Jupyter Notebook (v7.x)

## ⚙️ Installazione e Uso
1. **Prerequisiti:** Assicurati di avere Python 3.12+ installato.
2. **Clona la repository:**
   ```bash
   git clone https://github.com/annarudych/project_amazon.git
   cd project_amazon
3. **Installa le dipendenze**:
   ```bash
   pip install -r requirements.txt

## 📂 Struttura Dataset
**File**: [products_with_reviews_clean.csv](./products_with_reviews_clean.csv)
**Dimensioni**: 12MB | 6,355 righe × 35 colonne

## 💾 Pipeline dei dati (ETL)
1. **Storage**: I dati grezzi sono stati strutturati in un database MariaDB.
2. **SQL Querying**: I dati sono stati filtrati e aggregati tramite query SQL via phpMyAdmin.
 * *Database Schema*: Il file SQL per ricreare la struttura del database è disponibile nella cartella principale [amazon.sql](./amazon.sql).
3. **Data Extraction:** Esportazione dei dati ottimizzati in formato CSV per l'analisi avanzata in Python.
4. **Analisi Python**: Pulizia finale in Python, sentiment analysis e visualizzazione finale.


## 👥 Contatti & Link
- **Data Analyst:** Anna Rudych
- **Email:** [annarudychw@gmail.com](mailto:annarudychw@gmail.com)
- **LinkedIn:** [Anna Rudych](https://www.linkedin.com/in/annarudych/)
- **GitHub:** [@annarudych](https://github.com/annarudych)
