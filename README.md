# Kundenapp Le Marché

Eine Seite für das Handy. Name, Kundenkode, Buchung, Foto und Nachricht bleiben auf diesem Gerät.

## Start

Im Ordner `D:\Einzelhandel App\Le Marche`:

```
python -m http.server 8784
```

Dann im Browser `http://127.0.0.1:8784/` öffnen.

Die SQLite-Fassung (älterer Stand der Blaupause, Ordner `static/`) startet mit:

```
python server.py
```

Sie lauscht auf `http://127.0.0.1:8785/`. Dafür braucht es keine Zusatzpakete.

## Am Handy

Die Adresse in Chrome öffnen und zum Startbildschirm hinzufügen. Kunde und Kasse liegen auf demselben Handy.

## Kontakt laut Website

Le Marché, Kurfürstenstraße 19, 56068 Koblenz. Telefon +49 261 91498861, E-Mail lemarchekoblenz@web.de, Website https://le-marche-koblenz.de/

Öffnungszeiten laut Website: Montag geschlossen, Dienstag geschlossen, Mittwoch 10 bis 19 Uhr, Donnerstag 10 bis 19 Uhr, Freitag 9 bis 19 Uhr, Samstag 9 bis 14 Uhr, Sonntag geschlossen.

Sortiment laut Website: Käse, Wein & Crémant, Süßes & Gebäck, Salami & Schinken, Frische Pasta, Antipasti.

Die Vorteilssätze (1/2/3/5 Prozent) sind die Kartenlogik dieser App und keine Preise der Website. An der Kasse lassen sie sich ändern.
