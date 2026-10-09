# Lab Plastid Genome Visualization - Visualize Plastid Genome Structure
**Author:** Gorgonio A. Aurea lll 
**Date:** October 9, 2026  
---
## Overview
This laboratory activity documents the visualization, structural mapping, and analysis of the complete circular chloroplast genome of *Lavandula angustifolia* using OrganellarGenomeDRAW (OGDRAW).
---
## Genome Summary
* **Scientific Name:** *Lavandula angustifolia*
* **NCBI Accession Number:** NC_029370.1
* **Genome Size:** 153,448 bp
* **Source:** NCBI Nuccore (GenBank Format `.gb`)
---
## Part C. OGDRAW Visualization & Map Features
### Visualization Parameters
* **Software:** OrganellarGenomeDRAW (OGDRAW v1.3.1)
* **Map Mode:** Standard circular map
* **Sequence Source:** Plastid
* **Inverted Repeat (IR) Detection:** Automatic
* **Enabled Layers:** GC content graph, direction of transcription, full legend, intron asterisks (`*`)
* **Output Format:** PNG
### Plastid Genome Map
<img width="1250" height="1250" alt="ogdraw_job_e9c65c15425cfa34b912e121bc33b833-outfile-preview - Copy" src="https://github.com/user-attachments/assets/124d0641-cb5e-4545-aafb-959edb9b5fe3" />

### Summary of Map Structural Features

| Map Feature | Description & Key Examples | Observations on Organization & Distribution |
| :--- | :--- | :--- |
| **Large Single-Copy Region (LSC)** | Upper arc of the circular map | Contains photosynthetic complex genes (`psaA`, `psbA`), RNA polymerase (`rpo`), and ATP synthase subunits |
| **Small Single-Copy Region (SSC)** | Bottom segment opposite LSC | Primary locus for NADH dehydrogenase genes (`ndh` family) and `ccsA` |
| **Inverted Repeats A & B (IRa & IRb)** | Symmetrical side regions separating LSC and SSC | Identical duplicated regions housing ribosomal RNA operons (`rrn16`, `rrn23`) |
| **Protein-Coding Genes** | Indicated by colored blocks | Grouped functionally into polycistronic operons across all regions |
| **tRNA Genes** | Marked in blue/cyan text around outer/inner tracks | Distributed throughout to support translation; clustered near rRNA genes |
| **rRNA Genes** | Highlighted in red/maroon blocks in IR regions | Exclusively localized within IRa and IRb, duplicating their copy number |
| **Duplicated IR Genes** | Genes present in both IRa and IRb (`ycf2`, `ndhB`, `rps7`, `rrn` genes) | Displayed symmetrically on both sides due to IR duplication |
| **Direction of Transcription** | Gene arrow orientation (inside track = clockwise, outside = counter-clockwise) | Indicates bidirectional transcription across both DNA strands |
| **GC Content Graph** | Inner light-grey circle graph | Shows prominent peaks in IR regions due to high GC content of rRNA genes |

---
## Part E. Analysis & Study Questions
### 1. Scientific Name & Accession Number
* **Scientific Name:** *Lavandula angustifolia*
* **Accession Number:** NC_029370.1
### 2. Total Genome Length
* **Total Length:** 153,448 base pairs (bp)
### 3. Structural Regions (LSC, SSC, IRa, IRb)
* **LSC (Large Single-Copy):** Spans the large upper arc of the circular genome.
* **SSC (Small Single-Copy):** Spans the smaller segment at the bottom of the map.
* **IRa and IRb (Inverted Repeats):** Positioned on the right (IRa) and left (IRb) boundaries, separating the LSC and SSC regions.
### 4. Examples of Genes in the LSC Region
1. `psaA` (Photosystem I reaction center subunit IV)
2. `psbA` (Photosystem II reaction center protein D1)
3. `atpA` (ATP synthase subunit alpha)
### 5. Example of a Gene in the SSC Region
* `ndhF` (NADH dehydrogenase subunit 6)
### 6. Inverted Repeat Genes & Duplication
* **Example:** `ycf2` (also `ndhB`, `rrn16`, `rrn23`)
* **Duplication:** **Yes.** Because IRa and IRb are identical inverted duplicates, any gene located within the IR boundaries appears twice on opposite sides of the genome map.
### 7. Photosynthesis-Related Gene & Biological Function
* **Gene Name:** `psaA`
* **Biological Function:** Encodes a core reaction center protein of Photosystem I, which functions in driving photosynthetic electron transport to generate NADPH during light reactions.
### 8. Transcription Direction & Gene Orientation
* Gene orientation indicates strand specificity and direction of transcription ($5' \rightarrow 3'$). Genes on the inside track are transcribed in a clockwise direction, whereas genes on the outside track are transcribed counter-clockwise on the opposite strand.
### 9. GC Content Observation
* The GC content is non-uniform across the genome. Distinct elevated peaks occur within the inverted repeat regions (IRa and IRb), corresponding to high GC content within ribosomal RNA genes (`rrn16`, `rrn23`), whereas GC content is generally lower in the LSC and SSC regions.
### 10. Utility of Graphical Plastid Maps
* A graphical map visually integrates genome architecture (LSC/SSC/IRs), gene distribution, strand orientation, functional groupings, and GC content variation into an immediate, intuitive visual summary that is far easier to interpret than raw FASTA sequences or text annotations.
