---
publish: true
created: 2026-04-02T18:39:49.867+03:00
modified: 2026-04-10T19:10:22.912+03:00
published: 2026-04-10T19:10:22.912+03:00
date_created: 02-04-2026 18:39 +03:00
date_modified: 10-04-2026 19:10 +03:00
---

# Template - Manor (Replace with the name/title of note if you want; h1 should match titles)

**Type:** The distinction between private and crown is something you mention in your notes. For historical data that may change with time, let's start with a flexible approach: a basic property `type` and an additional property `types_historical`. Use `type` for the "current" or "official" type you want to list here. Your Primary Type, so to speak. Then, if there are _other_ types this manor was known as, make a list/array under `types_historical`.

> [!tip] Property inline array/list syntax:
> `types_historical: ["Type One", "Type Type"]`

If you want to make a note (or notes) for definitions of the manor types so that you can link/reference the different types, linking to them here would be like:

> [!tip] Linking in an array/list property type
> `types_historical: ["[[Type One]]", "[[Type Two]]"]`

A list/array is required to make each type its own property value, otherwise they are perceived as a single string. You can use a simple string `types_historical: Type A` if you have only one in that note. `types_historical: "[[Type A]]"` if you want to link it.

## Names

| Latvian | German | Russian | Estonian | Other made-up languages here |
| --- | --- | --- | --- | --- |
| Some gibberish | Some german gibberish | Russian noises | Estonian Grunting | Fantasy throat singing |
Lielvārde (Unique Identifier)

date\_created:
date\_modified:
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
  names\_est:
  names\_ger: Lennewarden
  names\_lith:
  names\_lv: Lielvārde
  names\_other:
  names\_pol:
  names\_rus: Ленневарден
  parish: Lielvārdes
  types\_historical:&#x20;
