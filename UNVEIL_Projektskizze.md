# UNVEIL Projektskizze: ePICI-basierte Immununterstützung bei Infektions-Clearance

## Executive Summary

Dieses Dokument skizziert ein innovatives Konzept zur Nutzung von **engineered Phage-Inducible Chromosomal Islands (ePICIs)** für die gezielte Exposition bakterieller Antigene während aktiver Infektionen. Ziel ist die **Unterstützung der immunologischen Clearance komplizierter Infektionen** - insbesondere bei Biofilmen, intrazellulären Persistern und Antibiotika-resistenten Erregern.

**Kernhypothese:** ePICIs können so engineered werden, dass sie bei Infektion von Zielbakterien T-Zell- und B-Zell-Epitope exprimieren und exponieren, wodurch das Immunsystem zur effektiven Clearance aktiviert wird - auch bei etablierten, schwer behandelbaren Infektionen.

**Abgrenzung:** UNVEIL ist KEINE Vakzin-Plattform für prophylaktische Immunisierung, sondern ein **therapeutischer Ansatz** zur Immununterstützung bei aktiver Infektion.

---

## 1. Stand der Forschung

### 1.1 Was existiert bereits?

#### ePICI-Technologie (etabliert)

| Anwendung | Status | Referenz |
|-----------|--------|----------|
| **CRISPR-Cas9 Delivery** | Proof-of-Concept | Novick Lab, Nature Biotechnology 2018 |
| **Antibakterielle Drohnen** | Präklinisch (Maus) | 10:1 Partikel:Bakterien verhindert Abszessbildung |
| **Diagnostische Biosensoren** | Validiert | 50 CFU/ml Detektionssensitivität |
| **Hefe-basiertes Rebooting** | Etabliert | Ibarra-Chavez et al. 2020 |
| **Δcos Helferphagen** | Verfügbar | Reine PICI-Partikel ohne Phagen |

#### Phagen-Immunologie (neuere Erkenntnisse)

| Beobachtung | Quelle | Relevanz für UNVEIL |
|-------------|--------|---------------------|
| Phagen-Lyse induziert Langzeit-Immunität | PNAS 2025 | **Lysierte Bakterien = Immunstimulation** |
| Bakterielle DNA aktiviert cGAS-STING | Multiple | Intrinsischer Adjuvans-Effekt |
| Peptidoglykan → Th17-Induktion | Immunologie-Literatur | Kritisch für S. aureus Clearance |

### 1.2 Die Forschungslücke

**NIEMAND hat bisher ePICIs für therapeutische Immununterstützung eingesetzt!**

| Aspekt | Phagen-Therapie | Vakzine | **UNVEIL-Konzept** |
|--------|-----------------|---------|-------------------|
| Ziel | Bakterien töten | Prophylaxe | **Clearance-Unterstützung** |
| Timing | Während Infektion | Vor Infektion | **Während Infektion** |
| Mechanismus | Lyse | Antikörper/T-Zellen | **Antigen-Exposition + Lyse** |
| Target | Planktische Bakterien | Naive Immunzellen | **Biofilme, SCVs, Persister** |

### 1.3 Warum bestehende Therapien bei komplizierten Infektionen versagen

#### Das Problem: Etablierte Infektionen

| Infektionstyp | Herausforderung | Therapieversagen |
|---------------|-----------------|------------------|
| **Biofilm (>3 Wochen)** | EPS-Matrix, Persister | 10-1000x Antibiotikaresistenz |
| **Intrazelluläre SCVs** | Versteckt in Wirtszellen | Antibiotika erreichen sie nicht |
| **Prosthetic Joint Infection** | Implantat-assoziiert | DAIR-Erfolgsrate <40% nach 3 Wochen |
| **Chronische Osteomyelitis** | Knochensequester | Rezidivrate >30% |

#### Warum S. aureus Vakzine gescheitert sind

| Grund | Mechanismus | UNVEIL-Vorteil |
|-------|-------------|----------------|
| **IL-10 Suppression** | S. aureus induziert IL-10 → Antikörper inaktiviert | In-situ-Lyse aktiviert andere Immunwege |
| **Immune Imprinting** | Nicht-protektive Antikörper durch Erstexposition | Kryptische Antigene durch Lyse exponiert |
| **Fehlende Th17-Antwort** | Nur Antikörper, keine T-Zell-Immunität | Bakterielle PAMPs induzieren Th17 |
| **Falscher Kontext** | Prophylaktisch vs. therapeutisch | **Immunstimulation im Infektionskontext** |

---

## 2. Das UNVEIL-Konzept

### 2.1 Grundprinzip: Immununterstützung bei aktiver Infektion

```
┌─────────────────────────────────────────────────────────────────────┐
│              UNVEIL: IMMUNUNTERSTÜTZUNG BEI CLEARANCE              │
├─────────────────────────────────────────────────────────────────────┤
│                                                                      │
│  AUSGANGSLAGE: KOMPLIZIERTE INFEKTION                               │
│  ─────────────────────────────────────                              │
│  • Biofilm etabliert (>3 Wochen)                                    │
│  • Intrazelluläre Persister (SCVs)                                  │
│  • Antibiotika-Versagen                                             │
│  • Immunsystem "erschöpft" oder evadiert                           │
│              │                                                       │
│              ▼                                                       │
│  1. ePICI-APPLIKATION                                               │
│     Helferphagen (Δcos) + ePICI-Partikel lokal appliziert          │
│              │                                                       │
│              ▼                                                       │
│  2. TRANSDUKTION DER PATHOGENEN                                     │
│     ePICI infiziert S. aureus im Biofilm/Gewebe                    │
│     • Auch SCVs werden erreicht                                     │
│     • Integration → Antigen-Expression                              │
│              │                                                       │
│              ▼                                                       │
│  3. ANTIGEN-EXPOSITION                                              │
│     Option A: Oberflächenpräsentation → "Markierung"               │
│     Option B: Sekretion → Lösliche Antigene                        │
│     Option C: Lyse → Massive Freisetzung + PAMPs                   │
│              │                                                       │
│              ▼                                                       │
│  4. REAKTIVIERUNG DES IMMUNSYSTEMS                                  │
│     • Kryptische Antigene exponiert (Immune Imprinting umgangen)   │
│     • PAMPs (PG, DNA) → Th17-Induktion                             │
│     • DC-Aktivierung → T-Zell Priming                              │
│     • B-Zell-Aktivierung → opsonisierende Antikörper               │
│              │                                                       │
│              ▼                                                       │
│  5. IMMUNOLOGISCHE CLEARANCE                                        │
│     • Opsonophagozytose der markierten Bakterien                   │
│     • CTL-Killing infizierter Wirtszellen (SCVs!)                  │
│     • Neutrophilen-Rekrutierung (IL-17) → Biofilm-Angriff         │
│              │                                                       │
│              ▼                                                       │
│  ERGEBNIS: ERADIKATION + SCHUTZ VOR REZIDIV                        │
│                                                                      │
└─────────────────────────────────────────────────────────────────────┘
```

### 2.2 Kernunterschied zu Vakzinen

| Aspekt | Konventionelle Vakzine | UNVEIL |
|--------|------------------------|--------|
| **Ziel** | Prophylaxe | **Clearance aktiver Infektion** |
| **Timing** | Vor Exposition | **Während Infektion** |
| **Kontext** | Isolierte Antigene | **Antigene im bakteriellen Milieu** |
| **Adjuvans** | Extern zugegeben | **Intrinsisch (PAMPs bei Lyse)** |
| **Immunstatus** | Naiv | **Bereits exponiert (oft mit Imprinting)** |
| **Target** | Prävention | **Etablierte Biofilme, SCVs, Persister** |

### 2.3 Warum UNVEIL bei komplizierten Infektionen funktionieren könnte

#### Problem 1: Biofilm-assoziierte Resistenz

| UNVEIL-Mechanismus | Wirkung |
|--------------------|---------|
| Phagen penetrieren Biofilm | ePICI erreicht Biofilm-Bakterien |
| Antigen-Expression in situ | Immunsystem "sieht" Biofilm-Bakterien |
| Th17-Induktion | Neutrophilen-Infiltration in Biofilm |
| Opsonisierende Antikörper | Phagozytose der markierten Bakterien |

#### Problem 2: Intrazelluläre Persister (SCVs)

| UNVEIL-Mechanismus | Wirkung |
|--------------------|---------|
| SCVs können re-aktivieren | Dann auch von ePICI infizierbar |
| MHC-I Epitope exprimiert | CTL erkennen infizierte Wirtszellen |
| Wirtszellen werden eliminiert | SCV-Reservoir zerstört |

#### Problem 3: Immune Imprinting

| UNVEIL-Mechanismus | Wirkung |
|--------------------|---------|
| Phagen-Lyse exponiert intrazelluläre Antigene | Neue Epitope, keine existierenden Antikörper |
| "Kryptische" Antigene | Imprinting umgangen |
| Anderer Immunkontext (Th17) | Nicht nur Antikörper |

---

## 3. Technische Komponenten

### 3.1 ePICI-Backbone (SaPI-basiert)

| Element | Funktion | Status |
|---------|----------|--------|
| **attL/attR** | Integration/Exzision | Etabliert |
| **int/xis** | Integrase/Excisionase | Etabliert |
| **ori** | PICI-Replikation | Etabliert |
| **cos/pac** | Verpackungssignal | Optimiert |
| **stl** | Master-Repressor | Für Kontrolle |

### 3.2 Antigen-Expressionsstrategien

```
┌─────────────────────────────────────────────────────────────────────┐
│          UNVEIL: ANTIGEN-EXPOSITIONSSTRATEGIEN                     │
├─────────────────────────────────────────────────────────────────────┤
│                                                                      │
│  STRATEGIE A: OBERFLÄCHEN-DISPLAY ("Markierung")                   │
│  ───────────────────────────────────────────────                   │
│  • Fusion mit Sortase-Substrat (LPXTG)                             │
│  • Antigen auf Bakterienoberfläche verankert                       │
│  • B-Zell-Epitope direkt exponiert                                 │
│  • Opsonisierung → Phagozytose                                     │
│                                                                      │
│  STRATEGIE B: SEKRETION                                             │
│  ──────────────────────                                            │
│  • Sec-Signalpeptid für Export                                     │
│  • Lösliche Antigene im Infektionsmilieu                          │
│  • DC-Aufnahme und Präsentation                                    │
│  • T-Zell- und B-Zell-Aktivierung                                  │
│                                                                      │
│  STRATEGIE C: LYSE-GEKOPPELT                                       │
│  ─────────────────────────                                         │
│  • Expression bei Phagen-Lyse induziert                            │
│  • Massive Freisetzung aller Antigene                              │
│  • + Bakterielle PAMPs (PG, DNA, Lipoteichonsäure)                │
│  • Stärkste Immunstimulation, aber Bakterien tot                  │
│                                                                      │
│  STRATEGIE D: HYBRID (empfohlen für UNVEIL)                        │
│  ──────────────────────────────────────────                        │
│  • Oberflächen-Display für Markierung                              │
│  • + Lyse-induzierte Expression für Immunboost                     │
│  • Optimale Kombination aus Markierung und Stimulation            │
│                                                                      │
└─────────────────────────────────────────────────────────────────────┘
```

### 3.3 Offene Kernfrage: Präsentation vs. Lyse

| Strategie | Vorteile | Nachteile | UNVEIL-Relevanz |
|-----------|----------|-----------|-----------------|
| **Oberfläche** | Lebende Bakterien markiert, kontinuierlich | Schwächere Immunstimulation | Gut für Opsonisierung |
| **Sekretion** | DC-Aufnahme, flexibel | Verdünnung im Gewebe | Moderat |
| **Lyse** | Stärkste Immunantwort, PAMPs | Bakterien sterben, einmalig | Gut für Th17 |
| **Hybrid** | Kombiniert Vorteile | Komplexer | **Optimum für UNVEIL** |

**Entscheidung benötigt:** Experimentelle Vergleichsstudie in Phase 1

### 3.4 Antigen-Auswahl für S. aureus

#### Priorität 1: Th17-induzierende Antigene (kritisch!)

| Antigen | Funktion | Rationale |
|---------|----------|-----------|
| **MntC** | Mangan-Transporter | Nachgewiesene Th17-Induktion |
| **FhuD2** | Eisen-Siderophor | Th17 + essentiell für S. aureus |

#### Priorität 2: Virulenzfaktoren (Opsonisierung)

| Antigen | Funktion | B-Zell-Epitope |
|---------|----------|----------------|
| **ClfA** | Fibrinogen-Bindung | Gut charakterisiert |
| **IsdB** | Eisenaufnahme | Gut charakterisiert |
| **Hla (detox)** | α-Hämolysin | Neutralisierend |

#### Priorität 3: T-Zell-Epitope (CTL für SCV-Clearance)

| Antigen | MHC-I Epitope | Ziel |
|---------|---------------|------|
| **Housekeeping-Proteine** | Konserviert | Infizierte Wirtszellen |
| **SCV-spezifische Proteine** | Zu identifizieren | SCVs direkt |

---

## 4. Indikationen und Anwendungsszenarien

### 4.1 Primäre Indikation: Prosthetic Joint Infection (PJI)

| Aspekt | Details |
|--------|---------|
| **Problem** | DAIR-Erfolgsrate <40% nach 3 Wochen Symptomen |
| **Therapiestandard** | Debridement + Antibiotika ± Implantatwechsel |
| **UNVEIL-Einsatz** | Adjuvant zu DAIR |
| **Applikation** | Lokal während Operation |
| **Ziel** | Immunologische Clearance von Residualbakterien |

### 4.2 Weitere Indikationen

| Indikation | UNVEIL-Strategie | Applikation |
|------------|------------------|-------------|
| **Chronische Osteomyelitis** | Adjuvant zu Debridement | Lokal |
| **Diabetische Fußinfektion** | Vor/nach Amputation | Topisch |
| **Chronische Wundinfektion** | Kombiniert mit Honig/Hydrogel | Topisch |
| **Rezidivierende Furunkulose** | Dekolonisation + Clearance | Topisch/nasal |
| **Biofilm auf Kathetern** | Vor Katheterentfernung | Lokal |

### 4.3 Kombinationstherapien

```
┌─────────────────────────────────────────────────────────────────────┐
│              UNVEIL: KOMBINATIONSSTRATEGIEN                         │
├─────────────────────────────────────────────────────────────────────┤
│                                                                      │
│  KOMBINATION 1: UNVEIL + DEBRIDEMENT                                │
│  ────────────────────────────────────                               │
│  1. Chirurgisches Debridement (Biofilm-Reduktion)                  │
│  2. ePICI-Applikation lokal                                        │
│  3. Immunsystem eliminiert Residualbakterien                       │
│                                                                      │
│  KOMBINATION 2: UNVEIL + ANTIBIOTIKA                                │
│  ─────────────────────────────────────                              │
│  • Synergie analog Phagen-Antibiotika-Kombination                  │
│  • ePICI schwächt Bakterien, Antibiotika töten                     │
│  • Oder: Antibiotika reduzieren Last, ePICI aktiviert Immunsystem  │
│                                                                      │
│  KOMBINATION 3: UNVEIL + HONIG (SHIELD-Synergie)                   │
│  ───────────────────────────────────────────────                   │
│  • Honig: Biofilm-Disruption, anti-SCV, antimikrobiell            │
│  • ePICI: Immunstimulation, Antigen-Exposition                     │
│  • Synergistisch bei chronischen Wundinfektionen                  │
│                                                                      │
│  KOMBINATION 4: UNVEIL + CHECKPOINT-BLOCKADE                       │
│  ─────────────────────────────────────────────                     │
│  • Bei chronischen Infektionen: T-Zell-Exhaustion                  │
│  • Anti-PD-1/PD-L1 reaktiviert erschöpfte T-Zellen                │
│  • ePICI liefert Antigene für reaktivierte T-Zellen               │
│                                                                      │
└─────────────────────────────────────────────────────────────────────┘
```

---

## 5. Experimenteller Plan

### Phase 1: Konstrukt-Entwicklung und Mechanismus-Klärung

#### 1.1 ePICI-Backbone Optimierung

| Schritt | Methode | Endpunkt |
|---------|---------|----------|
| Backbone-Auswahl | Vergleich SaPIbov1, SaPI1 | Transfereffizienz |
| Hefe-Rebooting | Ibarra-Chavez Protokoll | Modulares System |
| Δcos Helferphagen | 80α Δcos | Reine ePICI-Partikel |

#### 1.2 Antigen-Strategie-Vergleich (KRITISCH!)

| Konstrukt | Strategie | Readout |
|-----------|-----------|---------|
| **ePICI-Surface** | Oberflächen-Display (ClfA-Fusion) | Opsonisierung |
| **ePICI-Secrete** | Sekretion (Sec-Signal + Antigen) | DC-Aufnahme |
| **ePICI-Lyse** | Lyse-induzierte Expression | Th17-Induktion |
| **ePICI-Hybrid** | Kombination | Alle Readouts |

**Ziel:** Entscheidung für optimale Strategie basierend auf immunologischen Daten

#### 1.3 Epitop-Auswahl

| Schritt | Methode | Output |
|---------|---------|--------|
| In-silico Prädiktion | NetMHCpan, IEDB | Kandidaten-Epitope |
| Konservierungs-Analyse | BLAST gegen S. aureus Stämme | Konservierte Epitope |
| Humanhomolog-Screening | BLAST gegen Humanproteom | Keine Autoimmunität |

### Phase 2: Immunologische Charakterisierung (in vitro)

#### 2.1 Dendritische Zell-Aktivierung

| Assay | Readout | Fragestellung |
|-------|---------|---------------|
| DC-Aufnahme | Fluoreszenzmikroskopie | Werden Antigene internalisiert? |
| Reifungsmarker | CD80, CD86, CD83 (FACS) | Werden DCs aktiviert? |
| Zytokin-Profil | IL-12, IL-6, IL-23 (ELISA) | Th17-polarisierend? |

#### 2.2 T-Zell-Antwort

| Assay | Readout | Fragestellung |
|-------|---------|---------------|
| T-Zell-Proliferation | CFSE | Antigen-spezifisch? |
| IFN-γ ELISpot | SFU | CTL-Aktivierung? |
| **IL-17 ELISA** | Konzentration | **Th17-Induktion? (kritisch!)** |
| Zytotoxizität | LDH-Release | Killing infizierter Zellen? |

#### 2.3 B-Zell/Antikörper-Antwort

| Assay | Readout | Fragestellung |
|-------|---------|---------------|
| Antikörper-Titer | ELISA | Humorale Antwort? |
| **Opsonophagozytose (OPA)** | % Killing | **Funktionelle Antikörper?** |
| Biofilm-Penetration | Konfokalmikroskopie | Zugang zu Biofilm? |

### Phase 3: In-vivo Proof-of-Concept

#### 3.1 Mausmodelle (fokussiert auf komplizierte Infektionen)

| Modell | Relevanz für UNVEIL | Endpunkte |
|--------|---------------------|-----------|
| **Etablierter Biofilm (3-Wochen Katheter)** | Kernindikation | CFU, Rekolonisierung |
| **Chronischer Hautabszess** | Verzögerte Clearance | CFU, Histologie |
| **PJI-Modell (Titanimplantat)** | Klinische Relevanz | CFU, Biofilm-Bildung |

#### 3.2 Studiendesign: Therapeutische Anwendung

```
┌─────────────────────────────────────────────────────────────────────┐
│          UNVEIL: PROOF-OF-CONCEPT STUDIENDESIGN                    │
├─────────────────────────────────────────────────────────────────────┤
│                                                                      │
│  Tag 0        Tag 21          Tag 24       Tag 28       Tag 35     │
│   │            │               │            │            │          │
│   ▼            ▼               ▼            ▼            ▼          │
│  ┌───┐        ┌───┐           ┌───┐        ┌───┐        ┌───┐      │
│  │Inf│        │Bio│           │ePICI│      │Blut│       │Term│     │
│  └───┘        └───┘           └───┘        └───┘        └───┘      │
│                                                                      │
│  S. aureus    Biofilm         ePICI        Serum        Organ-     │
│  Infektion    etabliert       Behandlung   Antikörper   entnahme   │
│               (3 Wochen!)                  T-Zell FACS  CFU, Histo │
│                                                                      │
│  KRITISCH: Infektion wird 21 Tage ETABLIERT vor Behandlung!        │
│  → Simuliert klinische Realität (späte Diagnose)                   │
│                                                                      │
│  Gruppen:                                                           │
│  ─────────                                                          │
│  1. Etablierte Infektion + PBS (Negativ-Kontrolle)                 │
│  2. Etablierte Infektion + ePICI-Surface                           │
│  3. Etablierte Infektion + ePICI-Lyse                              │
│  4. Etablierte Infektion + ePICI-Hybrid                            │
│  5. Etablierte Infektion + ePICI + Antibiotikum                    │
│  6. Etablierte Infektion + nur Phage (ohne Antigen-Kassette)       │
│                                                                      │
│  Primärer Endpunkt: CFU-Reduktion Tag 35 vs. Tag 21                │
│  Sekundäre Endpunkte: Th17-Zellen, Antikörper, Rezidivrate        │
│                                                                      │
└─────────────────────────────────────────────────────────────────────┘
```

#### 3.3 Langzeit-Clearance und Rezidiv-Schutz

| Zeitpunkt | Test | Erwartung |
|-----------|------|-----------|
| Tag 35 | CFU | Signifikante Reduktion vs. Kontrolle |
| Tag 60 | Re-Inokulation | Reduzierte Etablierung bei behandelten Tieren |
| Tag 90 | Memory T-Zellen | Th17-Memory nachweisbar |

### Phase 4: Optimierung für klinische Translation

#### 4.1 Formulierungsentwicklung

| Formulierung | Indikation | Eigenschaften |
|--------------|------------|---------------|
| **Injizierbares Gel (GelMA)** | PJI, Osteomyelitis | Lokale Freisetzung |
| **Wundauflage + ePICI** | Chronische Wunden | Kombiniert mit Honig |
| **Lyophilisat** | Alle | Lagerungsstabilität |

#### 4.2 Dosierung und Timing

| Parameter | Zu klären | Methode |
|-----------|-----------|---------|
| Optimale Partikel:Bakterien Ratio | 1:1 bis 100:1 | Dosisfindungsstudie |
| Einmal- vs. Mehrfachgabe | Immunkinetik | Time-course Studie |
| Timing relativ zu Debridement | Vor/während/nach | Vergleichsstudie |

---

## 6. Risiken und Mitigationsstrategien

### 6.1 Wissenschaftliche Risiken

| Risiko | Wahrscheinlichkeit | Impact | Mitigation |
|--------|-------------------|--------|------------|
| Geringe Transduktion in etabliertem Biofilm | Mittel | Hoch | Biofilm-penetrierende Formulierung |
| Keine Th17-Induktion | Mittel | Hoch | PAMPs verstärken, Adjuvans |
| Immunantwort nicht clearance-effektiv | Mittel | Hoch | Epitop-Optimierung, Kombinationstherapie |
| Immune Imprinting nicht überwindbar | Mittel | Mittel | Kryptische Epitope fokussieren |

### 6.2 Technische Risiken

| Risiko | Wahrscheinlichkeit | Impact | Mitigation |
|--------|-------------------|--------|------------|
| ePICI-Instabilität nach Integration | Mittel | Mittel | Selektionsmarker (optional) |
| Unzureichende Antigen-Expression | Mittel | Mittel | Promotor-Screening |
| Schwierige GMP-Produktion | Mittel | Mittel | Frühe CMO-Einbindung |

### 6.3 Sicherheitsrisiken

| Risiko | Wahrscheinlichkeit | Impact | Mitigation |
|--------|-------------------|--------|------------|
| Überschießende Inflammation | Niedrig | Hoch | Dosisoptimierung, lokale Anwendung |
| Autoimmunität | Sehr niedrig | Hoch | Bioinformatisches Humanhomolog-Screening |
| Horizontal gene transfer | Sehr niedrig | Mittel | Minimales Konstrukt, essentielle Gene entfernt |

---

## 7. Unique Selling Points von UNVEIL

### 7.1 Abgrenzung zu existierenden Ansätzen

| Ansatz | Fokus | UNVEIL-Unterschied |
|--------|-------|-------------------|
| Prophylaktische Vakzine | Naives Immunsystem | **Therapeutisch bei aktiver Infektion** |
| Phagen-Therapie | Bakterienabtötung | **Immunaktivierung zusätzlich** |
| Antibiotika | Planktische Bakterien | **Biofilm und SCVs adressiert** |
| CRISPR-Phagen | Resistenzgene eliminieren | **Clearance durch Immunsystem** |

### 7.2 Innovation

1. **Erste ePICI-basierte Immuntherapie** - völliges Neuland
2. **Therapeutische Immununterstützung** bei etablierter Infektion
3. **Targeting von Biofilmen und SCVs** durch Immunsystem
4. **Intrinsischer Adjuvans-Effekt** durch bakterielle PAMPs
5. **Kombinierbar** mit Standardtherapien (Debridement, Antibiotika)

### 7.3 Klinischer Bedarf

| Indikation | Unmet Need | UNVEIL-Potenzial |
|------------|------------|------------------|
| PJI (>3 Wochen) | 60% Therapieversagen | Adjuvant zu DAIR |
| Rezidivierende Osteomyelitis | 30% Rezidivrate | Immunologische Clearance |
| Diabetisches Fußsyndrom | Amputationsrisiko | Frühe Intervention |

---

## 8. Ressourcenbedarf

### 8.1 Personal (Phase 1-3)

| Rolle | FTE | Expertise |
|-------|-----|-----------|
| Projektleiter | 1 | Infektiologie/Immunologie |
| Molekularbiologe | 1.5 | PICI-Engineering |
| Immunologe | 1 | T-Zell/B-Zell Assays, Th17 |
| Tierexperimentator | 0.5 | Biofilm-/Infektionsmodelle |

### 8.2 Infrastruktur

- BSL-2 Labor (S. aureus)
- Flow Cytometry
- Tierhaltung (SPF, Infektionsmodelle)
- Phagen-Produktion (Fermentation)

### 8.3 Budget-Schätzung

| Phase | Schwerpunkt | Geschätzte Kosten |
|-------|-------------|-------------------|
| **Phase 1** | Konstrukt, Mechanismus | 300-400k€ |
| **Phase 2** | In-vitro Immunologie | 200-300k€ |
| **Phase 3** | In-vivo PoC | 300-400k€ |
| **Gesamt (PoC)** | | **800k - 1.1M€** |

---

## 9. Offene Forschungsfragen

### Mechanistisch (Priorität 1)

1. **Oberflächen-Display vs. Lyse vs. Hybrid** - welche Strategie ist optimal?
2. **Welche Epitope** - T-Zell (MHC-I/II) vs. B-Zell?
3. **Wie zuverlässig Th17 induzieren** - kritisch für S. aureus Clearance!
4. **Umgeht UNVEIL Immune Imprinting?** - Kernhypothese

### Technisch (Priorität 2)

5. **Transduktionseffizienz in etabliertem Biofilm?**
6. **Timing: vor/während/nach Debridement?**
7. **Stabilität des Konstrukts ohne Selektion?**
8. **Optimale Partikel-Dosis?**

### Klinisch-translational (Priorität 3)

9. **Welche Indikation zuerst?** - PJI, Osteomyelitis, Wunde?
10. **Kombination mit welchem Antibiotikum?**
11. **Lokale vs. systemische Applikation?**

---

## 10. Nächste Schritte

### Sofort (Recherche)

- [ ] Detaillierte Th17-induzierende Epitope für S. aureus identifizieren
- [ ] Etablierte Biofilm-Mausmodelle recherchieren (>3 Wochen)
- [ ] Bestehende Phagen-Biofilm-Penetrationsdaten sammeln
- [ ] Vergleich Oberflächen-Display vs. Lyse-Systeme (Literatur)

### Kurzfristig (Konzept)

- [ ] Entscheidung: Fokus auf Oberfläche ODER Lyse ODER beides?
- [ ] Antigen-Kassetten-Design finalisieren
- [ ] Experimentalplan Phase 1 detaillieren

### Mittelfristig (Experimentell)

- [ ] ePICI-Konstrukt klonieren (Hefe-Rebooting)
- [ ] Expression validieren
- [ ] Erste DC-Aktivierungs-Assays
- [ ] In-vitro Th17-Induktion testen

---

## Quellen

### ePICI/PICI Technologie
1. [Ibarra-Chavez et al. 2020 - Rebooting Synthetic PICIs](https://spj.science.org/doi/10.34133/2020/5783064)
2. [Novick Lab - SaPI antibacterial drones](https://www.nature.com/articles/nbt.4002)
3. [Penades Lab - Capsid-forming PICIs 2025](https://www.nature.com/articles/s41564-024-01905-5)

### S. aureus Immunevasion und Vakzin-Versagen
4. [IL-10 suppression discovery - UC San Diego 2024](https://today.ucsd.edu/story/staphylococcus-aureus-thwarts-vaccines)
5. [Immune imprinting in S. aureus - PMC3417391](https://pmc.ncbi.nlm.nih.gov/articles/PMC3417391/)
6. [Th17 and S. aureus clearance - Nature Reviews](https://www.nature.com/nri/)

### Biofilm und komplizierte Infektionen
7. [Biofilm maturation and resistance - PMC4187959](https://pmc.ncbi.nlm.nih.gov/articles/PMC4187959/)
8. [DAIR timing - JBJS](https://journals.lww.com/jbjsjournal/)
9. [Intracellular S. aureus - Nature Communications](https://www.nature.com/articles/s41467-020-15966-7)

### Phagen-Immunologie
10. [Phages as dual-action immunotherapeutics - PNAS 2025](https://www.pnas.org/doi/10.1073/pnas.2423286122)

---

*UNVEIL Projektskizze erstellt: April 2026*
*Projektordner: C:\Users\david\Desktop\Claude Recherchen\UNVEIL\*
