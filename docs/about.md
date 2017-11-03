# Anleitung

## Mkdocs
### Neue Seite erstellen

Um eine neue Seite zu erstellen im Terminal folgenden Befehl eingeben:

    curl 'https://jaspervdj.be/lorem-markdownum/markdown.txt' > docs/about.md

Anschliessend im File *mkdocs.yml* die Seite verlinken:

    site_name: MkLorum
    pages:
      - Home: index.md
      - About: about.md

### Mkdocs starten

Im Terminal ins entsprechende Verzeichnis wechseln (dort wo das mkdocs.yml File liegt)
Anschlissend den Server starten:

	mkdocs serve



## Tools
* Time Tracking: Toggl 'https://toggl.com'
* Reports: Mkdocs (Markdown) / Git Pages
* Schlussbericht: LaTeX
* Versionisierung: Git
* Item Tracking: Trello

