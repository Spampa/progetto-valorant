# 📊 Valorant - Progetto Statistica

Analisi statistica e visualizzazione dei dati relativi a Valorant. Questo progetto processa e analizza dataset di partite e statistiche di gioco per ottenere insights e metriche significative utilizzando Python.

## 📋 Prerequisiti

Prima di iniziare, assicurati di avere installato:
- [Anaconda](https://www.anaconda.com/) o [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
- Git (per clonare la repository)
- Almeno 500MB di spazio libero su disco

## 🚀 Installazione

Segui questi passaggi per configurare l'ambiente di sviluppo locale.

### 1. Clona la repository
Scarica il progetto sul tuo computer:

```bash
git clone [https://github.com/Spampa/Valorant-prohetto-statistica.git](https://github.com/Spampa/Valorant-prohetto-statistica.git)
cd Valorant-prohetto-statistica
````

### 2\. Configura l'ambiente Conda

Il progetto utilizza un ambiente virtuale per gestire le dipendenze (Pandas, NumPy, ecc.) ed evitare conflitti.

Crea l'ambiente usando il file di configurazione incluso:

```bash
conda env create -f environment.yml
```

Questo installerà automaticamente:

  * **Python 3.9**
  * **Pandas** (Analisi dati)
  * **NumPy** (Calcolo numerico)
  * E altre dipendenze necessarie...

### 3\. Attiva l'ambiente

Una volta completata l'installazione, attiva l'ambiente:

```bash
conda activate valorant-progetto_statistica
```

Dovresti vedere `(valorant-progetto_statistica)` apparire all'inizio della tua riga di comando.
  * Assicurati che il file `data/merge_data_valorant.csv` sia presente prima di eseguire lo script.
  * Il progetto è ottimizzato per **Python 3.9**.

<!-- end list -->
