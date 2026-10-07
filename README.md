# Characterization of the Plastid Genome of *Lavandula angustifolia*

## Student & Course Information
* **Student Name:** Gorgonio A. Aurea lll
* **Course & Section:** Cell and Molecular Biology, Section - B
* **Selected Genus:** *Lavandula*
* **Selected Species:** *Lavandula angustifolia* (English Lavender)

---

## Genome Source Information
* **NCBI Accession:** [`NC_029370.1`](https://www.ncbi.nlm.nih.gov/nuccore/NC_029370.1)
* **Organism:** *Lavandula angustifolia*
* **Family:** Lamiaceae
* **Database:** NCBI RefSeq / Nucleotide
* **Date Retrieved:** October 7, 2026

---

## Genome Statistics Summary
The sequence analysis was performed using **Galaxy** (usegalaxy.org) with the **FASTA Statistics** tool.

* **Complete Genome Size:** 153,448 bp
* **Sequence Records:** 1 (complete circular plastome)
* **Overall GC Content:** 38.04%
* **Base Composition:**
  * **Adenine (A):** 46,802 bp
  * **Thymine (T):** 48,276 bp
  * **Cytosine (C):** 29,682 bp
  * **Guanine (G):** 28,688 bp
  * **Ambiguous Bases (N):** 0 bp

---

## Galaxy Analysis Workflow
1. **Account & History:** Created a Galaxy history named `Plastid_Lavandula <Aurea>`.
2. **Data Import:** Uploaded the complete plastid genome FASTA file (`NC_029370.1.fasta`) from NCBI Nucleotide.
3. **Dataset Renaming:** Renamed the dataset to `Lavandula_angustifolia_NC_029370.1` and set datatype to `fasta`.
4. **Tool Execution:** Ran **FASTA Statistics** to evaluate sequence length, record count, and nucleotide distribution.
5. **Output Verification:** Confirmed a single contig of 153,448 bp with 38.04% GC content.

*Screenshot of the Galaxy workflow and output statistics is available in `figures/galaxy_statistics_screenshot.png`.*

---

## Gene Content & Structural Overview
* **Architecture:** Quadripartite circular structure comprising Large Single-Copy (LSC ~83.2 kb), Small Single-Copy (SSC ~17.4 kb), and two Inverted Repeats (IRa & IRb ~26.4 kb each).
* **Total Annotated Genes:** 133 total genes (113 unique genes).
* **Gene Breakdown:**
  * **Protein-Coding Genes (CDS):** 88
  * **tRNA Genes:** 37
  * **rRNA Genes:** 8 (duplicated across IR regions)
* **Key Observations:** Inverted Repeat regions contain identical copies of rRNA genes (*rrn16*, *rrn23*, *rrn4.5*, *rrn5*) and associated tRNAs. Notable intron-containing genes include *clpP*, *ycf3*, and *petB*.

---

## How to Reproduce This Analysis
1. Download the FASTA sequence for `NC_029370.1` from NCBI Nucleotide.
2. Log into [usegalaxy.org](https://usegalaxy.org) and upload the FASTA file.
3. In the Galaxy tool panel, search for and run **FASTA Statistics** (or **SeqKit statistics**).
4. Compare the generated summary stats with the recorded values above.

---

## Data Sources & References
* **NCBI Record:** [NCBI RefSeq NC_029370.1](https://www.ncbi.nlm.nih.gov/nuccore/NC_029370.1)
* **Galaxy Project:** [usegalaxy.org](https://usegalaxy.org)
