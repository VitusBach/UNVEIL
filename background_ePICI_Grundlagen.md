# UNVEIL Background: ePICI / Helper Phage System

## 1. Phage-Inducible Chromosomal Islands (PICIs)

### Definition
Phage-induzierbare chromosomale Inseln (PICIs) sind mobile genetische Elemente von 10-15 kb Größe, die sowohl in gram-positiven als auch gram-negativen Bakterien weit verbreitet sind. Sie stellen eine Familie hochentwickelter molekularer Parasiten dar.

### Eigenschaften
- Hochmobil und weit verbreitet
- Tragen Virulenzfaktoren und Abwehrmechanismen
- Können zwischen Bakterienarten mit extrem hoher Frequenz mobilisiert werden
- Im Ruhezustand passiv im Bakterienchromosom integriert

---

## 2. Helper Phage System - Mechanismus

### Aktivierungszyklus

1. **Ruhezustand**: PICI liegt passiv im Bakterienchromosom (Expression eines globalen Repressors)
2. **Aktivierung**: Infektion durch Helfer-Phagen oder Induktion eines Prophagen
3. **Derepression**: Phagen-kodiertes Protein bindet an PICI-Repressor
4. **PICI-Zyklus**:
   - Exzision aus dem Chromosom
   - Replikation
   - Verpackung in Phagen-ähnliche Partikel

### Rpp-Protein (Redirecting Phage Packaging)
- Interagiert mit der kleinen Untereinheit der Phagen-Terminase
- Bildet Heterokomplex, der Phagen-DNA nicht mehr erkennt
- Blockiert Phagen-Verpackung
- Bindet spezifisch an PICI-Genom → fördert PICI-Verpackung

---

## 3. Engineered PICIs (ePICIs)

### Synthetische Biologie-Ansatz

Forscher haben eine Methode entwickelt, um PICIs in *Saccharomyces cerevisiae* zu editieren:

- **Rebooting**: Reaktivierung synthetischer Phagen-Genome in geeigneten Wirtszellen
- Gene können am 3'-Ende der PICI eingefügt werden
- Validiert durch Erzeugung multipler Mutationen in verschiedenen PICI-Genen

### Proof of Concept
- Engineering von PICIs aus *Staphylococcus aureus* und *Escherichia coli*
- EcCICFT073 (E. coli PICI) mobilisiert durch Phage φ80
- Chimäre PICIs erfolgreich zur Infektion von E. coli-Empfängerzellen genutzt

### Anwendungen als "Antibakterielle Drohnen"
- Diagnostische Plattformen zur selektiven Anreicherung von Bakterien
- Detektion von *E. coli* und *S. aureus*
- Sensitivität: ~50 CFU/mL
- Höhere Transferraten als konventionelle Phagen

---

## 4. Pathogenitätsinseln (PAIs) und Virulenzfaktoren

### Definition
Pathogenitätsinseln sind distinkte genetische Elemente (10-100+ kb) auf Chromosomen pathogener Bakterien, die bei nicht-pathogenen Stämmen fehlen.

### Kodierte Virulenzfaktoren

| Kategorie | Beispiele |
|-----------|-----------|
| Adhäsine | Zelladhäsionsproteine |
| Sekretionssysteme | Typ III, Typ IV |
| Toxine | Hämolysine, Exotoxine |
| Invasine | Zellinvasionsproteine |
| Superantigene | SAgs (T-Zell-Aktivatoren) |
| Eisenaufnahme | Siderophore |
| Serumresistenz | Komplementevasion |
| Kapselbildung | Polysaccharidkapsel |

### Beispiele in spezifischen Pathogenen

- **Salmonella**: SP-1 und SP-2 regulieren Invasion und Überleben in Wirtszellen
- **Helicobacter pylori**: Cag-Pathogenitätsinsel (erhöhte Virulenz)
- **Staphylococcus aureus**: SaPI-Familie kodiert Superantigene inkl. Toxic Shock Syndrome Toxin

---

## 5. Immunsystem-Interaktionen

### Superantigene und T-Zell-Aktivierung
- Staphylokokken-Superantigene sind hochmolekulare Proteine
- Potente Stimulatoren für CD4+ T-Lymphozyten
- Nicht-spezifische Aktivierung großer T-Zell-Populationen
- Massive Zytokinfreisetzung

### CRISPR-Cas Interaktion
- Phagen-Induktion von S. aureus Pathogenitätsinseln fördert CRISPR-Cas adaptive Immunantwort
- Verpackung unvollständiger Helfer-Phagen-Genome in SaPI-Partikel
- Defekte virale DNA stimuliert Spacer-Akquisition
- Immunisierte Staphylokokken blockieren Helfer-Phagen und verhindern SaPI-Mobilisierung

---

## 6. Therapeutisches Potenzial

### Aktuelle Forschungsrichtungen

1. **Diagnostik**: PICI-basierte Detektionsplattformen
2. **Antibakterielle Delivery**: Gezielte Gen-Delivery-Systeme
3. **CRISPR-Delivery**: Modifikation von Bakterienpopulationen

### Zukünftige Entwicklungen

- Engineered Helfer-Phagen mit diversen Schwanzfasern
- Erweiterung des PICI-DNA-Delivery auf verwandte Spezies

---

## Quellen

1. [Rebooting Synthetic Phage-Inducible Chromosomal Islands - BioDesign Research](https://spj.science.org/doi/10.34133/2020/5783064)
2. [Bacteriophages benefit from mobilizing pathogenicity islands - Cell (2022)](https://www.cell.com/cell/fulltext/S0092-8674(22)00917-5)
3. [Phage-Inducible Chromosomal Islands as Diagnostic Platform - Advanced Science (2023)](https://advanced.onlinelibrary.wiley.com/doi/full/10.1002/advs.202301643)
4. [E. coli phage-inducible chromosomal island - ISME Journal (2024)](https://academic.oup.com/ismej/advance-article/doi/10.1093/ismejo/wrae258/7941805)
5. [Pathogenicity Islands in Bacterial Pathogenesis - PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC321463/)

---

*Für UNVEIL-Projekt kompiliert: April 2026*
