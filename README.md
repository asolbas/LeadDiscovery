# LeadDiscovery

Code and data for the final project of the Computational Structural Biology for Lead Discovery course (MSc in Computational Biology-UPM). 

## Overview

The aim of this project was to create a computational pipeline for the identification of drug candidates for **JAK-family kinases**, which are a group of proteins involved in inflamatory diseases such as rheumatoid arthritis or psoriasis.   

The lead discovery pipeline proposed in this work is divided in three modules, which must be performed in chronological order: 

1. Ligand based virtual screening (LBVS)
2. Pharamcophore based virtual screening (PBVS)
3. Structure based virtual screening (PBVS)

All the data and Jupyter notebook's scripts used for each module in the present work can be found in their correspondent folders.

## Dependencies

- [RDKit](https://www.rdkit.org/)
- [OpenBabel](http://openbabel.org/wiki/Main_Page)
- [LeDock](http://www.lephar.com/software.htm)
- [Smina](https://sourceforge.net/projects/smina/)
- [Python](https://www.python.org/downloads/)

## Data and Bioinformatics tools

The structural and chemical data used for the project has been retrieved from several biochemical databases using the web server or their API. 

- Drug candidates: [ChEMBL](https://www.ebi.ac.uk/chembl/) and [PubChem](https://pubchem.ncbi.nlm.nih.gov/)
- LBVS compounds: [SwissModel](https://www.rcsb.org/)
- Protein structures: [PDB](https://swissmodel.expasy.org/)
- Pharmacophore: [Pharmit](https://pharmit.csb.pitt.edu/) and [PharmaGist](https://bioinfo3d.cs.tau.ac.il/PharmaGist/)

## Contributors 

Ana Solbas and Natalia García

## Liscense

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

