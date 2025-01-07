# ADB-GUI-Tool

🚀 **ADB Device Manager** ist ein leistungsstarkes Tool zur Verwaltung von ADB-Geräten. Es bietet zwei Betriebsmodi:  
1. **Simple Modus** für grundlegende Geräteinformationen.  
2. **Hersteller Modus** für erweiterte Funktionen wie Befehlsausführung, Installation und mehr (nur mit OEM-Anmeldung verfügbar).  

Alle erforderlichen Abhängigkeiten werden automatisch durch den **PackageDownloader** bereitgestellt.

---

## 🛠️ **Funktionen**

### Simple Modus (Standardmodus)
- 🔍 **Geräteinformationen anzeigen:**  
  Zeigt grundlegende Informationen wie Hersteller, Modell, Seriennummer und Softwareversion an.
- 🌐 **Einfach zu bedienen:**  
  Für Endnutzer, die schnell einen Überblick über ihre Geräte erhalten möchten.

### Hersteller Modus (Erweiterter Modus)
- 📋 **Erweiterte Geräteinformationen:**  
  Zeigt zusätzliche Systeminformationen wie Build-Nummern und Kernel-Details.
- 💻 **ADB-Befehle ausführen:**  
  Führe benutzerdefinierte Befehle direkt aus der Anwendung aus.
- 📦 **Automatische Installation:**  
  Installiere Anwendungen oder Pakete direkt auf deinem Gerät.
- 🔧 **Geräteverwaltung:**  
  Starte Geräte neu, führe Werksresets durch oder greife auf Debugging-Tools zu.  
  **Hinweis:** OEM-Anmeldung erforderlich.

### Integrierter PackageDownloader
- Lädt automatisch alle benötigten Abhängigkeiten und Bibliotheken herunter, sodass keine manuelle Konfiguration erforderlich ist.

---

## 📥 **Installation**

### Voraussetzungen
1. **ADB (Android Debug Bridge):** Stelle sicher, dass ADB auf deinem System installiert ist.  
2. **USB-Debugging aktivieren:**  
   - Gehe zu `Einstellungen > Über das Telefon > Build-Nummer` und tippe 7 Mal darauf, um die Entwickleroptionen zu aktivieren.
   - Aktiviere `USB-Debugging` in den Entwickleroptionen.

### Installation
1. Klone das Repository:
   ```bash
   git clone https://github.com/xeonios-studio/adbgui.git
   cd ADB-GUI-Tool
