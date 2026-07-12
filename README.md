# NLP-basierte Analyse von Bürgerbeschwerden (IU Portfolio)

Dieses Repository enthält die praktische Umsetzung der Erarbeitungs- und Reflexionsphase (Phase 2) für das Modul **Projekt: Data Analysis (DLBDSEDA02_D)** an der IU Internationalen Hochschule.

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

1. **Repository klonen:**
   ```bash
   git clone [https://github.com/DEIN-BENUTZERNAME/DEIN-REPO-NAME.git](https://github.com/DEIN-BENUTZERNAME/DEIN-REPO-NAME.git)
   cd DEIN-REPO-NAME
