---
date_created: 2026-08-20
date_modified: 2026-08-20
---
```dataview 
table without id file.link AS Persona, file.inlinks AS Muižas
from "Personas/Personas" 
where contains(file.etags, "#dzimta/Bordeliusi")
```