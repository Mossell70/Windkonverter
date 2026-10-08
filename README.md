# Windkonverter
Windgeschwindigkeits-Konverter für Luftfahrt, Segeln und Wetter – rechnet m/s, km/h, Knoten, mph und Beaufort ineinander um.

**Live:** https://mossell70.github.io/Windkonverter/

## Funktionen
- **Umrechner:** Ausgangseinheit wählen, Wert eingeben – alle anderen Einheiten (inkl. Beaufort mit Bezeichnung) werden sofort berechnet.
- **Seitenwind:** Windrichtung (°), Windstärke (kn) und Bahnnummer (zweistellig 01–36, z. B. 15 – vermeidet Verwechslung mit der Windrichtung) eingeben – berechnet Seitenwind (von links/rechts) sowie Gegen-/Rückenwind. Bei Rückenwind wird das Feld rot mit Achtungszeichen hervorgehoben. Die Grafik zeigt die Bahn immer senkrecht aus Pilotensicht: Bahnnummer unten an der Schwelle, Start-/Landerichtung nach oben. Der Wind wird relativ zur Bahn gezeichnet (oben = von vorne, rechts = von rechts); die umgebende Kompassrose dreht sich mit, sodass der Bahnkurs oben steht.

**Bedienung:** Beim Antippen/Anklicken eines Eingabefelds wird dessen Wert gelöscht, sodass direkt neu eingegeben werden kann. Startwerte sind 0 (die Bahnnummer ist anfangs leer, da 00 keine gültige Bahn ist).

Eine einzelne `index.html` ohne Abhängigkeiten, gehostet über GitHub Pages.
