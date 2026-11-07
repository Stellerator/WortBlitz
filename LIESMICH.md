# WortBlitz

Buchstaben-Lern-App fürs iPad (Förderunterricht, 1./2. Klasse). Läuft komplett im Browser, ohne Internetverbindung nach dem ersten Laden.

## Auf GitHub veröffentlichen (einmalig)

1. Auf github.com ein neues Repository anlegen, z. B. `wortblitz`, Sichtbarkeit **Public**
   (GitHub Pages ist im kostenlosen Konto nur für öffentliche Repos verfügbar).
2. Im Repository **Add file → Upload files** wählen und **alle Dateien aus dieser ZIP** hineinziehen
   (`index.html`, `icon-180.png`, `icon-512.png`, `manifest.webmanifest`, `.nojekyll`, `LIESMICH.md`).
   Hinweis: `.nojekyll` ist unter Windows/macOS eine „versteckte“ Datei – sie ist nicht zwingend nötig.
3. **Commit changes** klicken.
4. **Settings → Pages**: Bei „Source“ **Deploy from a branch** wählen, Branch **main**, Ordner **/ (root)**, **Save**.
5. Nach 1–2 Minuten ist die App erreichbar unter
   `https://DEIN-GITHUB-NAME.github.io/wortblitz/`

## Aufs iPad

1. Die Adresse in **Safari** öffnen.
2. **Teilen-Symbol → Zum Home-Bildschirm** → Hinzufügen.
3. WortBlitz ab jetzt **immer über das Symbol auf dem Home-Bildschirm** starten.

## Wichtig zu den Daten

- Alle Kinder, Einstellungen und Lernstände werden **nur auf dem iPad** gespeichert – nichts davon landet auf GitHub.
  Das Repo enthält nur die App selbst, keine Schülerdaten.
- Die Daten hängen an der Adresse und an der Home-Bildschirm-App. Wer die App einmal über die Datei und einmal über
  GitHub öffnet, hat zwei getrennte Datenstände.
- Regelmäßig im Lehrermodus **„Sicherung herunterladen“** nutzen.
- Lehrermodus: Den Schriftzug „WortBlitz“ auf dem Startbildschirm 2 Sekunden gedrückt halten, PIN beim ersten Start **1234** (bitte ändern).

## Neue Version einspielen

Im Repository `index.html` durch die neue Datei ersetzen (Upload mit gleichem Namen, Commit).
Die Lernstände auf dem iPad bleiben dabei erhalten, solange die Adresse gleich bleibt.

## Umstieg von Wortblox (V01)

Wer schon die alte Wortblox-Version unter derselben Adresse benutzt hat: einfach `index.html` (und die App-Symbole)
im Repository ersetzen. Alle Kinder und Lernstände bleiben erhalten; das alte „Erz“ wird als Energie-Kristalle
weitergezählt, der Held startet im Outfit „Klassik“.
