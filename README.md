
# Discord Bot

Ein Discord Bot mit verschiedenen Funktionen zur Interaktion und Verwaltung von Discord-Guilds.


## Abhängigkeiten

- **discord.js**: Eine leistungsstarke JavaScript-Bibliothek zur Interaktion mit der Discord-API.
- **mysql2/promise**: Ein MySQL-Client für Node.js mit Promise-Unterstützung.
- **fs**: Ein Node.js-Modul zum Arbeiten mit dem Dateisystem.
- **path**: Ein Node.js-Modul zur Arbeit mit Dateipfaden.
- **@discordjs/rest** und **discord-api-types/v9**: Für die Verwaltung von REST-API-Anfragen in Discord.

## Bot-Befehle

### review
- **Beschreibung:** Review-System zur Bewertung von bestellten Produkten oder Dienstleistungen.

### reminder
- **Beschreibung:** Kann in Tickets verwendet werden um dem User eine Erinnerung per DM zu schicken, dass eine Antwort gekommen ist.

### ticket-add
- **Beschreibung:** Fügt einen Benutzer zum Ticket hinzu.
- **Optionen:**
  - `user`: Der Benutzer, der zum Ticket hinzugefügt werden soll (erforderlich).

### lookup
- **Beschreibung:** Zeigt Informationen über einen Benutzer an und gibt die möglichkeit diesen zu Bannen, Kicken, Timeouten.
- **Optionen:**
  - `user`: Der Benutzer, über den Informationen angezeigt werden sollen (erforderlich).

### paysafecard
- **Beschreibung:** Erstellt ein Modal damit der Paysafecard-Code sicher übermittelt werden kann.

## Starten des Bots

Um den Bot zu starten, verwende folgenden Befehl:

```bash
yarn start
```

## Lizenz

Dieses Projekt ist lizenziert unter der MIT-Lizenz. Siehe die [LICENSE](LICENSE) Datei für Details.
