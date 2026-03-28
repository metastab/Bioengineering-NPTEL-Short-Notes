This document, titled **"Protein Interactions & Systems Biology"**, is the 38th lecture in the course *Bioengineering: An Interface with Biology and Medicine*. Its primary purpose is to provide a comprehensive overview of **interactomics**—the study of molecular interactions—and the emerging field of **systems biology**. The lecture explores label-free technologies, particularly **Surface Plasmon Resonance (SPR)**, and how high-throughput data is integrated to understand complex physiological systems.

### Interactomics and Biological Networks

Interactomics focuses on studying the interactions between various proteins and other cellular components, such as lipids, nucleic acids, and small drug inhibitors.

  * **Interactome**: This term refers to the network of all such interactions within a cell, providing a better understanding of genome and proteome functions.
  * **Dynamic Proteome**: The proteome is highly dynamic and intricately connected to the genome, transcriptome, metabolome, and various environmental factors.
  * **Types of Interactions**: Interactions are categorized by their nature, such as **transient** (lasting only fractions of a second) or **permanent**. They can also be classified as **weak** or **strong**, **obligate** or **non-obligate**, and can involve **homo-oligomers** (identical units) or **hetero-oligomers** (different units).
  * **Physical Basis**: Molecular interactions are driven by physical forces, including **electrostatic**, **steric**, **hydrophobic**, and **hydrogen bonds**.
  * **Biological Significance**: These interactions are essential for nearly every cellular event, including **signal transduction**, DNA replication, translation, cell cycle control, and metabolism.

### Overview of Label-free Techniques

While previous lectures covered label-based methods like protein microarrays, this document emphasizes **label-free techniques**, which measure molecular interactions without adding fluorescent or radioactive tags.

  * **Physical Principles**: These methods measure changes in physical properties, such as conductance, reflectance, or interference, when two biomolecules interact.
  * **Popular Platforms**: Notable label-free technologies include:
      * **Surface Plasmon Resonance (SPR)**: Measures changes in the **refractive index** (how light bends) of a medium directly in contact with a sensor surface, typically gold.
      * **Carbon Nanotubes**: Uses them as multi-color Raman labels to detect binding events.
      * **Planar Wave Guide Array**: A sensor platform used for high signal-to-noise ratio detection.
      * **Nanowire Sensor Array**: Measures changes in **conductance** (electrical flow) upon molecular binding.
      * **Nanohole Array**: Uses monochromatic light to study interactions through sub-wavelength holes in a metal film.
      * **Spectral Reflectance Imaging Biosensor**: Uses interference properties to monitor biomolecular interactions.

### Surface Plasmon Resonance (SPR) in Detail

SPR is a prominent label-free platform that monitors binding events in real-time.

  * **Sensorgram**: This is the output of an SPR experiment, plotting the **SPR signal** (in Response Units, or **RU**) against **time**.
  * **Phases of a Sensorgram**:
      * **Baseline**: The stable signal before interaction begins.
      * **Association (On-rate)**: The phase where the **query reagent** (analyte) binds to the immobilized **ligand**.
      * **Stochastic Steady State**: The point where binding and dissociation rates are equal, resulting in a stable signal.
      * **Dissociation (Off-rate)**: The phase where the analyte is washed away and dissociates from the ligand.
      * **Regeneration**: Using mild acids to remove all bound analyte from the chip, returning the signal to baseline so the chip can be reused.
  * **SPR Imaging (SPRi)**: A high-throughput advancement that combines SPR with microarrays to analyze hundreds or thousands of interactions simultaneously across the entire chip area using a **CCD** (Charge-Coupled Device) camera.
  * **SPR-MS**: Integration of SPR with **Mass Spectrometry** allows for both the measurement of interaction kinetics and the subsequent identification of the bound proteins.

### Systems Biology Approach

Systems biology aims to understand biological processes as whole, integrated systems rather than isolated parts.

  * **Data Integration**: It involves the behavior and relationships of all elements in a biological system, integrating high-throughput data from genomics, transcriptomics, and proteomics.
  * **Emerging Properties**: The property of a "system" is more than just the sum of its individual components; new properties emerge when components are analyzed within complex networks.
  * **Systems Biology Triangle**: This concept involves the synergy of three major aspects: **Experiment** (data generation), **Computational Modeling** (proposing models and simulations), and **Technology** (integration of theory and tools).
  * **Distinct Approaches**:
      * **Model-based**: Relies on prior information and computational simulation tools to build kinetic models.
      * **Data-based**: Relies on large **"omic" datasets** to discover new biological phenomena and map complex relationships among metabolic pathways and networks.
