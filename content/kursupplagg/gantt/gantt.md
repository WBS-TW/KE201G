---
# An instance of the Blank widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# tags
tags:
- laboration
- schema
- projekt

diagram: true
math: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 1

title: Ganttschema med överblick över kursmoment

design:
  columns: "1"
  spacing:
    padding: ["20px", "0", "20px", "0"]

## Use https://mermaid-js.github.io/mermaid-live-editor/ to modify mermaid gantt
---

Exakta datum för varje kursmoment finns i Kronox: https://kronox.oru.se/ (sök på kurskoden KE201G). <br>
<span style="background-color: #FF0000">Rödmarkerade</span> är obligatoriska moment inom kursen.

```mermaid
gantt
  dateFormat  YYYY-MM-DD
  excludes weekdays saturday,sunday
  
  section Undervisning
  Salsundervisning: 2020-09-01, 2020-10-01
  
  section Labbar
  Labbdugga: crit, LD, 2020-09-08, 1d
  Labb 1 FTIR: crit, L1, 2020-09-14, 1d
  Skriva färdig labbrapport 1: crit, after L1, 5d
  Labb 2 ICP: crit, L2, 2020-09-15, 1d
  Skriva färdig labbrapport 2: crit, after L2, 5d
  Labb 3 GC: crit, L3, 2020-09-21, 1d
  Skriva färdig labbrapport 3: crit, after L3, 5d
  Labb 4 DNA: crit, L4, 2020-09-22, 1d
  Skriva färdig labbrapport 4: crit, after L4, 5d
  Labb 5 Hår: crit, L5, 2020-09-25, 1d 
  Skriva färdig labbrapport 5: crit, after L5, 5d
  
  section Skiftlig rapport
  Färdigställa skriftlig arbete: crit, 2020-09-08, 2020-09-17
  Granskare läser rapport och ger kommentarer (se instruktion nedan): crit, 2020-09-17, 2020-09-22
  Reviderad rapport skickas till Thanh: crit, 2020-09-22, 2020-09-25  
  
  section Statistik
  Individuell statistikuppgift: crit, 2020-09-10, 2020-09-18
  Klassuppgift - presentation: 2020-09-24, 1d
```
Vill du veta mer om Ganttschema? Klicka [här](https://sv.wikipedia.org/wiki/Gantt-schema)
<br>