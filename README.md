# Visualisierung der Landtagswahlergebnisse in Baden-Württemberg 2025

> [!CAUTION]
> Die Statistik basiert auf der Ergebnispräsentation des Statistischen Landesamt Baden-Württemberg am Wahltag um 21:48. Zu dem Zeitpunkt wurden 11.541 von 11.570 Wahlergebnisse ausgezählt, ich werde schnellstmöglich das Endergebnis veröffentlichen. Es gibt keine Gewähr für Richtigkeit.

> [!NOTE]
> Das Urheberrecht für die Daten liegt beim Statistischen Landesamt Baden-Württemberg (© Statistisches Landesamt Baden-Württemberg, Stuttgart 2026). Dies wird auch in den Dateien genannt. Die Grafiken sind CC BY-SA (Attribution-Share-Alike).

Da mir einiges „komisch“ vorkam und es dazu keine guten öffentlichen Statistiken gibt, habe ich einige Statistiken erstellt, die wichtige Dinge zeigen.

## Welche Statistiken es gibt

Das Projekt erstellt derzeit Statistiken und Visualisierungen für folgende Bereiche:

- **[Landesweiter Überblick](./overview/)**
  - Wahlberechtigte
  - Wähler
  - Wahlbeteiligung
  - gemeldete Bezirke / Meldegrad
  - Briefwahl-Anteil
  - ungültige Erststimmen
  - ungültige Zweitstimmen
  - führende Parteien bei Erst- und Zweitstimme

- **[Parteivergleich landesweit](./delta/)**
  - Differenz zwischen Zweitstimme und Erststimme je Partei

- **[Wahlkreise als Matrix / Heatmap](./heatmaps/)**
  - Erststimmenanteile aller aktiven Parteien je Wahlkreis
  - Zweitstimmenanteile aller aktiven Parteien je Wahlkreis

- **[Briefwahl vs. Urnenwahl](./modes/)**
  - Vergleich der Parteianteile bei Erststimmen
  - Vergleich der Parteianteile bei Zweitstimmen

- **Erst-/Zweitstimmen-Differenzen**
  - **[Heatmap Wahlkreise × Parteien](./differences/)**: `Zweitstimme minus Erststimme`
  - **[größte Wahlkreis-Abweichungen je Partei](./differences/parties/)**: stärkste Differenzen zwischen Erst- und Zweitstimme
  - **[Scatterplots je Partei für Wahlkreise](./gaps/wahlkreis/)**: Erst- gegen Zweitstimmenanteil
  - **[Scatterplots je Partei für Gemeinden/Städte](./gaps/gemeinde/)**: Erst- gegen Zweitstimmenanteil

- **Gebietsprofile**
  - **[Wahlkreise](./profiles/wahlkreis/)**: Detailprofile für jeden Wahlkreis
  - **[Gemeinden/Städte](./profiles/gemeinde/)**: Detailprofile für jede Gemeinde/Stadt
  - enthalten jeweils:
    - Wahlbeteiligung
    - Meldegrad
    - ungültige Erst- und Zweitstimmen
    - Sieger bei Erst- und Zweitstimme
    - stärkster Erst- bzw. Zweitstimmen-Bonus
    - Parteianteile
    - Vergleich Erststimme vs. Zweitstimme je Partei

- **Top-/Flop-Rankings je Gebietsebene**
  - **[Wahlkreise](./explorer/wahlkreis/)**: Rankings für Wahlbeteiligung, Meldegrad, ungültige Stimmen, Parteianteile und Erst-/Zweitstimmen-Differenzen
  - **[Gemeinden/Städte](./explorer/gemeinde/)**: Rankings für Wahlbeteiligung, Meldegrad, ungültige Stimmen, Parteianteile und Erst-/Zweitstimmen-Differenzen
  - direkte Unterordner:
    - **[Wahlbeteiligung Wahlkreise](./explorer/wahlkreis/turnoutPct/)**
    - **[Meldegrad Wahlkreise](./explorer/wahlkreis/reportedPct/)**
    - **[ungültige Erststimmen Wahlkreise](./explorer/wahlkreis/invalidFirstPct/)**
    - **[ungültige Zweitstimmen Wahlkreise](./explorer/wahlkreis/invalidSecondPct/)**
    - **[Parteianteile Erststimme Wahlkreise](./explorer/wahlkreis/party-share/first/)**
    - **[Parteianteile Zweitstimme Wahlkreise](./explorer/wahlkreis/party-share/second/)**
    - **[Erststimme minus Zweitstimme Wahlkreise](./explorer/wahlkreis/vote-gap/)**
    - **[Wahlbeteiligung Gemeinden/Städte](./explorer/gemeinde/turnoutPct/)**
    - **[Meldegrad Gemeinden/Städte](./explorer/gemeinde/reportedPct/)**
    - **[ungültige Erststimmen Gemeinden/Städte](./explorer/gemeinde/invalidFirstPct/)**
    - **[ungültige Zweitstimmen Gemeinden/Städte](./explorer/gemeinde/invalidSecondPct/)**
    - **[Parteianteile Erststimme Gemeinden/Städte](./explorer/gemeinde/party-share/first/)**
    - **[Parteianteile Zweitstimme Gemeinden/Städte](./explorer/gemeinde/party-share/second/)**
    - **[Erststimme minus Zweitstimme Gemeinden/Städte](./explorer/gemeinde/vote-gap/)**
