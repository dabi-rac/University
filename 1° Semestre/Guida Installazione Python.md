Guida Passo-passo per Impostare Jupyter Notebooks in Visual Studio Code
1. Installa Python
Se non hai già installato Python, segui questi passaggi:

Scarica l'ultima versione di Python dal sito ufficiale di Python.
Importante: Durante l'installazione, spunta la casella "Add Python to PATH" (Aggiungi Python al PATH). Questo è essenziale affinché VS Code riconosca Python.
2. Installa Visual Studio Code (VS Code)
Scarica e installa VS Code dal sito ufficiale di VS Code.
Una volta installato, apri VS Code.
3. Installa l'Estensione Python in VS Code
Per lavorare con Python e Jupyter Notebooks in VS Code, devi installare l'estensione ufficiale per Python:

Apri VS Code.
Vai alla scheda Estensioni cliccando sull'icona delle Estensioni nella barra laterale (oppure premi Ctrl+Shift+X).
Nel campo di ricerca, digita "Python".
Trova l'estensione chiamata "Python" (pubblicata da Microsoft) e clicca su Installa.
4. Installa l'Estensione Jupyter in VS Code
Nella scheda delle Estensioni (Ctrl+Shift+X), cerca Jupyter.
Trova l'estensione chiamata "Jupyter" (pubblicata da Microsoft) e clicca su Installa.
Questa estensione ti permetterà di aprire ed eseguire Jupyter Notebooks direttamente in VS Code.

5. Creare un Ambiente Virtuale Python
Per gestire meglio le dipendenze e mantenere l'isolamento tra i vari progetti, è consigliato creare un ambiente virtuale per Python subito dopo aver installato Visual Studio Code.

Apri un terminale in VS Code: Vai su Visualizza -> Terminale o premi `Ctrl + ```.

Crea un ambiente virtuale: Nel terminale, esegui il seguente comando per creare un ambiente virtuale chiamato venv:

bash
Copia codice
python -m venv venv
Attiva l'ambiente virtuale:

Su Windows, esegui:
bash
Copia codice
venv\Scripts\activate
Su macOS o Linux, esegui:
bash
Copia codice
source venv/bin/activate
Una volta attivato, noterai che il prompt del terminale cambierà, mostrando il nome dell'ambiente (venv), il che significa che l'ambiente virtuale è attivo.

Installa le librerie richieste: Con l'ambiente virtuale attivato, installa le librerie necessarie per il tuo notebook (come numpy e plotly) eseguendo questi comandi:

bash
Copia codice
pip install numpy
pip install plotly
Seleziona l'ambiente virtuale in VS Code:

Quando apri un notebook o un file Python in VS Code, assicurati di selezionare il tuo ambiente virtuale come interprete Python. VS Code ti chiederà di selezionare un interprete quando apri il notebook, e potrai scegliere l'ambiente venv.
6. Aprire e Eseguire Jupyter Notebooks in VS Code
Apri il file .ipynb:

In VS Code, vai su File -> Apri File... e seleziona il tuo file Jupyter Notebook (MAT GEN - Limiti.ipynb).
Il file si aprirà in un'interfaccia notebook, simile a quella di JupyterLab.
Seleziona il Kernel Python:

Quando apri il notebook, VS Code ti chiederà di selezionare un interprete Python (cioè, l'ambiente Python o il kernel).
Seleziona l'interprete Python relativo all'ambiente virtuale creato in precedenza (venv).
Esegui le Celle:

Puoi eseguire le celle individualmente cliccando sul pulsante "play" accanto a ciascuna cella o premendo Shift + Enter.
7. Creare o Modificare Script Python in VS Code
Se desideri anche eseguire script Python (ad esempio file .py) oltre ai notebook, segui questi passaggi:

Crea un nuovo file Python:

Vai su File -> Nuovo File, poi salva il file con estensione .py (ad esempio mio_script.py).
Scrivi o incolla il tuo codice Python nel file.

Esegui lo script Python:

In VS Code, puoi eseguire lo script Python direttamente premendo F5 (o cliccando con il tasto destro del mouse e selezionando "Esegui File Python nel Terminale").
Riepilogo dei Comandi
Creare un ambiente virtuale Python:

bash
Copia codice
python -m venv venv
Poi attivarlo:

bash
Copia codice
venv\Scripts\activate  # Windows
source venv/bin/activate  # macOS/Linux
Installare le librerie Python:

bash
Copia codice
pip install numpy plotly