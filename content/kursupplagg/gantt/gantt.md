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
- Projektarbete
- Rapport
- Praktiska moment
- Statistik

diagram: true
math: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 1

title: Kursinnehåll

design:
  columns: "1"
  spacing:
    padding: ["20px", "0", "20px", "0"]

# Use https://mermaid-js.github.io/mermaid-live-editor/ to modify mermaid gantt
# A red vertical line will be shown to mark "today"

---

# Kursens upplägg

Analysvetenskap och forensik är ett multidisciplinärt område som förutom kemi även innefattar biologi, juridik, statistik och presentationsteknik. Analytiska mätningar för att identifiera kemiska ämnen samt kvantifiera mängder av dessa och är essentiellt för analysvetenskap och att säkerställa att mätningarna har gått rätt till är viktigt inom forensiken. Målet med denna kurs ___Introduktion till analysvetenskap och forensik___ är att ge en förhandsvisning om vilka viktiga vetenskapsområde som programmet kommer att behandla. 

- Grundläggande kemi
- Analytisk kemi
- Biokemi
- Biologi
- Statistik
- Teknisk rapportskrivning


<br>

# Ganttschema med datum för varje kursmoment inom introduktionskursen
<br>

Uppdaterade datum för varje kursmoment finns i Kronox: https://kronox.oru.se/ (sök på kurskoden KE201G). <br>
<span style="background-color: #FF0000">Rödmarkerade</span> är obligatoriska moment inom kursen.


```mermaid
gantt
  dateFormat  YYYY-MM-DD
  excludes weekdays saturday,sunday
  
  section Undervisning
  Salsundervisning: 2022-08-29, 2022-09-27
  Tentamen: 2022-09-30. 1d
  
  section Labbar
  Labbdugga: crit, LD, 2022-09-06, 1d
  Labb 1 FTIR: crit, L1, 2022-09-12, 1d
  Färdigställa labbrapport 1: crit, after L1, 5d
  Labb 2 Krut: crit, L2, 2022-09-13, 1d
  Färdigställa labbrapport 2: crit, after L2, 5d
  Labb 3 GC: crit, L3, 2022-09-19, 1d
  Färdigställa labbrapport 3: crit, after L3, 5d
  Labb 4 DNA: crit, L4, 2022-09-20, 1d
  Färdigställa labbrapport 4: crit, after L4, 5d
  Labb 5 Hår: crit, L5, 2022-09-23, 1d 
  Färdigställa labbrapport 5: crit, after L5, 5d
  
  section Skiftlig rapport
  Färdigställa skriftlig arbete: crit, 2022-09-08, 2022-09-17
  Granskare läser rapport och ger kommentarer: crit, 2022-09-17, 2022-09-22
  Revidera rapport och skicka till Thanh innan deadline: crit, 2022-09-22, 2022-09-25  
  
  section Statistik
  Individuell statistikuppgift: crit, 2022-09-07, 2022-09-19
  Klassuppgift - presentation: 2022-09-22, 1d
```
_Vill du veta mer om vad Ganttschema är? Se [här](https://sv.wikipedia.org/wiki/Gantt-schema)_
<br><br><br>