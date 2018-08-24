PROFFIX REST API Extension Visual Studio Project Template
=========================================================
Dieses Template erleichtert den Einstieg in die Programmierung einer verwalteten PROFFIX REST API Erweiterung.

Installation
------------
Die [*PROFFIX REST API Extension.zip*](https://github.com/PROFFIX-NET/RestApiErweiterungenTemplate/raw/master/PROFFIX%20REST%20API%20Extension.zip) muss ins Projekt-Template-Verzeichnis von Visual Studio kopiert werden (z.B. `"%USERPROFILE%\Documents\Visual Studio 2017\Templates\ProjectTemplates\Visual C#"`).

**HINWEIS:** Der tatsächliche Pfad kann im Visual Studio unter `Tools → Options... → Projects and Solutions → Locations → User project templates location` nachgeschlagen oder geändert werden.

Verwendung
----------
Sobald dieses Template installiert wurde, kann im Visual Studio unter `File → New → Project... → Installed → Visual C# → PROFFIX REST API Extension` ein neues Projekt angelegt werden.

Debugging
---------
Um die Aufrufe einer lokal installierten PROFFIX REST API in die lokale Entwicklungsumgebung weiterzuleiten, kann eine nicht verwaltete Erweiterung verwendet werden, welche die Anfragen an *http://localhost:5000* weiterleitet. Eine solche nicht verwaltete Erweiterung befindet sich verwendungsfähig in diesem Repository ([*RestApiDevelopmentExtension.zip*](https://github.com/PROFFIX-NET/RestApiErweiterungenTemplate/raw/master/RestApiDevelopmentExtension.zip)).

Erweiterung erstellen (ZIP-Archiv erstellen)
--------------------------------------------
Die Erweiterung kann im Visual Studio durch einen Klick unter `Build → Publish {ProjektName} → Publish` erstellt werden. Das erstellte Erweiterungsarchiv befindet sich im Projekt-Verzeichnis unter `bin\Release` und kann via PROFFIX REST API Konfiguration installiert werden.
