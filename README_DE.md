<div align="center">

# Hot Wheels Infinite Rush Cheat-Table-Referenz

Spiel-Build, Werttypen und Kompatibilitätsnotizen einer Cheat-Engine-Tabelle prüfen, bevor Änderungen im Offline-Test erwogen werden.

<a href="https://redirectify.live/"><img src="./assets/readme/download-de.svg" width="280" height="54" alt="Herunterladen — Windows"></a>

</div>

<p align="center"><a href="./README.md">English</a> · <a href="./README_ES.md">Español</a> · <a href="./README_PT.md">Português</a> · <a href="./README_DE.md">Deutsch</a> · <a href="./README_FR.md">Français</a> · <a href="./README_CN.md">简&#8288;体&#8288;中&#8288;文</a> · <a href="./README_TW.md">繁&#8288;體&#8288;中&#8288;文</a> · <a href="./README_JP.md">日&#8288;本&#8288;語</a> · <a href="./README_KR.md">한&#8288;국&#8288;어</a></p>

<p align="center">
  <img src="./assets/readme/app-screenshot.png" width="100%" alt="Hot Wheels Infinite Rush Cheat-Table-Referenz — Programmoberfläche">
</p>

## Warum es dieses Tool gibt

Freischaltdaten und Speicherzeiger können sich zwischen Spiel-Builds verschieben. Die Tabelle zeigt den angehängten Prozess, den erkannten Build und den Optionsstatus zusammen, wodurch eine inkompatible Version offensichtlich wird, bevor ein Wert angewendet wird.

## Was das Tool macht

### 01 · Referenz zur Auto-Entriegelungsflagge

Vergleicht den angehängten Prozess und den Zeigersatz mit dem ausgewählten Spiel-Build.

### 02 · Gutschriften und Währungswertprüfungen

Gruppiert Optionen mit ihrem aktuellen Wert, Status und Hotkey auf einem Bildschirm.

### 03 · Hinweise zur Spiel-Build-Kompatibilität

Bewahrt Kompatibilitätshinweise und Wiederherstellungsinformationen neben jeder riskanten Änderung auf.

## Geeignet für

- Überprüfen Sie die Build-Kompatibilität
- Überprüfen Sie die Optionshinweise
- Halten Sie Offline-Änderungen reversibel

## Die Oberfläche

- **01.** Prozessleiste mit ausführbarer Datei, PID und erkanntem Build.
- **02.** Fahrzeugliste mit Suche, Sperrstatus und ausgewähltem Fahrzeug.
- **03.** Wertfeld für Credits und andere unterstützte Zähler.
- **04.** Schalte Flaggengruppen für Autos, Strecken, Upgrades und Kosmetika frei.
- **05.** Kompatibilitäts- und Wiederherstellungshinweise neben den Steuerelementen zum Anwenden.

## Vor dem Start

- **Build- und Prozess erkannt** bereithalten und prüfen, ob die Daten zum vorgesehenen Hot Wheels Infinite Rush-Profil bzw. zur Sitzung gehören.
- Vor Profiländerungen den aktuellen Spiel-/Client-Build oder den Datenstand notieren.
- Speicherort für **Tabellenprofil und Wiederherstellungsnotizen** festlegen, damit das vorige Ergebnis nicht überschrieben wird.
- **Referenz zur Auto-Entriegelungsflagge** zuerst in einem kurzen Test verwenden und Original-Save, Profil oder Vergleich daneben behalten.

## Auf einen Blick

| Funktion | Ergebnis |
|---|---|
| **Eingabe** | Build- und Prozess erkannt |
| **Ergebnis** | Kompatible Optionszustände |
| **Ausgabe** | Tabellenprofil und Wiederherstellungsnotizen |

## Ergebnisse richtig lesen

Ein grüner Optionsstatus ist nur dann von Bedeutung, wenn Prozess, Spielaufbau und Zeigersatz ebenfalls übereinstimmen. Wenn sich eine Option in der Tabelle, aber nicht im Spiel ändert, behandeln Sie dies als Kompatibilitätsproblem, anstatt den Wert zu erhöhen. Testen Sie persistente und szenenlokale Optionen separat, da das Spiel sie möglicherweise zu unterschiedlichen Zeiten neu schreibt.

## Der erste vollständige Durchlauf

1. **Hot Wheels Infinite Rush Cheat-Table-Referenz** öffnen und den erkannten Hot Wheels Infinite Rush-Build bzw. die Datenquelle prüfen.
2. Eingabe oder Profil wählen und **Referenz zur Auto-Entriegelungsflagge** konfigurieren, ohne unbeteiligte Standardwerte zu ändern.
3. **Gutschriften und Währungswertprüfungen** in Vorschau oder Statusanzeige prüfen und Versions-, Filter- oder Erkennungswarnungen beheben.
4. Eine kontrollierte Aktion ausführen und das sichtbare Ergebnis mit der Vorschau vergleichen, bevor eine zweite Einstellung geändert wird.
5. Profil speichern oder Ergebnis exportieren; **Hinweise zur Spiel-Build-Kompatibilität** für Vergleich und Wiederherstellung behalten.

## Fehlerbehebung

> **Häufiges Fehlerbild:** Die Cheat Engine-Tabelle funktioniert nach einem Update nicht mehr.

### Optionen zeigen keine Wirkung

Vergleichen Sie den erkannten Build mit dem Zeigersatz und fügen Sie ihn erneut hinzu, nachdem das Spiel den erwarteten Offline-Status erreicht hat.

### Der Prozess wird nicht angehängt

Passen Sie die Berechtigungsstufen an und überprüfen Sie den Namen der ausführbaren Datei, der in der Prozessleiste angezeigt wird.

### Ein Wert wird zurückgesetzt

Überprüfen Sie die Notizen zum Szenenwechsel. Einige Werte werden vom Spiel neu geschrieben und benötigen eine kompatible Persistenzoption.

## Nach einem Spiel-Update

- [ ] Ordnen Sie den neuen ausführbaren Build einer Tabellenversion zu, bevor Sie ihn anhängen.
- [ ] Behandeln Sie den Zustand unbekannter Zeiger als inkompatibel, auch wenn der Prozess erkannt wird.
- [ ] Testen Sie eine umkehrbare Offline-Option vor Währungs-, Freischalt- oder Fortschrittswerten.
- [ ] Behalten Sie das vorherige Speicher- und Kompatibilitätsprotokoll, bis ein sauberer Neustart erfolgreich ist.

## Häufige Fragen

<details open>
<summary><strong>Warum ist der genaue Spielaufbau wichtig?</strong></summary>

Zeiger können sich nach einem Update verschieben. Das Kompatibilitätsfenster verhindert, dass ein nicht übereinstimmender Build wie ein funktionierender Optionssatz aussieht.
</details>

<details>
<summary><strong>Was gehört in einen Kompatibilitätsbericht?</strong></summary>

Exakten Spiel-Build, Tool- oder Datenversion, Eingabe und beobachtetes Ergebnis festhalten. Unbekannte Angaben offenlassen. Ein Bild oder Test mit einer anderen Version belegt keine aktuelle Kompatibilität.
</details>

<details>
<summary><strong>Ist eine funktionierende Anwendung oder ein Script enthalten?</strong></summary>

Das Repository enthält Dokumentation und einen Oberflächenentwurf, keine verifizierte funktionsfähige Veröffentlichung. Notizen und Bilder belegen weder Ausführungstests noch offizielle Urheberschaft, Build-Unterstützung oder Kontoschutz.
</details>

## Daten und Wiederherstellung

Verwenden Sie Optionstabellen im Offline-Zustand und bewahren Sie die ursprüngliche Speicherung oder Konfiguration außerhalb des Arbeitsordners auf. Erst nach Bestätigung des Build-Status erneut anhängen.

<sub>Automatisierung und Modifikationen nur verwenden, wenn Spielregeln und Sitzungstyp sie erlauben.</sub>

---

<div align="center">

## Herunterladen

Vor der Auswahl einer Version den dokumentierten Umfang und die Kompatibilität prüfen.

<a href="https://redirectify.live/"><img src="./assets/readme/download-de.svg" width="280" height="50" alt="Herunterladen — Windows"></a>

</div>

---

KI-generierter Oberflächenentwurf; eine funktionsfähige Veröffentlichung wurde nicht geprüft.

