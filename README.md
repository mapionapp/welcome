# Was ist [Mapion](https://mapion.de)?
Im Rahmen des [#wirvsvirus Hackathons](https://wirvsvirushackathon.org/) haben wir eine Lösung entwickelt, die aktuelle Informationen zu krisenrelevante POIs (Points of Interest) auf einer Karte darstellt. Entwickelt wurde von uns ein MVP (Minimum Viable Product), also eine Art Prototyp für die Plattformen [Web](https://mapion.de), [iOS]() und [Android]().

Standardmäßig implementieren wir die folgenden POI Kategorien:
- Supermärkte, Bäckereien, Baumärkte (z.B. Begrenztes Sortiment, Länge der Schlange, Einlassbegrenzungen, Zahlungsarten-Kontaktlos, Online Shop verfügbar, Geöffnet / Geschlossen (abgeleitet aus Öffnungszeiten), Lieferung verfügbar)
- Kitas und Schulen (Notbetreuung, Geöffnet / Geschlossen, Kontakt)
- Wichtige öffentliche Plätze (Offen / Gesperrt)
- Ärzte (Fachgebiet, Öffnungszeiten, Besucherzahl, Digitales Wartezimmer verfügbar)
- Krankenhäuser (Fachgebiete)
- Apotheken (Geöffnet / Geschlossen (abgeleitet aus Öffnungszeiten), Besucherzahl)
- Polizei, Öffentliche Ansprechstellen (Geöffnet / Geschlossen (abgeleitet aus Öffnungszeiten))
- User-gesetzte Marker (Geöffnet / Geschlossen (abgeleitet aus Öffnungszeiten))
- Cafés und Restaurants (Lieferung möglich, Anholung möglich, Öffnungszeiten)
- Einzelhandel (Onlineshop oder Telefon zum vorbestellen/liefern)

Da es beim Hackathon noch einige andere Projekte gibt, die sich zum Beispiel auf die Integrierung von Supermarkt Warteschlangen konzentriert haben, planen wir, mit diesen zu kooperieren und deren APIs einzubinden.
Die Grundinformationen der POIs kommen von der Google Maps API und werden durch unsere eigene Community mit aktuellen Infos ergänzt.

## Organisation
Wir kommunizieren aktuell über einen Discord Channel: https://discord.gg/Mh5r2DA
Tretet gerne dem Discord Channel bei!
**Twitter:** [@mapionapp](https://twitter.com/mapionapp)
**YouTube:** [mapion](https://www.youtube.com/channel/UC9XHiGpof3kGjhoR9u-Pi_w)

## Womit arbeiten wir?
### Backend
- Node.js
- MongoDB
- Google Maps API
- docker

### Web-App
- vue.js
- docker
- Google Maps API

### App für iOS und Android
- Flutter
- Google Maps API

# Contribution Guidelines
Es gibt in diesem Projekt Kanban Project Boards auf mehreren Ebenen. Ein Board auf der übergreifenden Projekt-Ebene und je ein Board auf Repo Ebene. Das Board auf der Projekt-Ebene ist nur für Ideen und perspektivische Features. Diese werden dann in die Repo-Boards übersetzt. Die dort erstellten Cards mit den Repo spezifischen Anforderungen können dann mit Issues verknüpft werden. Diese werden dann den Leuten zugewiesen, die sie bearbeiten. Bei Bedarf können den Issues auch noch Pull-Requests zugewiesen werden. Das Branching ist Repo-spezifisch.

# Release
[Aktuelle .apk](https://github.com/wirvsvirus-27/w27-app/releases)

# Screenshot
![](/static/screen_show_flat.png)
![](/static/screen_add_comments_flat.png)
![](/static/screen_show_comments_flat.png)
