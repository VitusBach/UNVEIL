# UNVEIL Background: Rebooting Synthetic PICIs (Paper-Zusammenfassung)

## Bibliographische Daten

| Feld | Information |
|------|-------------|
| **Titel** | Rebooting Synthetic Phage-Inducible Chromosomal Islands: One Method to Forge Them All |
| **Autoren** | Rodrigo Ibarra-Chávez, Andreas F. Haag, Pedro Dorado-Morales, Iñigo Lasa, José R. Penadés |
| **Journal** | BioDesign Research |
| **Jahr** | 2020 |

### Zugang

- [PubMed Central (PMC)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10530653/)
- [Publisher](https://spj.science.org/doi/10.34133/2020/5783064)

---

## Methode: Hefe-basiertes "Rebooting"

### Workflow

```
1. PCR-Amplifikation der PICI-Fragmente
         │
         ▼
2. Assembly in Saccharomyces cerevisiae (YAC)
         │
         ▼
3. YAC-PICI Extraktion aus Hefe
         │
         ▼
4. Rebooting durch Transformation in Bakterien
```

### YAC-PICI Konstruktion

- **YAC** = Yeast Artificial Chromosome
- PICI-Fragmente mit überlappenden Sequenzen
- Homologe Rekombination in Hefe
- Resultat: YAC-PICI als zirkuläres Konstrukt

---

## Proof of Concept

### SaPIs aus *Staphylococcus aureus*

| Aspekt | Details |
|--------|---------|
| Konstrukte | Mehrere SaPI-Varianten |
| Validierung | Multiple simultane Mutationen |
| Helfer-Phagen | φ11, 80α |

### EcCICFT073 aus *Escherichia coli*

| Aspekt | Details |
|--------|---------|
| Assembly | 3 PCR-Fragmente |
| Transformation | Direkt in E. coli |
| Helfer-Phagen | λ, φ80 |

---

## CRISPR-Cas9 Anwendung

### Target: NDM-1 Gen

- Klinisch relevante Carbapenem-Resistenz
- Auf Plasmid kodiert

### Trick: Reine PICI-Partikel

**Lösung:** φ80 Δcos Mutante

| Merkmal | Wildtyp φ80 | φ80 Δcos |
|---------|-------------|----------|
| cos-Site | Vorhanden | Deletiert |
| Phagen-Verpackung | Ja | Nein |
| PICI-Verpackung | Ja | Ja |
| Lysat-Inhalt | Phagen + PICIs | **Nur PICIs** |

---

## Schlussfolgerungen

### Methodische Vorteile

| Aspekt | Konventionell | Hefe-Rebooting |
|--------|---------------|----------------|
| Geschwindigkeit | Langsam | **Schnell** |
| Mutationen | Einzeln | **Multiple simultan** |
| Universalität | Spezies-spezifisch | **Gram+ und Gram-** |

### Technische Errungenschaften

1. **Universelle Methode** für PICI-Engineering
2. **Schnelle Iteration** für Optimierung
3. **Reine PICI-Partikel** ohne Phagen-Kontamination möglich
4. **CRISPR-Cas9 Integration** validiert

---

## Relevanz für UNVEIL-Konzept

### Direkte Anwendbarkeit

1. **Engineering von ePICIs** mit Antigen-Kassetten
2. **Reine ePICI-Partikel** für sichere Anwendung (ohne Phagen)
3. **Schnelle Iteration** für Antigen-Optimierung

### Technische Möglichkeiten

| UNVEIL-Komponente | Umsetzung via Rebooting |
|-------------------|-------------------------|
| Antigen-Expression | Gen-Insertion am 3'-Ende |
| Sicherheit | φ Δcos für reine ePICI-Partikel |
| Multiplexing | Multiple Gene simultan |

---

## Quellen

1. Ibarra-Chávez R, et al. BioDesign Research. 2020;2020:5783064.
2. Tormo-Más MÁ, et al. Nature. 2010.
3. Quiles-Puchalt N, et al. Mol Microbiol. 2014.

---

*Für UNVEIL-Projekt kompiliert: April 2026*
