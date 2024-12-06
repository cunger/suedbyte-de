
## Setup
 
1. [NodeJS installieren](https://nodejs.org/en/download/prebuilt-installer).
2. Dieses Repository [runterladen](https://github.com/cunger/suedbyte-de/archive/refs/heads/main.zip) und entpacken.
3. In einem Terminal oder der PowerShell in dem `suedbyte-de`-Ordner gehen und `npm i` ausführen.

## Ändern und Bauen

Die HTML-Datei `index.html` ist die Webseite. Das Styling funktioniert über Klassennamen, z.B. [`text-6xl` für die Textgröße](https://v1.tailwindcss.com/docs/font-size). Diese Klassennamen sind von Tailwind definiert und wir können alles verwenden, was in der Tailwind-Dokumentation angegeben wird.

Immer wenn wir neue Klassennamen hinzufügen, müssen wir die CSS-Datei neu bauen. Die wird von Tailwind automatisch generiert.
Dazu in einem Terminal oder der PowerShell `npm run build` ausführen.
Das baut die Datei `styles.css`.

## Hochladen

Am Ende müssen folgende Dateien und Ordner auf den Webserver hochgeladen werden:

* `index.html`
* `styles.css`
* `fonts`
* `images`

