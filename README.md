# Lernmodul Datenbankenzugriff mit Python

In diesem Modul lernen Sie wie Sie mit Python Database API (PEP 249) auf eine Datenbank Zugreiffen und SQL-Abfragen ausführen. Sowohl das Abfragen von Daten (SELECT) als auch die Manipulation wird erklärt. Als Beispiel DBMS wird SQLite verwendet. Vorraussetzungen für die Nutzung sind Grundkenntnisse in Python und SQL. Die Dauer der Bearbeitung beträgt 15 bis 20 Minuten.

## Start mit Binder 

Mit Hilfe des Binder-Services kann das Modul ohne Installation dierekt im Browser benutzt werden.

Starten: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/EILD-nrw/lm-database-with-python/HEAD?urlpath=notebooks%2FDatenbankzugriff.ipynb) Das Modul lädt etwas 3 Minuten!

## Start mit Docker

Mithilfe der folgenden Befehle kann das Lernmodul auch lokal in einem Docker Container gestartet werden:

```
git clone https://github.com/EILD-nrw/lm-database-with-python.git  && cd lm-database-with-python
docker build -t lmdbaccess:1.0 .
docker run -p 8888:8888 lmdbaccess:1.0
```
Die URL zum Aufrufen des Jupyter-Notebooks wird in der Konsole angezeigt und das Modul kann im Browser verwendet werden.
