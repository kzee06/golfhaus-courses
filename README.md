# GolfHaus course data

Hole geometry for golf courses in the United States, the United Kingdom and
Canada, as downloaded by the GolfHaus app the first time a course is opened.

Each file is a JSON object mapping a course id (its OpenStreetMap way or
relation) to that course's holes: tees, lines of play, green outlines, bunkers
and water, packed as integer offsets from the course's position.

```
<country>/<build>/geo-<n>.json
```

A build's files never change once published. New builds get a new folder.

## Licence

The data is derived from OpenStreetMap and is made available under the
[Open Database License](https://opendatacommons.org/licenses/odbl/1-0/) (ODbL).

© OpenStreetMap contributors. See https://www.openstreetmap.org/copyright.

If you use it, credit OpenStreetMap and keep any database you derive from it
under the same licence.
