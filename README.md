# Ship Status Panel
### Star Citizen · Browser-Display · Fan-made

---

> 🇩🇪 **Rechtlicher Hinweis**
> Dieses Projekt ist ein inoffizielles Fan-Projekt, das für den persönlichen Gebrauch
> erstellt und mit der Star Citizen Community geteilt wird. Es besteht keine Verbindung
> zu Cloud Imperium Games Corp. oder Roberts Space Industries Corp., und das Projekt
> wird von diesen Unternehmen weder unterstützt noch ist es mit ihnen verbunden.
> *Star Citizen® ist eine eingetragene Marke der Cloud Imperium Games Corp.*
>
> 🇬🇧 **Legal Notice**
> This is a fan-made project created for personal use and shared with the Star Citizen
> community. It is not affiliated with, endorsed by, or in any way connected to Cloud
> Imperium Games Corp. or Roberts Space Industries Corp.
> *Star Citizen® is a registered trademark of Cloud Imperium Games Corp.*

---

## Was ist das? · What is this?

🇩🇪 Ein Browser-Display das deinen Schiffszustand in Star Citizen live anzeigt —
auf Tablet, Handy oder zweitem Monitor. Nur ein Browser, sonst nichts.

Das Panel empfängt Live-Daten vom **Ship Status Wingman AI Skill** über MQTT
und zeigt 14 Schiffssysteme in Echtzeit an, im Stil des jeweiligen Herstellers.

🇬🇧 A browser display that shows your ship status in Star Citizen live —
on a tablet, phone, or second monitor. Just a browser, nothing else.

The panel receives live data from the **Ship Status Wingman AI Skill** via MQTT
and displays 14 ship systems in real time, styled to match each manufacturer.

---

## Panel öffnen · Open the panel

🇩🇪 Die URL bekommst du beim Aktivieren des Wingman Skills im Log angezeigt.
Ersetze `DEIN-TOPIC` mit deinem Topic aus dem Wingman-Log:

🇬🇧 The URL is shown in the Wingman log when you activate the skill.
Replace `YOUR-TOPIC` with your topic from the Wingman log:

```
https://gwuital.github.io/ship-status/?theme=drake&topic=DEIN-TOPIC
https://gwuital.github.io/ship-status/?theme=rsi&topic=DEIN-TOPIC
https://gwuital.github.io/ship-status/?theme=aegis&topic=DEIN-TOPIC
https://gwuital.github.io/ship-status/?theme=anvil&topic=DEIN-TOPIC
https://gwuital.github.io/ship-status/?theme=origin&topic=DEIN-TOPIC
https://gwuital.github.io/ship-status/?theme=crusader&topic=DEIN-TOPIC
https://gwuital.github.io/ship-status/?theme=misc&topic=DEIN-TOPIC
https://gwuital.github.io/ship-status/?theme=cnou&topic=DEIN-TOPIC
https://gwuital.github.io/ship-status/?theme=banu&topic=DEIN-TOPIC
https://gwuital.github.io/ship-status/?theme=xian&topic=DEIN-TOPIC
https://gwuital.github.io/ship-status/?theme=argo&topic=DEIN-TOPIC
https://gwuital.github.io/ship-status/?theme=vanduul&topic=DEIN-TOPIC
```

💡 🇩🇪 Als Lesezeichen speichern — das Topic ist in der URL enthalten.
💡 🇬🇧 Save as a bookmark — the topic is baked into the URL.

---

## Verfügbare Themes · Available Themes

| Theme | Hersteller · Manufacturer | Schiffe (Beispiele) · Ships (examples) |
|---|---|---|
| `drake` | Drake Interplanetary | Cutlass, Corsair, Caterpillar |
| `rsi` | Roberts Space Industries | Constellation, Aurora, Zeus |
| `aegis` | Aegis Dynamics | Hammerhead, Gladius, Vulcan |
| `anvil` | Anvil Aerospace | Hornet, Carrack, Valkyrie |
| `origin` | Origin Jumpworks | 300i, 890 Jump, M50 |
| `crusader` | Crusader Industries | Mercury, C2 Hercules |
| `misc` | Musashi Industrial | Freelancer, Prospector |
| `cnou` | Consolidated Outland | Mustang, Pioneer |
| `banu` | Banu Collective | Merchantman |
| `xian` | Xi'an / Aopoa | Khartu-Al, San'tok.yāi |
| `argo` | Argo Astronautics | MOLE, Raft, SRV |
| `vanduul` | Vanduul War Fleet | Scythe, Glaive, Blade |

🇩🇪 Alle Themes sind eigene Interpretationen des jeweiligen Hersteller-Looks —
angelehnt an Cockpit-Screenshots, keine 1:1-Nachbauten.

🇬🇧 All themes are original interpretations of each manufacturer's aesthetic —
inspired by cockpit screenshots, not 1:1 recreations.

---

## Wingman Skill

🇩🇪 Das Panel funktioniert zusammen mit dem **Ship Status Wingman AI Skill**.
Einrichtung und Anleitung: → [ship_status Skill](https://github.com/Gwuital/ship_status)

🇬🇧 The panel works together with the **Ship Status Wingman AI Skill**.
Setup and instructions: → [ship_status Skill](https://github.com/Gwuital/ship_status)

---

## Technik · Tech

- **MQTT** — öffentlicher Broker (`broker.emqx.io`), WSS Port 8084
- **Zufalls-Topic** — jede Installation bekommt ihr eigenes Topic / each install gets its own random topic
- **CSS-Theme-System** — ein HTML-Skelett, 12 Hersteller-CSS-Dateien
- **Kein Backend** — reines Static Hosting via GitHub Pages / pure static hosting

---

## Lizenz · License

MIT — frei verwendbar, veränderbar und weiterzugeben / free to use, modify and share.

Credit appreciated: **Gwuital aka Akirafox**
