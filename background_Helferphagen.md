# UNVEIL Background: Helferphagen und Stl-Inducer

## 1. Bekannte Helferphagen

### Für S. aureus SaPIs

| Phage | Mobilisiert | Besonderheit |
|-------|-------------|--------------|
| **80α** | Alle getesteten SaPIs | "Universeller" Helfer |
| **φ11** | Klasse I SaPIs | Gut charakterisiert |
| **φ12** | Klasse II SaPIs | Gut charakterisiert |
| **φNM1** | SaPIbov1 | dUTPase als Inducer |

### Für E. coli PICIs

| Phage | Mobilisiert |
|-------|-------------|
| **λ (Lambda)** | EcCI-Elemente |
| **φ80** | EcCICFT073 |

---

## 2. Phagen-Spezifität

**Nicht alle Phagen sind Helfer!**

Der **Stl-Repressor** bestimmt, welche Phagen induzieren können.

---

## 3. Bekannte Stl-Inducer-Proteine

| SaPI | Inducer-Protein | Phagen |
|------|-----------------|--------|
| SaPIbov1 | **dUTPase (Dut)** - trimer | φ11, 80α |
| SaPIbov5 | **dUTPase (Dut)** - dimer | φNM1 |
| SaPIbov2 | **ORF15** | 80α |
| SaPI1 | **Sri** | Diverse |
| SaPI2 | **Rekombinase** | Diverse |

---

## 4. PICI-Detektion: Bioinformatische Tools

### SatelliteFinder

| Eigenschaft | Details |
|-------------|---------|
| **Funktion** | Genomweite Identifikation von Phagen-Satelliten |
| **Familien** | P4-like, PICI, cfPICI, PLE |
| **Ergebnis** | ~5.000 Satelliten identifiziert |

### PHAROKKA (Phagen-Annotation)

| Feature | Details |
|---------|---------|
| **Funktion** | Schnelle Phagen-Genom-Annotation |
| **Virulenz-Detektion** | VFDB |
| **AMR-Detektion** | CARD |
| **Speed** | <5 min für 50 kb Genom |

---

## 5. Forschungslücke: Stl-Inducer-Detektion

**Es existiert KEIN spezifisches Tool zur Vorhersage von Stl-dereprimierenden Phagen-Proteinen!**

### Warum ist das schwierig?

| Problem | Erklärung |
|---------|-----------|
| **Strukturelle Diversität** | Inducer sind strukturell unterschiedlich |
| **Keine Sequenzhomologie** | Sequenz-basierte Suche versagt |
| **Multiple Targets** | Ein Stl kann mehrere Inducer erkennen |

---

## 6. Relevanz für UNVEIL

### Dual-Use Aspekt

| Anwendung | Ziel bezüglich Stl-Inducer |
|-----------|----------------------------|
| **Therapeutische Phagen** | Inducer **vermeiden** |
| **UNVEIL-Konzept** | Inducer **nutzen** → gezielte ePICI-Aktivierung |

### Implikationen

1. **Helfer-Phagen-Auswahl:** 80α als "universeller" Inducer
2. **Δcos-Mutanten:** Reine ePICI-Partikel ohne Phagen
3. **Inducer-Engineering:** Optimierung der Stl-Bindung

---

## Quellen

1. [Structure of polygamous repressor - Nature Communications](https://www.nature.com/articles/s41467-019-11504-2)
2. [Pirating conserved phage mechanisms - eLife](https://elifesciences.org/articles/26487)
3. [Pharokka - Bioinformatics](https://academic.oup.com/bioinformatics/article/39/1/btac776/6858464)
4. [Moonlighting phage proteins - Nature](https://www.nature.com/articles/nature09065)

---

*Für UNVEIL-Projekt kompiliert: April 2026*
