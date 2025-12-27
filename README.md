# CopyJobManager

**CopyJobManager** ist eine Windows-Desktop-Anwendung zur komfortablen Verwaltung, Ausführung und Automatisierung von Datei-Kopiervorgängen auf Basis von **Robocopy**.  
Sie ersetzt komplexe Batch-Skripte und manuelle Konsolenaufrufe durch eine übersichtliche grafische Oberfläche mit Vorlagen, Zeitplanung und sauberer Protokollierung.

---

## ✨ Features

### 📁 Job-Vorlagen
- Beliebig viele Kopierjobs (Quelle → Ziel) als Vorlagen speichern
- Zentrale Übersicht aller Jobs
- Einfache Bearbeitung und Wiederverwendung
- Export & Import von Vorlagen (JSON)

### ▶️ Ausführung & Monitoring
- Start/Stop von Kopierjobs per Klick
- Live-Log direkt in der Anwendung
- Fortschrittsanzeige während des Kopiervorgangs
- Automatische Logdateien mit Zeitstempel

### ⏱️ Automatisierung
- Zeitgesteuerte Ausführung pro Vorlage (Uhrzeit + Wochentage)
- **Headless-Modus** für Hintergrundbetrieb
- Optimiert für **Windows Aufgabenplanung**
- Läuft auch **ohne Benutzeranmeldung** (z. B. beim Systemstart)

### 🔄 Update-Hinweis
- Beim Start automatische Prüfung auf neue GitHub-Releases
- Hinweis, wenn eine neuere Version verfügbar ist

---

## 🧠 Typische Einsatzszenarien

- Regelmäßige Backups von Arbeits- oder Projektordnern
- Synchronisation auf NAS oder Server
- Nachts oder am Wochenende geplante Kopierjobs
- Einheitliche Kopierprozesse auf mehreren Rechnern (per Import/Export)

