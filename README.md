# CMS Schnellzugriff

Hier kommst du schnell zu allen wichtigen Dateien, um sie sofort zu bearbeiten:

- [Hintergrundinformationen (Titel, SEO, Email-Adresse, Telefonnummer, logo)](_config.yml)
- [Angebote](_angebote/)
- Abschnitte der Titelseite:
  - [Über mich](_seitenabschnitte/uebermich.md)
  - [Referenzen](_seitenabschnitte/referenzen.md)
  - [Newsletter-Bereich und Kontaktformular](_seitenabschnitte/kontakt.md)

# So geht's

Bevor du irgendwas machst, scroll hoch und stell sicher, dass rechts mitte oben in der Box neben `Branch` nicht "master" sondern "gh-pages" steht. Du kannst dort draufklicken und dann auf "gh-pages". Nur Änderungen, die du machst, während links oben "gh-pages" steht, werden auch live auf der Webseite zu sehen sein.

Die wichtigen Elemente der Seite sind Variablen zugewiesen, um die Inhalte leicht bearbeitbar zu machen.

Die Inhalte sind in zwei "Sprachen" formatiert:

- [Markdown Format](http://assemble.io/docs/Cheatsheet-Markdown.html)
Das ist eine Sprache zur einfachen Formatierung deiner Texte. Diese README Datei ist z.B. in Markdown formatiert. Schau dir die [Rohform hier](https://raw.githubusercontent.com/jimbroski/boogyspenden/master/README.md) an, um herauszufinden, wie das geht.

- [YAML](http://statamic.com/learn/configuring/using-yaml)
Zu Beginn jeder Markdown Datei ist ein Bereich mit `---` eingerahmt. Innerhalb dieses Bereiches wird die Sprache [YAML](http://statamic.com/learn/configuring/using-yaml) verwendet, um Variablen zu definieren. Es gibt auch Dateien, die nur im YAML Format sind. Die enden dann auf .yml
Meistens kannst du im YAML-Bereich auch einfaches HTML verwenden. Allerdings solltest du damit sehr vorsichtig sein und es erst ausprobieren oder nachfragen. Zum Beispiel kannst du `<br>` jederzeit einfügen, um einen Absatz zu machen. Im Markdown brauchst du übrigens genau dieses HTML Zeug nicht.

Um Dateien zu bearbeiten, klicke zunächst oben im Schnellzugriff auf die Datei, die du verändern möchtest und anschließend rechts oebn auf das Stiftsymbol. Nun kannst du die Datei bearbeiten.
Wenn du fertig bist gib unten unter "Commit changes" im oberen Textfeld ein, was du gemacht hast. Etwas kurzes wie "Fehler behoben" reicht vollkommen. Dann klick unten auf "Commit changes".

>_Achtung!_
>Nur, was du im "branch" "gh-pages" bearbeitest, erscheint auch live auf der Webseite.

## Hintergrundinformationen in der config.yml

In der `_config.yml` definierst du einige grundsätzlichen Informationen deiner Webseite, die auch auf der Titelseite angezeigt werden. Wichtig zu definieren sind vor allem:

- title: (Erscheint oben im Browser)
- email: (Rechts oben auf der Titelseite)
- telefonnummer: (Rechts oben auf der Titelseite)
- logo: (Links oben auf der Titelseite)
- description: (Wird in der Google Suche unter deinem Seitenlink angezeigt)

**Wichtig**: Hinter `description` ist ein `|`. In der Zeile sollte auch nichts anderes sein. Der Inhalt steht in den Zeilen darunter. Jede Zeile **muss** exakt Leerzeichen eingerückt sein. Das ist von YAML so vorgegeben.

### Bilder Hochladen

Bilder direkt hochladen kann momentan nur ich. Du musst sie mir also als Email schicken und ich speichere sie dann in `assets/img/`. Alternativ kannst du sie selbst irgendwo hochladen (z.B. Dropbox) und den Link jeweils einfügen (z.B. beim Logo)

## Angebote

Die verschiedenen Angebote sind im Ordner `_angebote` in verschiedenen Dateien gespeichert. Du kannst die Dateien umbenennen, löschen oder neue hinzufügen. Halte dich aber unbedingt an das Format der existierenden Dateien. Außerdem sollten es (im aktuellen Setup) nur exakt 4 Angebote sein. Das können wir aber bei Bedarf noch einmal anders gestalten.

### icon:

Für die icons kannst du dir [HIER](http://fortawesome.github.io/Font-Awesome/icons/) eins aussuchen und anklicken. Dort siehst du dann einen icon-code, der so etwa aussieht: `fa-paper-plane`. Diesen kannst du dann einfach einfügen. **Achte aber darauf**, dass du vorher ein `fa ` hinzufügst, wenn du ein Icon von der Seite wählst. Das würde dann zum Beispiel so aussehen:

```
icon: fa fa-paper-plane
```

### karussell_bild:

  - Die Bilder sollten einheitlich im JPG format sein
  - Die Bilder sollten die selben Dimensionen haben: 1920 × 662
  - Die Bilder sollten am besten mit einem Image Optimizer möglichst klein gemacht werden.

### 'Call To Action':

  - cta = Call to Action
  - der cta_link wird im Karussell sowie in der Box darunter verwendet
  - Externe links müssen immer mit http:// oder https:// beginnen
  - Interne links zu anderen Seiten beginnen mit /
  - Links zu Abschnitten auf der Titelseite beginnen mit # und müssen in Anführungszeichen sein


## Seitenabschnitte

Die Seitenabschnitte haben IDs und eine Reihenfolge. Beide sind wichtig für die Navigation und die Verlinkungen und sollten (erstmal) nicht geändert werden.
