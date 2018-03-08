# Anleitung

## Mkdocs

### Bild einfügen
Das Bild muss im Ordner 'img' abgelegt werden.
Die Verlinkung erfolgt dann mit:

    ![Screenshot](/img/module.png)
    *Abb.: Übersicht Module*

### Neue Seite erstellen

Um eine neue Seite zu erstellen im Terminal folgenden Befehl eingeben:

    curl 'https://jaspervdj.be/lorem-markdownum/markdown.txt' > docs/about.md

Anschliessend im File *mkdocs.yml* die Seite verlinken:

    site_name: MkLorum
    pages:
      - Home: index.md
      - About: about.md

### Preview auf localhost starten

Im Terminal ins entsprechende Verzeichnis wechseln (dort wo das mkdocs.yml File liegt)
Anschlissend den Server starten:

	mkdocs serve

### Deployen auf github

    mkdocs gh-deploy

Achtung: nicht manuell d.h. mit *git add* deployen!



## Tools, die wir verwenden
* Time Tracking: [Toggl](https://toggl.com/app/team/2386768)
* Reports: Mkdocs (Markdown) / Git Pages
* Schlussbericht: LaTeX
* Versionisierung: [Git](https://github.com/LB-NTB/wetterArbon)
* Item Tracking: [Trello](https://trello.com/b/5cGzdFWq/bachelor-arbeit)
* Kommunikation: slack
* Screen-Sharing und Telefonie: skype

