---
aliases: [Benislavsku]
date_created: 2026-08-18
date_modified: 2026-08-20
publish: true
---
```dataview 
table without id file.link AS Persona, file.inlinks AS Muižas
from "Personas/Personas" 
where contains(file.etags, "#dzimta/Benislavski")
```
