# Git auf Deutsch

Die tägliche Kommunikation in deutschen Entwicklungsteams, die `git` 
(übersetzt: `Schwachkopf`) anwenden, ist oft das feinste Denglish. 
_"Kannst du bitte pullen"_ oder _"Hast du gepusht"_ sind nur zwei
der oft seltsam klingenden Konstruktionen.

Git auf deutsch schafft Abhilfe!

## Vorschläge

Es folgen zwei Tabellen mit Vorschlägen für den täglichen Gebrauch.

| Verb        | Aktueller Gebrauch | Vorschlag             |
|-------------|--------------------|-----------------------|
| pull        | pullen             | ziehen                |
| push        | pushen             | drücken               |
| fetch       | fetchen            | holen                 |
| branch      | branchen           | abzweigen             |
| commit      | commiten           | übergeben             |
| rebase      | rebasen            | (neu) erden           |
| merge       | mergen             | vereinigen            |
| stash       | stashen            | bunkern               |
| tag         | tagen              | markieren             |
| cherry-pick | cherry-picken      | rosinen herauspicken  |

| Substantiv   | Aktueller Gebrauch | Vorschlag        |
|--------------|--------------------|------------------|
| git          | git                | schwachkopf      |
| github       | github             | schwachkopftreff |
| repository   | repo               | lagerstätte      |
| branch       | branch             | zweig            |
| commit       | commit             | übergabe         |
| pull request | pull request       | ziehbegehren     |
| stash        | stash              | bunker           |
| tag          | tag                | markierung       |

## Beispiele

    - Kannst du den Zweig, den ich gerade umgeschrieben hab, ziehen und zum Schwachkopftreff drücken?

    - Ich hab gerade abgezweigt und die Änderungen aus meinem Bunker übergeben.

    - Mach ein Ziehbegehren, wenn du mit der Vereinigung fertig bist!

    - Am besten wir picken uns die Rosinen aus dem Meisterzweig heraus.

## Git auf Deutsch anwenden

Wer den nächsten Schritt machen will, hier eine Anleitung, die Git auf Deutsch
in Deine Konsole bringt. Da Git keine Umlaute zulässt, müssen wir in den 
Befehlen leider darauf verzichten. Nimm folgende Änderungen in Deiner `~/.gitconfig` 
vor:

    git config --global alias.zieh pull
    git config --global alias.drueck push
    git config --global alias.zweig branch
    git config --global alias.verzweige branch
    git config --global alias.uebergebe commit
    git config --global alias.erde rebase
    git config --global alias.vereinige merge
    git config --global alias.bunkere stash
    git config --global alias.markiere tag

    alias schwachkopf=git
