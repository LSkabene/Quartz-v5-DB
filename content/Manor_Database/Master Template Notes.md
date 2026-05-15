---
date_created: 02-04-2026 18:39 +03:00
date_modified: 10-04-2026 19:10 +03:00
---

# Template - Manor (Replace with the name/title of note if you want; h1 should match titles)

%%Text found between double percentage-signs is only viewable in Source Mode, so you can leave yourself comments and notes that are hidden in Reading/Live Preview modes. Notice how it looks stylistically different in Source Mode, it is probably a grayish text. Requires double percentage-signs at the end to close, like so: %%

**Type:** The distinction between private and crown is something you mention in your notes. For historical data that may change with time, let's start with a flexible approach: a basic property `type` and an additional property `types_historical`. Use `type` for the "current" or "official" type you want to list here. Your Primary Type, so to speak. Then, if there are *other* types this manor was known as, make a list/array under `types_historical`. 

> [!tip] Property inline array/list syntax:
> `types_historical: ["Type One", "Type Type"]`

If you want to make a note (or notes) for definitions of the manor types so that you can link/reference the different types, linking to them here would be like:

> [!tip] Linking in an array/list property type
> `types_historical: ["[[Type One]]", "[[Type Two]]"]`

A list/array is required to make each type its own property value, otherwise they are perceived as a single string. You can use a simple string `types_historical: Type A` if you have only one in that note. `types_historical: "[[Type A]]"` if you want to link it.

## Names

%%Could use dataview to make a table here that pulls from the note's language properties, add the dataview query to this template so it has a similar query table on every note%%

| Latvian | German | Russian | Estonian | Other made-up languages here |
| --- | --- | --- | --- | --- | 
| Some gibberish | Some german gibberish | Russian noises | Estonian Grunting | Fantasy throat singing |
Lielvārde (Unique Identifier)
%%Note name pretending there is more than one a la Annenhof%%
date_created: 
date_modified: 
tags:
  - type/-privātmuiža
type: privātmuiža
aliases:
  - "Lenuwart (1)"
  - "Linwarden"
  - "Lineward"
  - "Lendenwarden"
  - "Lennewaden"
  - "Леневарден"
  - "Лиелварде"
aprinkis: Rīgas
coordinates: 
governorate: Vidzemes
names_est:
names_ger: Lennewarden
names_lith:
names_lv: Lielvārde
names_other:
names_pol:
names_rus: Ленневарден
parish: Lielvārdes
types_historical: %%N/A in this case%%