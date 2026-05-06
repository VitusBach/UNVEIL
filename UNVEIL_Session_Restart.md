# UNVEIL Project - Session Restart File

## Projektname

**UNVEIL** - Universal ePICI-Vectored Epitope Immune Labeling

---

## Konzept in einem Satz

ePICIs (engineered Phage-Inducible Chromosomal Islands) werden genutzt, um während aktiver bakterieller Infektionen Antigene zu exponieren und so die Immunantwort zur **Clearance komplizierter Infektionen** zu unterstützen.

---

## Kernhypothese

Durch ePICI-vermittelte Infektion pathogener Bakterien können T-Zell- und B-Zell-Epitope exprimiert/exponiert werden, die das Immunsystem zur effektiven Clearance aktivieren - insbesondere bei:
- Biofilm-Infektionen
- Intrazellulären Infektionen (SCVs)
- Chronischen/persistierenden Infektionen
- Antibiotika-resistenten Erregern (MRSA)

**Fokus:** Therapeutische Immununterstützung bei aktiver Infektion (NICHT prophylaktische Vakzinierung)

---

## Dokumentstruktur

Alle Dokumente befinden sich in diesem Ordner:

| Datei | Inhalt |
|-------|--------|
| **UNVEIL_Session_Restart.md** | Dieses File - Projektübersicht |
| **UNVEIL_Projektskizze.md** | Detaillierter Projektplan |
| **background_ePICI_Grundlagen.md** | PICIs, Helper Phage System, PAIs |
| **background_PICI_Aktivierung.md** | ERP-Zyklus, Transfereffizienz |
| **background_Rebooting_Paper.md** | Hefe-basiertes PICI-Engineering |
| **background_Helferphagen.md** | Helferphagen, Stl-Inducer |
| **background_S_aureus_Intrazellular.md** | SCVs, Trojanisches Pferd |
| **background_Biofilm_Resistenz.md** | 3-Wochen-Schwelle |

---

## Warum dieses Projekt?

### Problem: S. aureus Vakzine sind gescheitert (~30 klinische Studien)

| Grund | Mechanismus |
|-------|-------------|
| **IL-10 Suppression** | S. aureus induziert IL-10 → Antikörper inaktiviert |
| **Immune Imprinting** | Nicht-protektive Antikörper durch Erstexposition |
| **Fehlende Th17-Antwort** | Nur Antikörper, keine T-Zell-Immunität |
| **Einzelantigen-Ansätze** | Zu wenige Targets |

### Lösung: UNVEIL

- **In-situ** während aktiver Infektion (anderer Immunkontext)
- **Kryptische Antigene** durch Phagen-Lyse exponiert
- **Bakterielle PAMPs** als intrinsisches Adjuvans (Th17-Induktion)
- **Multiple Antigene** gleichzeitig

### Forschungslücke

**NIEMAND hat bisher ePICIs für Immuntherapie/Antigenpräsentation eingesetzt!**

---

## Technische Basis

### ePICI-Technologie (etabliert)

| Komponente | Status |
|------------|--------|
| Hefe-basiertes Rebooting | Etabliert (Ibarra-Chavez 2020) |
| Δcos Helferphagen | Verfügbar (reine ePICI-Partikel) |
| SaPI-Backbone | Charakterisiert |
| Transfereffizienz | ~10⁵/ml (1000x höher als Transduktion) |

### Helferphagen

| Phage | Eigenschaft |
|-------|-------------|
| **80α** | Breitester Wirtsbereich, "universal" |
| **80α Δcos** | Nur ePICI-Partikel (keine Phagen) |
| **φ11** | Gut charakterisiert |

### Antigen-Präsentation (noch zu klären!)

| Option | Mechanismus |
|--------|-------------|
| **A: Oberfläche** | Fusion mit Sortase-Substrat → B-Zell-Epitope |
| **B: Sekretion** | Sec-Signalpeptid → lösliche Antigene |
| **C: Lyse** | Expression bei Phagen-Lyse → massive Freisetzung |
| **D: Hybrid** | Kombination |

---

## Ziel-Antigene (S. aureus)

### SaPI-kodierte Virulenzfaktoren

| Antigen | Funktion |
|---------|----------|
| TSST-1 | Superantigen (detoxifiziert) |
| SEB/SEC | Enterotoxine (detoxifiziert) |

### Essentielle Virulenzfaktoren

| Antigen | Funktion |
|---------|----------|
| ClfA/ClfB | Adhäsion, Biofilm |
| IsdB | Eisenaufnahme |
| Hla | α-Hämolysin |

### Th17-induzierende Antigene

| Antigen | Rationale |
|---------|-----------|
| MntC | Mangan-Transporter |
| FhuD2 | Eisen-Siderophor |

---

## Offene Forschungsfragen

### Mechanistisch

1. **Präsentation vs. Lyse?** - Welcher Mechanismus ist effektiver?
2. **Welche Epitope?** - T-Zell (MHC-I/II) vs. B-Zell
3. **Wie Th17-Antwort induzieren?** - Kritisch für S. aureus Clearance
4. **Umgeht es Immune Imprinting?** - Kernhypothese testen

### Technisch

5. **Transduktionseffizienz in vivo?** - Biofilm, Gewebe
6. **Timing der Expression?** - Konstitutiv vs. induziert
7. **Stabilität des Konstrukts?** - Ohne Selektionsdruck
8. **Optimale Dosis?** - Partikel:Bakterien Ratio

### Anwendung

9. **Lokale vs. systemische Applikation?**
10. **Kombination mit Antibiotika?** - Synergie?
11. **Welche Indikation zuerst?** - PJI, Osteomyelitis, Wundinfektion?

---

## Nächste Schritte

### Sofort (Recherche)

- [ ] Detaillierte Epitop-Recherche (T-Zell, B-Zell für S. aureus)
- [ ] Vergleich Oberflächenpräsentation vs. Lyse vs. Sekretion
- [ ] Th17-Induktion durch bakterielle PAMPs - Mechanismen
- [ ] Bestehende in-vivo Phagen-Immunologie-Daten

### Kurzfristig (Konzept)

- [ ] Entscheidung: Präsentation ODER Lyse ODER beides?
- [ ] Antigen-Kassetten-Design
- [ ] Experimentalplan Phase 1 (in vitro)

### Mittelfristig (Experimentell)

- [ ] ePICI-Konstrukt klonieren
- [ ] Expression validieren
- [ ] DC-Aktivierung testen
- [ ] T-Zell/B-Zell Assays

---

## Schlüssel-Referenzen

### ePICI/PICI Technologie

1. **Ibarra-Chavez et al. 2020** - "Rebooting Synthetic Phage-Inducible Chromosomal Islands"
   - https://spj.science.org/doi/10.34133/2020/5783064

2. **Novick Lab** - SaPI antibacterial drones
   - Nature Biotechnology 2018

3. **Penades Lab 2025** - Capsid-forming PICIs

### S. aureus Immunologie

4. **IL-10 Suppression** - UC San Diego 2024
   - https://today.ucsd.edu/story/staphylococcus-aureus-thwarts-vaccines

5. **Immune Imprinting** - PMC3417391

### Phagen-Immunologie

6. **Phages as dual-action immunotherapeutics** - PNAS 2025
   - Phagen-Lyse → Langzeit-Immunität

---

## Kontakt/Kollaborationen (potentiell)

| Gruppe | Expertise | Institution |
|--------|-----------|-------------|
| José R. Penadés | PICI-Biologie | Imperial College London |
| Richard P. Novick | SaPI Therapeutics | NYU |
| Rodrigo Ibarra-Chavez | Synthetic PICI | - |

---

## Projekt-Metadaten

| Feld | Wert |
|------|------|
| **Projektname** | UNVEIL |
| **Vollständiger Name** | Universal ePICI-Vectored Epitope Immune Labeling |
| **Fokus** | Therapeutische Immununterstützung bei Infektions-Clearance |
| **Ziel-Pathogen** | S. aureus (initial), erweiterbar |
| **Stadium** | Konzeptphase / Recherche |
| **Erstellt** | April 2026 |
| **Spin-off von** | SHIELD-Projekt |

---

## Quick Start für neue Session

```
1. Lies dieses File (UNVEIL_Session_Restart.md)

2. Lies UNVEIL_Projektskizze.md für detaillierten Plan

3. Background-Files nach Bedarf:
   - background_ePICI_Grundlagen.md (PICI-Basics)
   - background_PICI_Aktivierung.md (ERP-Zyklus)
   - background_Rebooting_Paper.md (Hefe-Engineering)
   - background_Helferphagen.md (80α, Δcos)
   - background_S_aureus_Intrazellular.md (SCVs)
   - background_Biofilm_Resistenz.md (3-Wochen-Regel)

4. Offene Kernfragen:
   - Präsentation vs. Lyse als Mechanismus?
   - Welche Epitope priorisieren?
   - Wie Th17-Antwort sicherstellen?
```

---

*Session Restart File erstellt: April 2026*
*Projektordner: C:\Users\david\Desktop\Claude Recherchen\UNVEIL\*
