# BMI Rechner - README

## Projektbeschreibung

Dieses Projekt ist eine einfache Webseite, die einen Body-Mass-Index (BMI)-Rechner implementiert. Benutzer können ihr Gewicht und ihre Körpergröße eingeben, um ihren BMI zu berechnen und eine Einordnung in eine Gewichtskategorie zu erhalten (z. B. Untergewicht, Normalgewicht, Übergewicht oder Adipositas). Der BMI-Wert wird auf Basis der Eingaben dynamisch berechnet und auf der Seite angezeigt.

## Inhalt

Das Projekt besteht aus einer einzigen HTML-Datei, die folgende Komponenten enthält:
1. **HTML-Struktur** für die Eingabe und Anzeige.
2. **CSS-Styling** für eine benutzerfreundliche Oberfläche.
3. **JavaScript-Funktion** zur Berechnung des BMI.

## Funktionsweise

1. **Eingabefelder**: Der Benutzer gibt sein Gewicht in Kilogramm und seine Größe in Zentimetern in die dafür vorgesehenen Eingabefelder ein.
2. **Berechnung**: Nach einem Klick auf den "BMI berechnen"-Button wird die `calculateBMI()`-Funktion ausgeführt:
   - Die Funktion prüft die Gültigkeit der Eingaben.
   - Sie berechnet den BMI basierend auf der Formel:
     \[
     \text{BMI} = \frac{\text{Gewicht}}{\text{Größe}^2}
     \]
   - Die Größe wird dabei von Zentimetern in Meter umgerechnet.
3. **BMI-Kategorie**: Basierend auf dem berechneten BMI wird eine entsprechende Gewichtskategorie festgelegt:
   - **Untergewicht**: BMI < 18,5
   - **Normalgewicht**: 18,5 ≤ BMI < 24,9
   - **Übergewicht**: 25 ≤ BMI < 29,9
   - **Adipositas**: BMI ≥ 30
4. **Anzeige des Ergebnisses**: Das Ergebnis und die Gewichtskategorie werden unterhalb der Eingabefelder angezeigt.

## Dateien und Code-Struktur

- **HTML**: Enthält die Struktur der Webseite, inklusive Eingabefelder für Gewicht und Größe, den Button zum Starten der Berechnung und einen Bereich für die Anzeige des Ergebnisses.
- **CSS**: Definiert das Styling der Anwendung für eine saubere, zentralisierte Anzeige und eine einfache Benutzerinteraktion.
- **JavaScript**: Berechnet den BMI und legt die Gewichtskategorie basierend auf den eingegebenen Werten fest.

## Verwendung

1. Öffnen Sie die HTML-Datei in einem Webbrowser.
2. Geben Sie Ihr Gewicht (in kg) und Ihre Größe (in cm) in die entsprechenden Felder ein.
3. Klicken Sie auf den Button **"BMI berechnen"**.
4. Das Ergebnis wird mit der BMI-Zahl und der Gewichtskategorie angezeigt.

## Anpassungen

- Die Gewichtskategorien können in der JavaScript-Funktion `calculateBMI()` angepasst werden, um andere Kategorien hinzuzufügen oder bestehende zu modifizieren.
- Das Styling kann im `<style>`-Block im `<head>`-Bereich der HTML-Datei angepasst werden.

## Lizenz

Dieses Projekt kann frei kopiert, angepasst und weiterverwendet werden.
