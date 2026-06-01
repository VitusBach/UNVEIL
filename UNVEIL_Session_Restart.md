# UNVEIL — Session Restart File

**Letztes Update:** Juni 2026 — DFG-Antrag-Phase

---

## Projektkurzform

**UNVEIL** — *Universal ePICI-Vectored Epitope Immune Labeling*

Engineered Phage-Inducible Chromosomal Islands (ePICIs) werden während aktiver bakterieller Infektion lokal appliziert, infizieren *S. aureus* in situ und exponieren immundominante Antigene im Kontext bakterieller PAMPs. Ziel: Th17-getriebene Immununterstützung zur Clearance komplizierter, biofilm- und intrazellulär persistierender Infektionen — **therapeutisch, NICHT prophylaktisch**.

**Primärindikation:** Prosthetic Joint Infection (PJI). DAIR-Erfolg bei MRSA-PJI nur 58 %, 2-Jahres-Überleben 29 % — riesiger Unmet Need.

---

## Konsortium

| Rolle | Person | Institution | DFG-Section | Status |
|---|---|---|---|---|
| **PI** | PD Dr. David Peterhoff | IMHR + Phage Center Regensburg, UKR | Hauptantragsteller | aktiv |
| **Co-Investigator Inland** | Prof. Dr. Martijn Riool | Experimentelle Unfallchirurgie, UKR | 4.5 | zugesagt |
| **Cooperation Partner Ausland** | Dr. Iñigo Lasa | Navarrabiomed/UPNA, Pamplona, ES | 4.6 + Letter of Cooperation | konzeptionell an Bord, Detail-WP noch abzustimmen |

**Arbeitsteilung:**
- **WP1 (Lasa):** ePICI-Backbone + 4 Antigen-Kassetten-Varianten
- **WP2 (Peterhoff):** Antigen-Konservierungsanalyse über > 1.000 klinische MRSA-Isolate (IMHR-Sammlung)
- **WP3 (Peterhoff):** Immunogenität in vitro (DC, T-Zell, B-Zell, OPA; Th17 priorisiert)
- **WP4 (Riool):** Galleria-Implantat-Pre-Screen → Maus-K-Wire-PJI-Modell
- **WP5 (Peterhoff/Riool):** Translation gegen klinische MRSA-Isolate, Vorbereitung FIH

---

## Aktueller Stand (Juni 2026)

**Phase:** DFG-Sachbeihilfe-Antrag in Vorbereitung (3 Jahre, ~677 k€ inkl. Programmpauschale).

**Antrag-Datei:** `Antrag_DFG_UNVEIL.md` (im Projektordner).
**Drafting-Format:** Markdown — finale Konversion in Word-DFG-Template (Arial 11 pt, 1.2 Zeilenabstand).

### Antrag-Bearbeitungsstatus v0.1

| Section | Status |
|---|---|
| Frontmatter / Outline / Seitenbudget | ✅ |
| Zusammenfassung DE + EN | ✅ Draft v0.1 — Review |
| Sec. 1 State of the art + Vorarbeiten | ✅ Draft v0.1 — Review (mit 27 Quellen, alle DOI/PMID-verifiziert) |
| Sec. 2 Objectives + WP-Plan | 🟡 Outline mit Hypothesen H1–H4 |
| Sec. 3 Publikationsliste | 🟡 Sec.1-Quellen vollständig |
| Sec. 4 Supplementary info | 🔴 Outline only |
| Sec. 5 Mittelantrag | 🔴 Outline only |
| Letters of Cooperation | 🔴 ausstehend |
| Word-Konversion DFG-Template | 🔴 letzte Iteration |

### Drei beim User offene Punkte (vor Section 2)
1. DFG-Antragshistorie — First-time-Antragsteller? (Sec. 4.3)
2. Anstellungsstatus — W2 unbefristet? (Sec. 4.2)
3. Abnahme Section 1 (Narrativ + Vorarbeiten-Darstellung)

---

## Warum dieses Projekt — Kernargumente

### Forschungslücke
**Niemand hat bisher ePICIs für therapeutische Immununterstützung eingesetzt.** ePICI-Plattform ist als Methodik etabliert (Diagnostik, CRISPR-Delivery, antibakterielle Drohnen), aber Immunaktivierung als therapeutisches Konzept ist unbearbeitet.

### Vakzin-Failure-Modes, die UNVEIL umgeht
| Mechanismus | Klassische Vakzine | UNVEIL |
|---|---|---|
| **IL-10-Suppression** | Antikörper funktional entwertet im Milieu | Akuter PAMP-Burst überschreibt IL-10 lokal |
| **Fehlende Th17-Antwort** | Alum → Th2-Bias; 9/10 IL-17A-null V710-Empfänger gestorben (PMC4514053) | PG/LTA/CpG-DNA bei Lyse → TLR2/9 + NOD2 → Th17 |
| **Immune Imprinting** | Erwachsene nicht-naiv; Boost = nicht-protektive AK verstärkt | Kryptische intrazelluläre Antigene durch Lyse exponiert |
| **Falsche Antigen-Form** | Lösliches Protein ohne Kontext | Antigen IM bakteriellen Milieu — richtiges Pattern Recognition |

### USPs des UNVEIL-Konsortiums
1. **>1.000 klinische MRSA-Sammlung** am IMHR (kein Wettbewerber repliziert das)
2. **Etabliertes ePICI-Engineering** bei Lasa (Co-Autor Rebooting-Methode)
3. **Validierte Galleria + Maus-PJI-Modelle** bei Riool (incl. publizierte Phagen+Antibiotika-Kombi)
4. **Lokale klinische Anbindung** UKR Unfallchirurgie (direkte Translation Richtung FIH bei PJI)
5. **PI-Profil:** Vakzinologie/Antigen-Engineering (HIV, SARS-CoV-2) + lokale Phagentherapie-Erfahrung (Front Med 2024)

---

## Dokumentstruktur

| Datei | Zweck |
|---|---|
| **UNVEIL_Session_Restart.md** | Dieses File — aktuellster Stand & Restart-Pointer |
| **Antrag_DFG_UNVEIL.md** | DFG-Sachbeihilfe-Antrag-Draft (zentraler Output) |
| **UNVEIL_Projektskizze.md** | Ursprüngliche Konzept-Skizze (Hintergrund) |
| **UNVEIL_Presentation.pptx** | 5-min Projektpräsentation |
| **background_ePICI_Grundlagen.md** | PICI-Biologie, Helferphagen |
| **background_PICI_Aktivierung.md** | ERP-Zyklus, Transfereffizienz |
| **background_Rebooting_Paper.md** | Hefe-Engineering (Ibarra-Chávez 2020) |
| **background_Helferphagen.md** | 80α, φ11, Stl-Inducer |
| **background_S_aureus_Intrazellular.md** | SCVs, Trojanisches Pferd |
| **background_Biofilm_Resistenz.md** | 3-Wochen-Schwelle |

GitHub-Repo: https://github.com/Vitusbach/UNVEIL

---

## Schlüsselquellen (alle DOI/PMID-verifiziert)

### ePICI/PICI-Technologie
- Ibarra-Chávez, Lasa, Penadés et al. *BioDesign Research* 2020 — Hefe-Rebooting. doi:10.34133/2020/5783064
- Penadés et al. *Cell* 2025 — Chimeric cf-PICI particles cross species. S0092-8674(25)00974-2
- Ibarra-Chávez et al. *Adv Sci* 2023 — ePICI-Diagnostik. doi:10.1002/advs.202301643

### Phagen-Immunologie (UNVEIL-Konzeptkern)
- Hetta HF et al. *PNAS* 2025;122(22):e2423286122 — Phage-induced protection, lytisch-abhängig. doi:10.1073/pnas.2423286122

### S. aureus Vakzin-Failure
- Fowler VG et al. *JAMA* 2013 — V710-Trial. PMID 23549582
- McNeely TB et al. *Hum Vaccin Immunother* 2014 — V710-Mortality-Analyse. doi:10.4161/hv.34407
- Tande & Patel *Clin Microbiol Rev* 2014 — PJI-Standard-Review

### Eigene Vorarbeiten (Peterhoff, projekt-relevant)
- *Nat Chem Biol* 2019 — Modulare Lanthipeptide nanoliter scale. doi:10.1038/s41589-019-0250-5
- *Front Med* 2024 — Lokale Phagentherapie fracture-related infection. doi:10.3389/fmed.2024.1428432
- *npj Vaccines* 2023 — HIV-1 Env-Trimer
- *Eur J Pharm Biopharm* 2023 — Silica-NP SARS-CoV-2 Vakzin

### Konsortialpartner-Riool
- Mannala/Riool *Bone Joint Res* 2024 — Phagen+Gentamicin Galleria. PMID 39089687
- Mannala/Riool *J Orthop Res* 2020/2023 — Galleria-Implantat-Modelle

---

## Quick Start für neue Session

```
1. Lies dieses File (UNVEIL_Session_Restart.md)
2. Auto-Memory-Bank wird automatisch geladen aus
   ~/.claude/projects/-home-david-Schreibtisch-Claude-Recherchen-UNVEIL/memory/
3. Aktiver Output: Antrag_DFG_UNVEIL.md (Status v0.1)
4. Nächster Schritt: Section 2 (Objectives & WP-Plan) detailliert ausarbeiten,
   sobald User die drei offenen Punkte beantwortet:
   (a) DFG-Antragshistorie, (b) Anstellungsstatus, (c) Section-1-Abnahme
5. GitHub-Sync: git pull, am Ende der Session committen + pushen
```

---

## Projekt-Metadaten

| Feld | Wert |
|---|---|
| Projektname | UNVEIL |
| Vollständiger Name | Universal ePICI-Vectored Epitope Immune Labeling |
| Stadium | DFG-Antrag in Vorbereitung (Sachbeihilfe, 36 Mo., ~677 k€) |
| Konzeptphase abgeschlossen | April 2026 |
| Antrag-Drafting begonnen | Mai 2026 |
| Zielindikation | PJI / Osteomyelitis (MRSA primär) |
| Spin-off von | SHIELD-Projekt |
| GitHub | github.com/Vitusbach/UNVEIL |
