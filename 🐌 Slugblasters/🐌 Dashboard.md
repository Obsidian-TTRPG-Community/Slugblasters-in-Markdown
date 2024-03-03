---
cssclasses:
  - cards
  - cards-cols-5
---

# [[Groups/👪📚 Group Database|🛹 Crews]]
```dataview
TABLE WITHOUT ID 
	link(file.path, name) AS "Name",
	embed(Logo) AS "Logo",
	Summary AS "Summary"
from "Groups"
WHERE contains(Type, "Crew")
SORT file.name
```

# [[Groups/👪📚 Group Database|👮‍♂️ Authorities]]
```dataview
TABLE WITHOUT ID 
	link(file.path, name) AS "Name",
	Summary AS "Summary"
from "Groups"
WHERE contains(Type, "Authorities")
SORT file.name
```

# [[Groups/👪📚 Group Database|🍦 Sponsors]]
```dataview
TABLE WITHOUT ID 
	link(file.path, name) AS "Name",
	Summary AS "Summary"
from "Groups"
WHERE contains(Type, "Sponsor")
SORT file.name
```

# [[Groups/👪📚 Group Database|🧑‍🤝‍🧑 Crowds]]
```dataview
TABLE WITHOUT ID 
	link(file.path, name) AS "Name",
	Summary AS "Summary"
from "Groups"
WHERE contains(Type, "Crowd")
SORT file.name
```

# [[🎲 Generator Database|🎲 Generators]]
```dataview
TABLE WITHOUT ID 
	link(file.path, displayname) AS "Name",
	gen1 AS "gen1",
	gen2 AS "gen2"
from "Generators"
WHERE Show = True
SORT file.name
```

# 🗺️ Map

```leaflet
id: slugblaster-map
image: [[Multiverse map.png]]
height: 500px
lat: 50
long: 50
minZoom: 1
maxZoom: 3
defaultZoom: 1
unit: meters
scale: 1
darkMode: true
```

# [[Worlds/🏠 World Database|🌎 Worlds]]
```dataview
TABLE WITHOUT ID 
	link(file.path, name) AS "Name",
	Pernounced AS "Pernounced",
	Notes AS "Notes"
from "Worlds"
WHERE contains(NoteIcon, "World")
SORT file.name
```
