# CMS Schnellzugriff

Hier kommst du schnell zu allen wichtigen Dateien, um sie sofort zu bearbeiten:

- ...

# So geht's

Wichtige Hintergrund-Infos zur Seite sind in der `_config.yml` Datei.

Die verschiedenen Angebote sind im Ordner `_angebote` in verschiedenen Dateien gespeichert.

Die Dateien sind im [Markdown Format](http://assemble.io/docs/Cheatsheet-Markdown.html). Das ist eine Sprache zur einfachen Formatierung deiner Texte. Diese README Datei ist z.B. in Markdown formatiert. Schau dir die [Rohform hier](https://raw.githubusercontent.com/jimbroski/boogyspenden/master/README.md) an, um herauszufinden, wie

Zu Beginn jeder Markdown Datei ist ein Bereich mit `---` eingerahmt. Innerhalb dieses Bereiches wird die Sprache [YAML](http://statamic.com/learn/configuring/using-yaml) verwendet, um variablen zu definieren. Es gibt auch Dateien, die nur im YAML Format sind. Die enden dann auf .yml

Meistens kannst du im YAML-Bereich auch einfaches HTML verwenden. Allerdings solltest du damit sehr vorsichtig sein und es erst ausprobieren oder nachfragen. Zum Beispiel kannst du `<br>` jederzeit einfügen, um einen Absatz zu machen. Im Markdown brauchst du übrigens genau dieses HTML Zeug nicht.

## Angebote

Wichtige Infos zu den Inhalten der Angebote:

### karussell_bild:

  - In welchem Ordner die Bilder liegen ist egal.
    Allerdings ist der Standardpfad zu bevorzugen: assets/img/
  - Der Pfad ist von der index.html Datei ausgehend.
  - Die Bilder sollten einheitlich im JPG format sein
  - Die Bilder sollten die selben Dimensionen haben: 1920 × 662
  - Die Bilder sollten am besten mit einem Image Optimizer möglichst klein gemacht werden.

### 'Call To Action':

  - cta = Call to Action
  - der cta_link wird im Karussell sowie in der Box darunter verwendet
  - Externe links müssen immer mit http:// oder https:// beginnen
  - Interne links zu anderen Seiten beginnen mit /
  - Links zu Abschnitten auf der Titelseite beginnen mit # und müssen in Anführungszeichen sein


## Seitenabschnitte:

Die Seitenabschnitte haben IDs und eine Reihenfolge. Beide sind wichtig für die Navigation und die Verlinkungen und sollten (erstmal) nicht geändert werden.
