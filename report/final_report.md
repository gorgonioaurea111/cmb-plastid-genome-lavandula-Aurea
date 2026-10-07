# Lab Activity: Characterization of the Plastid Genome of *Lavandula angustifolia*
**Course:** Cell and Molecular Biology (CMB)  
**Organism:** *Lavandula angustifolia* Mill. (English Lavender)  
**Family:** Lamiaceae  
**NCBI Accession:** `NC_029370.1`  
---
## Part 1: Answers to Lab Questions (Questions 1–10)
### 1. Basic Genome Metadata
* **Scientific Name:** *Lavandula angustifolia* Mill.
* **Family:** Lamiaceae
* **NCBI Accession/Version:** `NC_029370.1` (GenBank: `KX216399.1`)
* **Database Source:** NCBI RefSeq / Nucleotide
* **Complete Genome Size:** 153,448 bp
### 2. Evidence of Completeness
The record represents a complete plastid genome because Galaxy sequence analysis confirms a single continuous sequence record (`num_seq = 1`) with a total length of 153,448 bp. The annotation contains a full, conserved set of functional genes (CDS, tRNAs, rRNAs) spanning standard quadripartite regions, unlike short DNA barcode markers (e.g., *rbcL*, *matK*), intergenic spacers, or unmapped sequencing fragments.
### 3. Overall Genome Architecture
*Lavandula angustifolia* displays a circular, quadripartite plastome architecture consisting of:
* **Large Single-Copy (LSC) Region:** ~83,200 bp
* **Small Single-Copy (SSC) Region:** ~17,400 bp
* **Two Inverted Repeat (IRa & IRb) Regions:** ~26,400 bp each
### 4. Annotated Gene Content & IR Duplications
* **Total Genes:** 133 annotated genes (113 unique genes)
  * **Protein-Coding Genes (CDS):** 88
  * **tRNA Genes:** 37
  * **rRNA Genes:** 8
* **Gene Duplication Explanation:** Genes located within the Inverted Repeat (IR) regions—such as all four ribosomal RNA genes (*rrn16*, *rrn23*, *rrn4.5*, *rrn5*) and associated tRNAs—exist in two identical physical copies because the IR regions are duplicated in reverse orientation across the circular genome.
### 5. Protein-Coding Genes Across Functional Groups
1. **`psbA`** (Photosystem II): Encodes the D1 reaction center protein required for light energy absorption and electron transfer.
2. **`psaA`** (Photosystem I): Encodes the P700 chlorophyll a apoprotein A1 involved in photosystem I reaction center activity.
3. **`rbcL`** (RuBisCO): Encodes the large subunit of ribulose-1,5-bisphosphate carboxylase/oxygenase for carbon fixation.
4. **`atpA`** (ATP Synthase): Encodes the alpha subunit of the CF0CF1 ATP synthase complex responsible for ATP synthesis.
5. **`petA`** (Cytochrome b6f): Encodes cytochrome f involved in photosynthetic electron transport between photosystems.
6. **`rpoA`** (RNA Polymerase): Encodes the alpha subunit of plastid-encoded RNA polymerase (PEP) essential for transcription.
7. **`rps12`** (Ribosomal Protein): Encodes 30S ribosomal protein S12, a core component of the translation machinery undergoing trans-splicing.
8. **`clpP`** (Protease): Encodes the proteolytic subunit of the ATP-dependent Clp protease complex involved in protein degradation.
### 6. RNA Features & Intron-Containing Genes
* **rRNA Genes:** *rrn16*, *rrn23*, *rrn4.5*, and *rrn5* (duplicated in IRs).
* **tRNA Examples:** *trnH-GUG*, *trnK-UUU*, *trnL-UAA*, and *trnM-CAU*.
* **Intron-Containing Genes:** *clpP* (contains 2 introns), *ycf3* (contains 2 introns), and *petB* (contains 1 intron).
### 7. Pseudogenes & Structural Features
The *Lavandula angustifolia* plastid genome maintains highly conserved gene order and synteny typical of Lamiaceae family plastomes, displaying no major gene losses, novel rearrangements, or pseudogenes beyond minor expansion/contraction events at LSC/IR/SSC boundary junctions.
### 8. Sequence Statistics & Observations
* **GC Content:** 38.04%
* **Observation 1 (AT Bias):** Base composition is significantly A+T rich, with adenine and thymine accounting for 61.96% (95,078 bp) of the genome.
* **Observation 2 (Assembly Quality):** Zero ambiguous base pairs (`num_N = 0`), confirming a high-quality, complete assembly represented as a single contiguous molecule (`num_seq = 1`).
---
### 9. Comparison of Plastid and Mitochondrial Genomes
#### **Five Similarities:**
1. **Endosymbiotic Origin:** Both organelles evolved from ancient free-living prokaryotic endosymbionts (cyanobacteria for plastids, alpha-proteobacteria for mitochondria).
2. **Inheritance Pattern:** Both exhibit non-Mendelian, predominantly uniparental (maternal) inheritance in angiosperms.
3. **Autonomous Protein Expression:** Both maintain independent 70S prokaryote-like ribosomes, tRNAs, and rRNAs for translating organellar-encoded proteins.
4. **Multiple Copy Number:** Both exist in high copy numbers per cell rather than a single nuclear diploid set.
5. **Endosymbiotic Gene Transfer:** Both have lost significant original ancestral genes over evolutionary time via migration to the cell nucleus.
#### **Five Differences:**
1. **Genome Size & Variation:** Plastid genomes are compact and uniform (~120–170 kb), whereas plant mitochondrial genomes are much larger and highly variable in size (200 kb to over 2 Mb).
2. **Structural Stability:** Plastids maintain a rigid, conserved quadripartite architecture, whereas plant mitochondrial genomes undergo frequent structural rearrangements and recombination.
3. **Mutation Patterns:** Plastid genomes have a moderate point-mutation rate, whereas plant mitochondrial genomes have an exceptionally low nucleotide substitution rate.
4. **Primary Functions:** Plastid genomes encode genes for photosynthesis and metabolic biosynthesis, whereas mitochondrial genomes encode components for cellular respiration and ATP synthesis.
5. **Physical Conformation:** Plastid genomes map predominantly as single circular molecules, whereas plant mitochondrial genomes form complex dynamic networks of linear, circular, and branched molecules.
---
### 10. Practical Value, Advantages, Limitations, & Applications
#### **Advantages of Plastid Genomes over Nuclear Genomes:**
1. **High Copy Number:** Easy to sequence and amplify even from ancient, degraded, or herbarium specimens.
2. **Structural Conservation:** Conserved gene order allows reliable universal primer design across broad taxa.
3. **Haploid & Uniparental:** Lacks heterozygosity and biparental recombination, simplifying lineage tracking.
4. **Compact Structure:** Lacks large repetitive non-coding arrays and transposable elements that hamper nuclear assembly.
#### **Important Limitations:**
1. **Single Structural Locus:** Functions as a single linked genetic unit, delivering only one locus tree.
2. **Obscured Hybridization:** Maternal inheritance cannot reveal polyploidy, reticulate evolution, or cross-species hybridization.
3. **Reduced Resolution at Low Speciation:** Moderate substitution rates may lack adequate variations for resolving very recent speciation events.
#### **Sample Research Questions:**
* **Plastid Data Query:** *"What are the deep phylogenetic relationships and divergence times among major genera within the family Lamiaceae?"* (Ideal because conserved plastid sequences provide strong evolutionary signal across broad timescales).
* **Nuclear Genomic Data Query:** *"How have historical hybridization and biparental gene flow influenced heat-tolerance adaptations across wild populations of Lavandula?"* (Ideal because nuclear data captures recombination, biparental lineages, and polygenic adaptive loci).
---
## Part 2: Plastid vs. Mitochondrial Genome Comparison Table

| Feature | Plastid Genome | Mitochondrial Genome |
| :--- | :--- | :--- |
| **Cellular location** | Stroma of plastids/chloroplasts | Matrix of mitochondria |
| **Main biological functions** | Photosynthesis, fatty acid synthesis, amino acid synthesis | Cellular respiration, oxidative phosphorylation, ATP synthesis |
| **Typical genome organization** | Circular quadripartite structure (LSC, SSC, two IRs) | Variable; circular, linear, and complex branched molecules |
| **Relative genome size** | Uniform across land plants (120–170 kb) | Highly variable and larger in plants (200 kb to >2,000 kb) |
| **Gene content** | ~110–130 genes (photosynthesis, gene expression machinery) | ~50–60 genes (respiratory complexes, gene expression) |
| **Copy number** | High (1,000 to 10,000 copies per cell) | Moderate to high (100 to 1,000 copies per cell) |
| **Inheritance** | Predominantly maternal in angiosperms | Predominantly maternal in angiosperms |
| **Recombination / structural change** | Low rate of structural recombination; highly syntenic | High intramolecular recombination; frequent rearrangements |
| **Mutation/substitution pattern** | Moderate nucleotide substitution rate | Exceptionally low nucleotide substitution rate |
| **Common research applications** | Plant phylogenetics, population genetics, plastid transformation | Evolutionary history of organellar transfer, cytoplasmic male sterility (CMS) |
