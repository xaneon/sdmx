{{cookiecutter.project_slug}}
==============================

{{cookiecutter.project_short_description}}

Project Organization
--------------------
.
├── AUTHORS.md 		 				<-- Information zu den Authoren 
├── bin 						<-- Executables, exe-Dateien oder RUN
├── config 						<-- Alle Konfigurationsdateien, auch für beispielsweise Dokumentation
├── data 						<-- Alle verwendeten Daten (je nach Größe nicht unbedingt getrackt mit Git)
│   ├── external 					<-- Alle externen Datenquellen
│   ├── interim 					<-- Zwischenergebnisse 
│   ├── processed 					<-- die endgültigen (vorverarbeiteten) Daten, die man z.B. zum Trainieren des Modells verwendet
│   └── raw 						<-- Rohdaten (unveränderbar)
├── docs 						<-- Dokumentationsordner (z.B. automatisiert erstellt mit doxygen oder sphinx)
├── LICENSE 						<-- Standardlizenz
├── notebooks 						<-- R, Python, Jupyter oder Zeppelin Notebooks
├── README.md 						<-- Projektbeschreibung als *Markdown*
├── reports 						<-- Projektspezifische Berichte / Veröffentlichungen
│   └── figures 					<-- Abbildungen für die Berichte
└── src 						<-- Quellcode
    ├── data 						<-- Skripte zur Manipulation von Daten
    ├── external 					<-- Externe Skripte z.B. geclonte Git Repositories
    ├── models 						<-- Implementation von Modellen
    ├── testing 					<-- Skripte zum automatisierten Testen 
    ├── tools 						<-- Skripte, Module und Bibliotheken mit (Hilfs-) Funktionen
    └── visualization 					<-- Skripte zur Visualisierung