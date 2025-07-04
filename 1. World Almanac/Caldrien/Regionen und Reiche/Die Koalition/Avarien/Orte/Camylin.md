
> [!infobox]+
> # Camylin
> 
> ![[Settlements.png]]
> ###### Info
>  |
> ---|---|
> 
> **Type** | City|
> **Population** | 80.000 |
> 
> **Kingdom** | Avarien |
> 
> ###### Politics
>  |
> ---|---|
> **Rulers** | `=this.Rulers` |
> **Leaders** | `=this.Leaders` |
> **Religions** | [[Lunarael]] |
> 

> [!infobox|left]- 
> ![[Placeholderimage.png]]
> **Description:** 

# **Camylin**
> [!recite]- Introduction
Nach Tagen der Reise erreicht ihr endlich **Camylin**, eine der größten und geschäftigsten Städte des Südkontinents. Hinter hohen Mauern tobt das Leben – Händler preisen lautstark ihre Waren an, Gaukler ziehen die Blicke auf sich, und der Duft von Gewürzen liegt in der Luft. Am Ufer des glitzernden **Nervorra-Sees** gelegen, wirkt die Stadt wie ein Schmelztiegel aller Völker. Menschen, Elfen, Zwerge, Gnome, Halflinge – sie alle mischen sich auf den Straßen, in Tavernen und auf den Märkten. Doch trotz der Vielfalt liegt eine spür
Doch trotz der Vielfalt liegt eine spürbare Anspannung in der Luft. **Soldaten des Kaiserreichs [[Valentis]]** patrouillieren sichtbar durch die Straßen – schweigend, wachsam, unangenehm präsent.
Camylin ist ein Ort voller Möglichkeiten – und voller Risiken. Die Tore stehen euch offen.



> [!metadata|map]- Map
> ```leaflet
> id: TBD
> image: [[camylin.png]]
> height: 600px
> width: 640px
> lat: 50
> long: 50
> minZoom: 1
> maxZoom: 5
> defaultZoom: 1
> unit: meters
> scale: 1
> darkMode: false
> ```

> [!metadata|districts]- Districts
> [[🪧 District Database|🪧Add New District]]
> ```dataview
table join(aliases, ", ") AS Aliases, join(type, ", ") AS Types
WHERE Settlement = this.file.name AND contains(NoteIcon, "District")
SORT file.name ASC

> [!metadata|shops]- Shops
> [[💲 Shop & Service Database|📝Add New Shop/Service]]
> ```dataview
table join(aliases, ", ") AS Aliases, join(type, ", ") AS Types
WHERE Location = this.file.name AND contains(NoteIcon, "Shop")
SORT file.name ASC

> [!metadata|pois]- Points of Interest
> [[❓ POI Database|📝Add New Point of Interest]]
> ```dataview
table join(aliases, ", ") AS Aliases, join(type, ", ") AS Types
WHERE Location = this.file.name AND contains(NoteIcon, "POI")
SORT file.name ASC

> [!metadata|groups]- Groups
> [[🔰 Group Database| 🔰 Add New Group]]
> ```dataview
table join(aliases, ", ") AS Aliases, join(type, ", ") AS Types
WHERE econtains(Location, this.file.name) AND contains(NoteIcon, "Group")
SORT file.name ASC

> [!metadata|characters]- Characters
> [[👨‍👩‍👧‍👦 NPC Database| 📝Add New NPC]]
> ```dataview
table join(aliases, ", ") AS Aliases, join(occupation, ", ") AS "Occupations", join(link(associatedgroup), ", ") AS "Groups"
WHERE Location = this.file.name AND contains(NoteIcon, "Character") AND !contains(Condition, "Dead")
SORT file.name ASC

## History


## Notes
### Plot Hooks


### Hidden Details


### General Notes




