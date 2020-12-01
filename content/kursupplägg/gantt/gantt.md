---
# An instance of the Blank widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: blank

# Activate this widget? true/false
active: true

diagram: true
math: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 2

title: Ganttschema med överblick över kursmoment

design:
  columns: "1"
  spacing:
    padding: ["20px", "0", "20px", "0"]
---



```mermaid
gantt
  dateFormat  YYYY-MM-DD
  section Undervisning
  Salsundervisning: 2020-09-01, 2020-10-01
  section Labbar
  Labbdugga: LD, 2020-09-08, 1d
  Labb 1 FTIR: L1, 2020-09-14, 1d
  Skriva färdig labbrapport 1: after L1, 5d
  Labb 2 ICP: L2, 2020-09-15, 1d
  Skriva färdig labbrapport 2: after L2, 5d
  Labb 3 GC: L3, 2020-09-21, 1d
  Skriva färdig labbrapport 3: after L3, 5d
  Labb 4 DNA: L4, 2020-09-22, 1d
  Skriva färdig labbrapport 4: after L4, 5d
  Labb 5 Hår: L5, 2020-09-25, 1d 
  Skriva färdig labbrapport 5: after L5, 5d
  section Skiftlig rapport
  Färdigställa skriftlig arbete: 2020-09-08, 2020-09-17
  Granskare läser rapport och ger kommentarer (se instruktion nedan): 2020-09-17, 2020-09-22
  Reviderad rapport skickas till Thanh: 2020-09-22, 2020-09-25  
  section Statistik
  Individuell statistikuppgift: 2020-09-10, 2020-09-18
  Klassuppgift - presentation: 2020-09-24, 1d
```
