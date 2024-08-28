
# Discord Bot

Ein Discord Bot mit verschiedenen Funktionen zur Interaktion und Verwaltung von Discord-Guilds.

## Installation

1. Klone dieses Repository:
    ```bash
    git clone <repository-url>
    ```
2. Installiere die benötigten Abhängigkeiten:
    ```bash
    npm install
    ```

3. Erstelle eine `config.json` Datei basierend auf der mitgelieferten Vorlage und füge deinen Discord-Bot-Token und andere erforderliche Konfigurationsinformationen hinzu.

## Konfiguration

Stelle sicher, dass die `config.json` Datei folgende Struktur hat:

```json
{
  "token": "YOUR_BOT_TOKEN",
  "guildId": "YOUR_GUILD_ID"
}
```

## Verwendete Technologien

- **discord.js**: Eine leistungsstarke JavaScript-Bibliothek zur Interaktion mit der Discord-API.
- **mysql2/promise**: Ein MySQL-Client für Node.js mit Promise-Unterstützung.
- **fs**: Ein Node.js-Modul zum Arbeiten mit dem Dateisystem.
- **path**: Ein Node.js-Modul zur Arbeit mit Dateipfaden.
- **@discordjs/rest** und **discord-api-types/v9**: Für die Verwaltung von REST-API-Anfragen in Discord.

## Bot-Befehle

### review
- **Beschreibung:** Öffnet ein Formular für eine Bewertung.

### reminder
- **Beschreibung:** Sendet eine Erinnerung an den Benutzer, dass eine neue Antwort vorliegt.

### ticket-add
- **Beschreibung:** Fügt einen Benutzer zum Ticket hinzu.
- **Optionen:**
  - `user`: Der Benutzer, der zum Ticket hinzugefügt werden soll (erforderlich).

### lookup
- **Beschreibung:** Zeigt Informationen über einen Benutzer an.
- **Optionen:**
  - `user`: Der Benutzer, über den Informationen angezeigt werden sollen (erforderlich).

### paysafecard
- **Beschreibung:** Spezifische Funktionen im Zusammenhang mit Paysafecard-Embeds.

## Starten des Bots

Um den Bot zu starten, verwende folgenden Befehl:

```bash
node index.js
```

Stelle sicher, dass der Bot die richtigen Berechtigungen in deiner Discord-Guild hat, um ordnungsgemäß zu funktionieren.

## Lizenz

Dieses Projekt ist lizenziert unter der MIT-Lizenz. Siehe die [LICENSE](LICENSE) Datei für Details.
