# Gaussian Files and Structures for Pyridonate Pincer Complexes

This repository contains Supplementary Information pertaining to the manuscript "A σ-Poor, π-Rich Pyridonate Pincer Ligand Designed to Enhance C-H Oxidative Addition at Platinum Group Metals: Experimental and Computational Studies" as submitted to _Organometallics_. 

The repository contains:
* Gaussian input (.com) and output (.log) files for all geometry optimizations, single-point energy calculations, NBO calculations, and relaxed scans
* .xyz files corresponding to all optimized structures at the wB97X-D/def2-TZVPP level of theory
* A summary Excel spreadsheet containing energies and free energies for various calculated species, along with the associated energy and free energy barriers for the various transitions states (TS) described in the manuscript

The naming scheme for Gaussian files is outlined in the Excel spreadsheet. In
brief, file names for geometry optimizations are of the form PML1[L2], where P
represents the pincer ligand (Y=classic NCN pincer, Z=pyridonate ligand,
HZ=protonated pyridonate ligand), M represents the metal (M=Pt, Ir, Rh), and
other ligands (L) directly attached to the metal are listed after the metal
name. Thus, for example, HZPtMeH.gjf would correspond to the oxidative
addition complex between methane and a protonated pyridonate platinum complex.

For convenience, file names for compounds explicitly in the main text are
given in the table below.

| File (.gjf)  | Compound # | Comment     |
|--------------|------------|-------------|
| ZPtMe        |  2'        |             |
| YPtMe        |  3'        |             |
| ZPtMeH       |  4'        |             |
| YPtMeH       |  5'        |             |
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


Any questions or requests for information about the data can be sent to mary.vanvleet (at) spelman.edu



