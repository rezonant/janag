# NameGenerator
----------------------------
_(English)_

Namegenerator creates random names based on settings defined in three files (see below). These files can be customized with any text editor (e.g. Notepad++). 

## Data Files

The text files can be found in the installation file path (Windows "C:\Program Files\NameGenerator"):

### `init.txt`
This file is loaded on startup and sets the semantics and languages file. Within the program you can define which init file you want to use. Select "Init-File..." from the menu.

### `languages.txt`
This file defines the language data. A group is defined by a title surrounded by square brackets ([]), followed by lines of blocks. Empty lines are ignored, as are comment lines starting with ##.

### `semantics.txt`
Semantic rules for different "cultures" are included in this file. The exact rules can be found in the comment section of the file. Comment and empty lines behave like in languages.txt.

## Contact and enhance language files
-----------------------------------
Download of JaNaG Name Generator on http://www.beimax.de
I am happy to add to the files. Just send me a note, so I can add it to the "official" list.


## Command line and server modes
------------------------------
JaNaG support multiple modes:
-  GUI mode (Desktop)
-  Server mode (to be queried using tcp, default port is 12022)
-  HTTP server mode (JSON, default port is 12023)
-  Command line mode (client or local)
-  Applet (kind of old fashioned...)

## Compile
--------
Compile using ant. Select the right build file like this:

```
$ ant -f JaNaG_CML.xml
```



# NameGenerator
----------------------------
_(Deutsch)_

Namegenerator erzeugt zufällige Namen nach bestimmten Einstellungen, die in drei Textdateien festgelegt sind. Diese Dateien kann man ganz einfach mit einem Texteditor (z.B. Notepad++) bearbeiten und für seinen eigenen Wünschen anpassen. 

## Datei

Die drei Textdateien liegen im Installationsverzeichnis (Voreingestellt "C:\Programme\NameGenerator"):

### `init.txt`

Diese Datei wird beim Laden gelesen und gibt die dazugehörigen Semantik- und Sprachdateien an. Man kann im Programm zwischen den init-Dateien wechseln, indem man im Menü den Punkt "Init-Datei..." wählt und die entsprechende Datei aussucht.

### `languages.txt`

In dieser Datei stehen die Sprachdaten. Eine Gruppe wird durch eckige Klammern ([]) definiert, die nachfolgenden Zeilen enthalten jeweils die einzelnen Blöcke. Leere Zeilen werden ignoriert, ebenso Kommentarzeilen, die mit ## anfangen.

### `semantics.txt`

Diese Datei enthält die Wortbildungsregeln für die verschiedenen Kulturen. Die genauen Regeln werden in der Datei erklärt. Auch hier werden leere und Kommentarzeilen ignoriert.

## Kontakt und Sprachdateien einschicken
--------------------------------------

Download des NameGenerators unter http://www.beimax.de
Falls Ihr selbst eigene Dateien erstellt habt, dann würde ich mich freuen, wenn ihr diese an mich schicken könntet. Gegebenenfalls werde ich diese in die offizielle Sprachdatei übernehmen.

Viel Spaß beim ausprobieren!
-- Max Kalus, Autor.
