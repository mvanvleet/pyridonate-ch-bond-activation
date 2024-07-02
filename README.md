# Gaussian Files and Structures for Pyridonate Pincer Complexes

This repository contains Supplementary Information pertaining to the manuscript "A σ-Poor, π-Rich Pyridonate Pincer Ligand Designed to Enhance C-H Oxidative Addition at Platinum Group Metals: Experimental and Computational Studies" as submitted to _Organometallics_. 

The repository contains:
* Gaussian input (.com) and output (.log) files for all geometry optimizations, single-point energy calculations, NBO calculations, and relaxed scans
* .xyz files corresponding to all optimized structures at the wB97X-D/def2-TZVPP level of theory
* A summary Excel spreadsheet containing energies and free energies for various calculated species, along with the associated energy and free energy barriers for the various transitions states (TS) described in the manuscript

The naming scheme for Gaussian files is outlined in the summary Excel
spreadsheet (summary.xlsx). In brief, file names for ground state geometry
optimizations are of the form PML1[L2].gjf, where P represents the pincer
ligand (Y = classic NCN pincer, Z = pyridonate ligand, HZ = protonated
pyridonate ligand), M represents the metal (M = Pt, Ir, Rh), and other ligands
directly attached to the metal (L1, L2) are listed after the metal name. Thus,
for example, HZPtMeH.gjf would correspond to the methyl hydride complex
resulting from oxidative addition between methane and a protonated pyridonate
platinum complex, which is compound 14’ in the main text. For transition
states, Gaussian job file names are of the form TS/QST2_reactant_product.gjf .

For convenience, file names for compounds explicitly discussed in the main text are
given in the table below.

| File (.gjf)  | Compound # | Comment     |
|--------------|------------|-------------|
| ZPtMe        |  2'        |             |
| ZPtMeH (TS_ZPtMeH_ZPtMeHsigma.xyz)      |  4'        |  For ZPt, OA complex corresponds to a transition state rather than a ground state structure         |
| MeZPtMe      |  7'        |             |
| MeZPt        |  8'        | Bare metal; no counterion    |
| HZPtMe       |  9'        |             |
| HZPt         |  10'       | Bare metal; no counterion     |
| ZPtMeH\_sigma |  11'       |             |
| MeZPtMeMe    |  12'       |             |
| MeZPt        |  13'       |  Bare metal; no counterion            |
| HZPtMeH      |  14'       |             |
| HZPtMeH\_sigma |  15'       |             |
| HZPt         |  16'       |  Bare metal; no counterion            |
| ZIr       |  18'Ir       |  Bare metal; no counterion |
| ZIrMeH       |  18'Ir(CH3)(H)       |          |
| HZIrMe       |  (NN<sup>OH</sup>N)IrMe       |            |
| YIr       |  17'Ir       |  Bare metal; no counterion |
| YIrMeH       |  17'Ir(CH3)(H)       |          |
| ZRh       |  18'Rh       |  Bare metal; no counterion |
| ZRhMeH       |  18'Rh(CH3)(H)       |          |
| HZRhMe       |  (NN<sup>OH</sup>N)RhMe       |            |
| YRh       |  17'Rh       |  Bare metal; no counterion |
| YRhMeH       |  17'Rh(CH3)(H)       |          |



Any questions or requests for information about the data can be sent to mary.vanvleet (at) spelman.edu



