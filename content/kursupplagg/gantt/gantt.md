---
# An instance of the Blank widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# tags
tags:
- Laboration
- Gantt
- Projekt
- Rapport
- Praktiska moment
- Statistik

diagram: true
math: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 1

title: Ganttschema med datum för varje kursmoment

design:
  columns: "1"
  spacing:
    padding: ["20px", "0", "20px", "0"]

# Use https://mermaid-js.github.io/mermaid-live-editor/ to modify mermaid gantt
# A red vertical line will be shown to mark "today"

---

Uppdaterade datum för varje kursmoment finns i Kronox: https://kronox.oru.se/ (sök på kurskoden KE201G). <br>
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
  Färdigställa labbrapport 1: crit, after L1, 5d
  Labb 2 ICP: crit, L2, 2020-09-15, 1d
  Färdigställa labbrapport 2: crit, after L2, 5d
  Labb 3 GC: crit, L3, 2020-09-21, 1d
  Färdigställa labbrapport 3: crit, after L3, 5d
  Labb 4 DNA: crit, L4, 2020-09-22, 1d
  Färdigställa labbrapport 4: crit, after L4, 5d
  Labb 5 Hår: crit, L5, 2020-09-25, 1d 
  Färdigställa labbrapport 5: crit, after L5, 5d
  
  section Skiftlig rapport
  Färdigställa skriftlig arbete: crit, 2020-09-08, 2020-09-17
  Granskare läser rapport och ger kommentarer (se instruktion nedan): crit, 2020-09-17, 2020-09-22
  Revidera rapport och skicka till Thanh innan deadline: crit, 2020-09-22, 2020-09-25  
  
  section Statistik
  Individuell statistikuppgift: crit, 2020-09-10, 2020-09-18
  Klassuppgift - presentation: 2020-09-24, 1d
```
_Vill du veta mer om vad Ganttschema är? Se [här](https://sv.wikipedia.org/wiki/Gantt-schema)_
<br><br><br>