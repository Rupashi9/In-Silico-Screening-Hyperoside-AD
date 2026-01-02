# In-Silico-Screening-Hyperoside-AD
Data and methods for the in-silico discovery of MTDL leads from Himalayan phytoconstituents targeting Alzheimer's Disease (BACE1 and MAO-B). Includes docking poses, ADMET profiles, and reverse pharmacology screening results
# In-Silico Screening of Himalayan Phytoconstituents for Alzheimer’s Therapy
**Targeting Multi-Target Directed Ligands (MTDL) via Reverse Pharmacology**

[![ORCID](https://img.shields.io/badge/ORCID-0009--0002--5144--8676-green)](https://orcid.org/0009-0002-5144-8676)
[![Preprint](https://img.shields.io/badge/ChemRxiv-Awaiting_Approval-orange)](https://chemrxiv.org)

## 🧬 Project Overview
This repository hosts the computational dataset and molecular docking results for the identification of **Hyperoside** as a dual-action inhibitor against Alzheimer’s Disease (AD). By utilizing a **Reverse Pharmacology** approach, we screened 48 phytochemicals native to the Himalayan region.

### 🧪 Key Findings: Hyperoside (Lead Compound)
Hyperoside demonstrated superior binding affinity across key neurodegenerative targets and stability in human transport proteins.

| Target Protein | PDB ID | Binding Affinity (kcal/mol) | Key Interactions |
| :--- | :--- | :--- | :--- |
| **BACE1** | 1FKN | **-8.8** | Asp32, Asp228 (Catalytic Dyad) |
| **MAO-B** | 2V5Z | **-8.2** | Cys172, Ile199 |
| **HSA (Transport)**| 1A06 | **-9.4** | Hydrophobic Pocket |



## 📂 Repository Structure
* `/Proteins`: Prepared PDBQT files for BACE1, MAO-B, and HSA.
* `/Ligands`: Library of 48 Himalayan phytochemical structures (.sdf).
* `/Results`: Raw docking logs and 3D interaction snapshots.
* `/ADMET`: Pharmacokinetic and toxicity screening data from SwissADME.

## 💻 Methodology
1. **Protein Preparation:** Targeted receptors were cleaned, water molecules removed, and polar hydrogens added.
2. **Molecular Docking:** Performed using **AutoDock Vina** (via PyRx) with a focused grid box on active sites.
3. **ADMET Profiling:** Evaluated for Blood-Brain Barrier (BBB) permeability and Lipinski’s Rule of Five compliance.
4. **Visualization:** Interaction maps generated using **PyMOL** and **Discovery Studio**.

## 📄 Citation
If using this data, please cite the forthcoming ChemRxiv preprint:
*Rupashi et al. (2026). "ADMET Profiling and In-silico Screening of Himalayan Phytoconstituents..."*

---
**Contact:** [Rupashi Verma] | [jayish2002@gmail.com] | [C.G.C. University]
