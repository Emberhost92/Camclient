<p align="center">
  <img src="docs/assets/camclient-banner.png" alt="Camclient" width="920">
</p>

# Camclient

Tampermonkey-Skript für Chaturbate, von **Emberhost**.

Damit schaust du deine Lieblingsmodels und Streamerinnen auf Chaturbate: live, nackt, beim Ficken oder bei dem, was sie sonst in der Cam machen. Eine allein oder mehrere gleichzeitig. Dazu kommen Funktionen, die die normale Seite so nicht hat. Deine Sammlung bleibt im Browser.

**20.114.0-custom** · [MIT](LICENSE) · **[Installieren](https://raw.githubusercontent.com/Emberhost92/Camclient/main/Camclient.user.js)** · [Änderungen](CHANGELOG.md) · [English](#english)

## Funktionen

- **SingleCam:** eine Streamerin groß, mit Zoom, Ton, Chat, Profil und eigenen Notizen. Screenshots und Aufnahmen landen in ihrer Galerie, lokal bei dir. Bild-im-Bild und Vollbild gehen auch.
- **MultiCam:** mehrere Cams im Raster, oder eine groß und die anderen daneben. Reinziehen, austauschen, mit × aus der Ansicht nehmen. Ton und Qualität pro Fenster. Anzeige, ob in der Cam gerade was zu hören ist, auch bei Stumm. Meldung, wenn eine aus deiner Sammlung online oder offline geht.
- **Entdecken:** öffentliche Räume suchen. Tags mit UND, ODER und Ausschluss, nach Zuschauern filtern, Favoriten und wen du schon gesehen hast. Vorschläge nach dem, was du dir lokal schon angeschaut hast. Den Rest ausblenden.
- **Live-Vorschau:** Auf der Startseite und in den Listen laufen die Karten als Livebild. Maus drauf, dann kommt das Video stumm und etwas größer. Anheften geht auch. Zählt nicht als Sehzeit.
- **Bibliothek:** Favoriten, Gruppen, eigene Tags, Notizen, Cover, gespeicherte Bilder und Clips. Auf der Raumseite ein Dock: aktuelle Streamerin in den Arbeitsbereich, Screenshot, Aufnahme, Bild-im-Bild, Pause, Stumm.
- **Gefolgt:** die Models, denen du auf Chaturbate folgst. Nur die Liste. Das Skript folgt niemandem und entfolgt niemandem.
- **Statistik:** wen du wie lange angeschaut hast, wie oft, welche Tags, zu welcher Uhrzeit. Nur das, was Camclient selbst gesehen hat. Keine Tokens, keine privaten Nachrichten, keine Passwörter.
- **Aussehen und Sicherung:** Farben, Schrift, Dark Mode, Clean-Modus ohne die Buttons. Arbeitsbereiche merken sich Räume und Layout. Einstellungen und Statistik exportieren und wieder reinholen.

## Installieren

<details>
<summary>Erstinstallation und Update</summary>

Du brauchst einen Browser mit [Tampermonkey](https://www.tampermonkey.net/) und Zugang zu Chaturbate. Geprüft wurde mit Brave. Ob jeder Browser mitmacht, ist offen. Du musst volljährig sein. Login, Altersprüfung und Sperren macht Chaturbate, das Skript umgeht die nicht.

1. Tampermonkey von der offiziellen Seite installieren. Wenn Userscripts aus sind, die [Einrichtungshilfe](https://www.tampermonkey.net/faq.php#Q209) nehmen. Chrome-Browser wollen oft **Userscripts zulassen** oder den Entwicklermodus.
2. **[Camclient installieren](https://raw.githubusercontent.com/Emberhost92/Camclient/main/Camclient.user.js)** öffnen und in Tampermonkey bestätigen.
3. Chaturbate neu laden. Dann die [Startseite](https://chaturbate.com/?multicam_discover=1&suite_view=dashboard) oder [MultiCam](https://chaturbate.com/?multicam_mode=1) öffnen.

Siehst du nur JavaScript, im Tampermonkey-Dashboard ein neues Skript anlegen, den kompletten Inhalt von `Camclient.user.js` reinkopieren, speichern, aktivieren, Seite neu laden. Nicht in die Konsole der Website einfügen.

Zum Aktualisieren zuerst exportieren, was du behalten willst. Denselben Installationslink nochmal öffnen und den vorhandenen Eintrag aktualisieren. Im Editor den Inhalt vom bestehenden Skript ersetzen. Keine zweite aktive Kopie, dasselbe Browserprofil. Einen automatischen Update-Kanal gibt es in dieser Version nicht. Skript löschen, Browserdaten leeren oder das Profil wechseln kann die Sammlung treffen.

</details>

## English

Userscript for Chaturbate, by **Emberhost**. Watch your favorite models and female streamers live: naked, fucking, or whatever they are doing on cam. One at a time, or several at once. Extra tools on top. Your collection stays in the browser.

- **SingleCam:** one streamer large, with zoom, sound, chat, profile and your notes. Screenshots and recordings go into her gallery on your machine. Picture-in-picture and fullscreen too.
- **MultiCam:** several cams in a grid, or one large and the others beside her. Drag in, swap, remove from the view with ×. Sound and quality per window. A meter shows when the cam is making noise, even while muted. Alert when someone in your collection goes online or offline.
- **Discover:** search public rooms. Tags with AND, OR and exclude. Filter by viewers, favorites and who you already watched. Suggestions follow what you watched locally. Hide the rest.
- **Live preview:** On the home page and in the lists the cards show the live picture. Hover and the video plays muted, a bit larger. You can pin it. It does not count as watch time.
- **Library:** favorites, groups, your own tags, notes, covers, saved pictures and clips. On the room page a dock adds the current streamer to your workspace and does screenshot, recording, picture-in-picture, pause and mute.
- **Following:** the models you already follow on Chaturbate. The list only. The script does not follow or unfollow anyone.
- **Stats:** who you watched, for how long, how often, which tags, what hour. Only what Camclient itself saw. No tokens, no private messages, no passwords.
- **Look and backup:** colors, fonts, dark mode, clean mode with the buttons gone. Workspaces remember rooms and layout. Export and import settings and stats.

<details>
<summary>Install and update</summary>

You need a browser with [Tampermonkey](https://www.tampermonkey.net/) and access to Chaturbate. Checks were done on Brave. You have to be an adult. Chaturbate does login, age checks and blocks. The script does not bypass them.

1. Install Tampermonkey from its official site. If userscripts are off, use the [setup help](https://www.tampermonkey.net/faq.php#Q209). Chrome-based browsers often need **Allow User Scripts** or Developer Mode.
2. Open **[Install Camclient](https://raw.githubusercontent.com/Emberhost92/Camclient/main/Camclient.user.js)** and confirm it in Tampermonkey.
3. Reload Chaturbate. Then open [Home](https://chaturbate.com/?multicam_discover=1&suite_view=dashboard) or [MultiCam](https://chaturbate.com/?multicam_mode=1).

If you only see JavaScript, create a script in the Tampermonkey dashboard, paste the full `Camclient.user.js`, save, enable it, reload the site. Do not paste it into the website console.

Before an update, export what you want to keep. Open the same install link again and update the existing entry. In the editor, replace that existing script. No second active copy, same browser profile. This version has no separate automatic update feed. Removing the script, clearing browser data or switching profiles can hit the collection.

</details>

## Kurz dazu

- Aufnehmen und Screenshots nur lokal, und nur wenn du das speichern darfst. Manche Streams blockt der Browser.
- Camclient ist kein offizielles Chaturbate-Programm.
- Fehlermeldungen ohne Passwörter, Cookies und ohne deine Sicherungen: [Issues](https://github.com/Emberhost92/Camclient/issues/new/choose).
- [Adult Client](https://github.com/Emberhost92/AdultClient) ist ein anderes Programm für Windows.
- [SHA256SUMS](SHA256SUMS) · [Drittanbieter](THIRD_PARTY_NOTICES.md)
