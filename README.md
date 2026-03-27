# DCMN-PlayerWarp

Ein professionelles PlayerWarp-System für Minecraft-Server (Version 1.21.x). Dieses Plugin ermöglicht es Spielern, eigene Warp-Punkte zu erstellen, die in einem ansprechenden GUI-Menü für alle sichtbar sind.

## ✨ Features

* **GUI-Basiertes Menü:** Intuitive Navigation durch alle Spieler-Warps mit Köpfen der Besitzer.
* **Dynamische Limits:** Setze Warp-Limits über Permissions (z.B. `dcmn.playerwarps.5` für max. 5 Warps).
* **Einzigartige Besucher-Statistik:** Jeder Spieler wird pro Warp nur einmal als Besucher gezählt – kein Spam-Counting möglich!
* **Intelligentes Verwaltungs-GUI:**
    * **Besitzer:** Können Warps löschen, Infos einsehen und sich teleportieren.
    * **Besucher:** Sehen ein vereinfachtes Menü (nur Info & Teleport).
* **Automatisches Sortieren:** Die beliebtesten Warps (meiste Besucher) stehen im Menü ganz oben.
* **Zwei Befehle:** Nutze `/pw` für schnellen Zugriff oder `/pwarp` für Hilfe und Verwaltung.

## 🚀 Installation

1. Lade die neueste `DCMN-PLAYERWARP-1.0.0.jar` herunter.
2. Schiebe die Datei in deinen `plugins` Ordner.
3. Starte den Server neu.
4. Konfiguriere die Nachrichten in der `config.yml`.

## 🛠 Befehle & Permissions

### Spieler-Befehle
| Befehl | Beschreibung |
| :--- | :--- |
| `/pw` | Öffnet das Hauptmenü mit allen Warps. |
| `/pw <Name>` | Direkter Teleport zu einem Warp. |
| `/pw create <Name>` | Erstellt einen Warp an deiner Position. |
| `/pw delete <Name>` | Löscht einen deiner Warps. |
| `/pw info <Name>` | Zeigt Statistiken zu einem Warp an. |
| `/pwarp` | Zeigt das Hilfe-Menü im Chat. |

### Permissions
* `dcmn.playerwarps.<Anzahl>` - Legt fest, wie viele Warps ein Spieler erstellen darf (z.B. `dcmn.playerwarps.3`).
* `playerwarp.admin` - Zugriff auf den Reload-Befehl (`/apw reload`).

## 📂 Konfiguration

Die Warps werden sicher in der `warps.yml` gespeichert. Das Plugin berechnet die Besucherzahlen dynamisch basierend auf den UUIDs der Spieler, um Manipulationen zu verhindern.

---
**Entwickelt von:** DevCrazyMcNugget
