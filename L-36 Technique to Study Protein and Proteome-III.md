This document, titled **"Techniques to Study Protein & Proteome-III"** (Lecture 36 of the course *Bioengineering: An Interface with Biology and Medicine*), focuses on the application of mass spectrometry in the field of proteomics. Its primary purpose is to explain the fundamental components of a mass spectrometer and demonstrate how these tools are used to identify and quantify thousands of proteins in complex biological samples.

### Core Concept of Mass Spectrometry (MS)

Mass spectrometry is a technique used for protein identification and analysis.

  * **Mechanism**: It produces charged molecular species in a vacuum and separates them using magnetic and electric fields.
  * **Measurement**: Separation is based on the **mass-to-charge (m/z) ratio**, which is the physical quantity representing the mass of an ion divided by its electric charge.
  * **Significance**: MS is the method of choice for proteomics due to its ability to identify thousands of proteins simultaneously.

### Proteomics Workflow

The document outlines a typical MS-based proteomics workflow:

  * **Digestion**: An intact protein is digested into smaller fragments called **proteolytic peptides** using enzymes like **trypsin**, which cleaves proteins at specific amino acid sites.
  * **Separation**: These peptides are often separated using **liquid chromatography (LC)**, which sorts molecules in a solution based on properties like hydrophobicity.
  * **Ionization**: Peptides are converted into **gas-phase ions** in a vacuum.
  * **Analysis**: Ions are separated by mass analyzers to generate a mass spectrum. Researchers can use one analyzer for standard **MS** or two for **MS/MS (tandem mass spectrometry)** to obtain peptide sequence information.

### Ionization Sources

Ionization sources are responsible for converting analyte molecules into gas-phase ions. The field uses **soft ionization**, a technique that ionizes non-volatile biomolecules with minimal fragmentation, making the resulting data easier to interpret.

  * **MALDI (Matrix-Assisted Laser Desorption/Ionization)**:
      * The analyte is mixed with a **matrix**, a chemical compound (usually an aromatic acid like **CHCA** or **DHB**) that absorbs UV laser energy and transfers it to the sample to ionize it.
      * The sample-matrix mixture is crystallized on a metallic target plate and bombarded with short, intense laser pulses.
  * **ESI (Electrospray Ionization)**:
      * Ions are formed by spraying a dilute solution from a fine metal capillary at atmospheric pressure, creating a highly charged fine mist of droplets.
      * As solvent evaporates, the droplet size reduces and the molecules pick up protons to form gas-phase ions that are drawn into the mass analyzer.

### Mass Analyzers

Mass analyzers resolve ions based on their m/z ratios using various physical properties:

  * **Time of Flight (TOF)**: Measures the time it takes for ions to travel through a vacuum tube to the detector. Mass is exponentially proportional to flight time; thus, lighter ions reach higher velocities and hit the detector faster.
  * **Quadrupole**: Uses oscillating electrical fields to selectively stabilize or destabilize the paths of ions passing through a radio frequency (RF) field.
  * **Orbitrap**: Consists of barrel-like and spindle-like electrodes that create an electrostatic field. Ions oscillate around the central electrode, creating a signal that is deconvoluted using a **Fourier transform** to determine m/z values.
  * **Hybrid and Tribrid Systems**: Modern instruments often combine multiple analyzers (e.g., **Q-TOF** or **Orbitrap Fusion**) to increase resolution and provide multiple ways to fragment and analyze ions.

### Quantitative Proteomics

Beyond identification, MS is used for **quantitative proteomics** to compare protein levels across different conditions.

  * **iTRAQ (Isobaric Tagging for Relative and Absolute Quantification)**:
      * Uses **isobaric tags**, which are multiplexed reagents that add the same total mass to all samples but release different **reporter ions** during MS/MS.
      * This allows up to eight different biological samples to be mixed and analyzed simultaneously.
  * **TMT (Tandem Mass Tags)**: A similar technology to iTRAQ that also uses isobaric tagging for simultaneous identification and quantification.
