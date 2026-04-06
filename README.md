# 🚴 ActivityWeather Pro

**RideWeather Pro** is een superstrakke, browser-gebaseerde tool voor wielrenners en hardlopers die hun Strava- of Komoot-activiteiten willen verrijken met accurate weerdata. Geen saaie tekstjes meer, maar data met een "vibe".

## 🌟 Belangrijkste Features

- **📍 Locatie Intelligentie:** Automatische herkenning van je startlocatie via GPS (Reverse Geocoding).
- **🛤️ A-naar-B Modus:** Speciaal voor lange ritten of runs; bereken het weerverloop van je startpunt tot je finishlocatie.
- **🌡️ Dynamische Icoontjes:** Automatische weergave van het weerbeeld (zon, regen, wolken) op basis van officiële WMO-codes.
- **🎭 De Vibe-Slider:** Kies hoe je de data presenteert met een stapsgewijze selector:
    - **Nerd 🤓:** Voor de data-analisten (luchtvochtigheid, exacte gevoelstemperatuur, windrichting).
    - **Gewoon 🌤️:** Een gebalanceerde, menselijke samenvatting voor je volgers.
    - **Avonturier 🌋:** Heroïsche, willekeurig gegenereerde teksten die passen bij jouw strijd tegen de elementen.
- **🏃 Activiteit-Specifiek:** De tekstgeneratie past zich aan; een fietser gaat "beuken tegen de wind" terwijl een loper "kilometers vreet".

## 🚀 Hoe te gebruiken?

1.  Open https://peterkrijgsman85.github.io/activity-weather/ simpelweg in je favoriete browser (geen server nodig).
2.  Geef toestemming voor je locatie of typ handmatig een stad in.
3.  Kies je activiteit, de datum/tijd en je gewenste **vibe**.
4.  Klik op **Genereer Bericht**.
5.  Klik op een van de resultaten om de tekst direct naar je klembord te kopiëren.
6.  Plak het in je Strava/komoot-beschrijving en zie die kudo's binnenstromen! 👍

## 🛠️ Techniek

Dit project is "zero-dependency" en extreem snel:
- **HTML5 & Modern CSS:** Responsief kaart-ontwerp met Strava-accenten.
- **Vanilla JavaScript:** Volledige logica zonder zware frameworks.
- **Open-Meteo API:** Voor hoogwaardige actuele én historische weerdata (geen API-key nodig).
- **Nominatim (OpenStreetMap):** Voor het vertalen van GPS-coördinaten naar plaatsnamen.

## 📄 Licentie

Dit project is open-source. Voel je vrij om het te forken, aan te passen voor je eigen fietsclub, of te delen met je sportvrienden.

---
*Gemaakt voor atleten die net zoveel van data houden als van de buitenlucht.* 🤘
