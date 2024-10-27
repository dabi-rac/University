# Guida Passo-Passo per Impostare Jupyter Notebooks in Visual Studio Code e utilizzare i file del prof. Vellucci🐍💻

## 1. Installa Python
Se non hai già installato Python, segui questi passaggi:
- Scarica l'ultima versione di Python dal [sito ufficiale di Python](https://www.python.org/).
- **Importante:** Durante l'installazione, spunta la casella **"Add Python to PATH"** (Aggiungi Python al PATH). Questo è essenziale affinché VS Code riconosca Python.

## 2. Installa Visual Studio Code (VS Code)
- Visual Studio e' un text editor che permette di avere feature avanzate.
- Scarica e installa VS Code dal [sito ufficiale di VS Code](https://code.visualstudio.com/).
- Una volta installato, apri VS Code.

## 3. Installa l'Estensione Python in VS Code
Per lavorare con Python e Jupyter Notebooks in VS Code, devi installare l'estensione ufficiale per Python:
- Apri VS Code.
- Vai alla scheda **Estensioni** cliccando sull'icona delle Estensioni nella barra laterale (oppure premi `Ctrl+Shift+X`).
- Nel campo di ricerca, digita **"Python"**.
- Trova l'estensione chiamata **"Python"** (pubblicata da Microsoft) e clicca su **Installa**.

## 4. Installa l'Estensione Jupyter in VS Code
Nella scheda delle Estensioni (premi `Ctrl+Shift+X`), cerca **Jupyter**:
- Trova l'estensione chiamata **"Jupyter"** (pubblicata da Microsoft) e clicca su **Installa**. 
- Questa estensione ti permetterà di aprire ed eseguire Jupyter Notebooks direttamente in VS Code.

## 5. Creare un Ambiente Virtuale Python 🌱
Per gestire meglio le dipendenze e mantenere l'isolamento tra i vari progetti, è consigliato creare un ambiente virtuale per Python:
- **Apri un terminale in VS Code:** Vai su **Visualizza -> Terminale** o premi ``Ctrl + ` ``.
- **Crea un ambiente virtuale:** Esegui il seguente comando per creare un ambiente virtuale chiamato `venv`:

    ```bash
    python -m venv venv
    ```

- **Attiva l'ambiente virtuale:**
  - Su Windows, esegui:

    ```bash
    venv\Scripts\activate
    ```

  - Su macOS o Linux, esegui:

    ```bash
    source venv/bin/activate
    ```

- Una volta attivato, noterai che il prompt del terminale cambierà, mostrando il nome dell'ambiente `(venv)`, il che significa che l'ambiente virtuale è attivo.

## 6. Installa le librerie richieste 📦
Con l'ambiente virtuale attivato, installa le librerie necessarie per il tuo notebook (come numpy e plotly) eseguendo questi comandi:

```bash
pip install numpy
pip install plotly
```

## 7. Fatto! 
Ora puoi aprire, modificare e runnare questi file e visualizzare grafici all'interno di visual studio!
Se hai bisogno di aiuto o la guida non ti risulta chiara, cercami a lezione o scrivimi su l'email di istituto! 
