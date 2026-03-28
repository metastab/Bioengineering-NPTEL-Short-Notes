This document, titled **"Techniques to Study Protein & Proteome-II"** (Lecture 34 of the course *Bioengineering: An Interface with Biology and Medicine*), discusses advanced methods for protein analysis and purification. Its primary purpose is to explain **Difference Gel Electrophoresis (DIGE)** as an advancement over traditional 2D electrophoresis for quantitative proteomics and to detail various **chromatography** techniques used for protein purification.

### 1\. Difference Gel Electrophoresis (DIGE)

DIGE is presented as a solution to the limitations of traditional 2-Dimensional Electrophoresis (2-DE), such as gel-to-gel variation and user bias in data analysis.

  * **Mechanism and Labeling**: Different protein samples are labeled with distinct **cyanine dyes** (Cy3, Cy5, and Cy2) before being mixed and separated on a single gel.
  * **Cyanine Dyes**: These are derivatives of **N-hydroxysuccinimide** that covalently bind to the **epsilon amino group** of lysine residues on proteins.
  * **Internal Standard**: A critical feature of DIGE where equal amounts of protein from all samples in an experiment are pooled and labeled with **Cy2**. This pooled standard acts as a universal reference point on every gel, facilitating accurate normalization and co-detection.
  * **Labeling Strategies**:
      * **Minimum Labeling**: Targets the lysine amino group, labeling approximately 3% of all proteins.
      * **Saturation Labeling**: Targets **cysteine** residues and is used for proteins with high cysteine content.
  * **Dye Swapping**: A method to eliminate potential labeling bias by alternating which dye (Cy3 or Cy5) is used for control and treated samples across different gels.
  * **Analysis**: Labeled samples co-migrate on one gel, which is then scanned at different wavelengths to produce distinct images for each Cy dye. Software overlays these images to identify differentially expressed proteins, often visualized as red or green spots against a yellow background of unchanged proteins.

### 2\. Protein Purification and Chromatography

The document transitions to **protein purification**, which is essential for studying the structural and functional properties of specific proteins. **Chromatography** is defined as a collection of techniques that separate complex mixtures based on the differential partitioning of molecules between a **stationary phase** and a **mobile phase**.

  * **Gel Filtration Chromatography (Size Exclusion)**:
      * Separates proteins based on **size** using a column of porous beads (made of polyacrylamide, dextran, or agarose).
      * Large molecules elute first because they do not enter the pores, while small molecules are retained longer as they travel through the porous matrix.
  * **Ion Exchange Chromatography**:
      * Separates proteins based on **net charge** differences.
      * Common exchangers include **CM-cellulose** (carboxymethyl, a cation exchanger for positively charged proteins) and **DEAE-cellulose** (diethylaminoethyl, an anion exchanger for negatively charged proteins).
      * Proteins are eluted (desorbed) by increasing salt concentration, where ions compete for binding sites, or by altering the pH to change the protein's charge.
  * **Affinity Chromatography**:
      * Utilizes specific biological interactions between a protein and a **ligand** (such as a substrate, antibody, or metal) coupled to matrix beads.
      * **His-tag Purification**: A common application where a **histidine tag** is genetically engineered into a protein. The tagged protein binds to a column containing **nickel (Ni-NTA)** beads. It is later eluted using **imidazole**, which competes with the histidine tag for binding sites.

### 3\. Fast Protein Liquid Chromatography (FPLC)

The laboratory demonstration highlights the **FPLC system** for automated protein purification.

  * **Components**: Includes pumps for different buffers, an injection valve and loops for sample loading, columns (e.g., **Superdex 200** for size exclusion), a flow cell to measure pH and conductivity, and a **UV detector** at 280 nm to detect protein elution.
  * **Software Control**: Systems like the **Unicorn software** allow users to set flow rates, manage gradients for elution, and evaluate the resulting chromatograms to isolate purified proteins.
