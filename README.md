# NLP-basierte Analyse von Bürgerbeschwerden (IU Portfolio)

Dieses Repository enthält die praktische Umsetzung der Erarbeitungs- und Reflexionsphase (Phase 2) für das Modul **Projekt: Data Analysis** an der IU Internationalen Hochschule.

## Projektübersicht
Im Rahmen dieses Projekts wird eine NLP-Pipeline in Python implementiert, um unstrukturierte Textdaten (Beschwerden) systematisch zu analysieren. Ziel ist es, mithilfe von Machine-Learning- und Natural-Language-Processing-Techniken die am häufigsten diskutierten Themen automatisiert zu extrahieren, um Entscheidungsträgern in einer Kommune eine datenbasierte Handlungsgrundlage zu bieten.

## Features & Pipeline
Die Implementierung umfasst folgende Schritte:
1. **Datenvorverarbeitung (Preprocessing):** Bereinigung der Texte (Sonderzeichen/Zahlen), Lowercasing, Stoppwort-Filterung und Lemmatisierung unter Verwendung von `nltk` und `spacy`.
2. **Text-Vektorisierung:** Vergleich von zwei numerischen Ansätzen (`CountVectorizer` und `TfidfVectorizer`).
3. **Themenextraktion (Topic Modeling):** Anwendung und Vergleich von zwei semantischen Analysetechniken (`Latent Dirichlet Allocation (LDA)` und `Non-Negative Matrix Factorization (NMF)`).

## Repository-Struktur
* `nlp_analysis.ipynb` - Das Haupt-Jupyter-Notebook mit der gesamten Pipeline und Datenanalyse.
* `requirements.txt` - Liste aller benötigten Python-Bibliotheken zur einfachen Reproduktion der Umgebung.
* `data/` - Ordner für den verwendeten (Beispiel-)Datensatz.

## Installation & Ausführung

Folge diesen vier einfachen Schritten, um die Entwicklungsumgebung lokal einzurichten und das Jupyter Notebook auszuführen:

### 1. Repository klonen
Öffne dein Terminal oder die Eingabeaufforderung und klone das Projekt mit folgendem Befehl:
```bash
git clone [https://github.com/MrSebas3/IU-Data-Analysis-Portfolio](https://github.com/MrSebas3/IU-Data-Analysis-Portfolio)
cd IU-Data-Analysis-Portfolio
```

### 2. Virtuelle Umgebung einrichten & aktivieren

Es wird empfohlen, eine virtuelle Umgebung (venv) zu erstellen, um Konflikte mit anderen Python-Paketen zu vermeiden:
Windows:
```bash
python -m venv venv
.\venv\Scripts\activate
```
MAC
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Abhängigkeiten installieren

Installiere alle für dieses Projekt benötigten Bibliotheken automatisiert über die bereitgestellte requirements.txt:
````bash
pip install -r requirements.txt
````

### 4. Jupyter Notebook starten

Starte die interaktive Entwicklungsumgebung. Dein Standard-Webbrowser sollte sich automatisch mit dem Dashboard öffnen:
````bash
jupyter notebook
````
