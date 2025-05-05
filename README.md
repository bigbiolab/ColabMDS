# Molecular Modelling and Simulation on Google Colab 
![](https://github.com/bigbiolab/ColabMDS/blob/main/images/flowchart.png)
---


## Overview

Welcome to **Molecular Modelling and Simulation on Google Colab**! This course offers hands-on training in computational techniques used to study the structure, dynamics, and interactions of biological macromolecules. By leveraging the power of the free, cloud-based *Google Colab* platform, this course makes advanced molecular modelling and simulation methods accessible to everyone, regardless of local computing resources. We will explore a wide range of essential bioinformatics tools and workflows through a series of practical tutorials.

---
## Target Audience

This course is designed for undergraduate and graduate students, researchers, and professionals in *structural biology*, *bioinformatics*, *computational chemistry*, *biophysics*, *pharmacy*, and related life science fields who wish to gain practical skills in molecular modelling and simulation. Some familiarity with basic biological and chemical concepts is recommended. While programming experience (especially *Python*) is helpful, the tutorials are designed to be accessible via the user-friendly Colab interface.

---
## Learning Objectives

Upon successful completion of this course, participants will be able to:

* Set up and manage common bioinformatics software within the *Google Colab* environment.
* Visualize, manipulate, and compare biomolecular structures using tools like *py3Dmol* and *NGL Viewer*.
* Perform phylogenetic analyses using standard bioinformatics pipelines (*MAFFT*, *ModelTest-NG*, *RAxML-NG*).
* Build 3D protein models using comparative modelling techniques (*MODELLER*).
* Utilize *PyRosetta* for modelling tasks, including membrane proteins and *ab initio* folding.
* Conduct molecular docking studies to predict ligand binding using *AutoDock Vina*.
* Set up, run, and analyze conventional molecular dynamics (MD) simulations using *GROMACS*.
* Analyze MD simulation trajectories effectively using *MDAnalysis*.
* Employ structure-based models (SBMs) with *SMOG2* to simulate protein folding and conformational changes.
* Use coevolutionary sequence analysis (DCA) to predict molecular interactions.
* Integrate cutting-edge deep learning methods (*ColabFold*, *MSA Transformer*) with simulation and modelling pipelines.

---

### Course Content

The course is structured as a series of hands-on labs covering fundamental and advanced topics:

1.  **Foundations:** Introduction to *Google Colab*, accessing biomolecular databases, and fundamentals of molecular visualization and structural comparison (*Labs 01, 02*). (Note: *Lab 00* on specific installation methods is obsolete, but software setup is integrated into relevant labs).
2.  **Sequence Analysis & Evolution:** Building phylogenetic trees from sequence data (*Lab 03*).
3.  **Structure Prediction & Modelling:** Comparative modelling with *MODELLER* (*Lab 04*), membrane protein modelling (*Lab 05*) and *ab initio* folding with *PyRosetta* (*Lab 12*).
4.  **Molecular Interactions:** Predicting protein-ligand binding through molecular docking (*Lab 06*) and inferring interactions from sequence coevolution (*Lab 11*).
5.  **Molecular Simulation:** Running and analyzing classical MD simulations with *GROMACS* and *MDAnalysis* (*Labs 07, 08*). Simulating folding and conformational transitions using structure-based models with *SMOG2* (*Labs 09, 10*).
6.  **Integrative & Advanced Approaches:** Combining coevolutionary data (DCA) or deep learning embeddings (*MSA Transformer*) with structure-based models (*Labs 13, 14*). Integrating state-of-the-art structure prediction (*ColabFold*) with MD simulations (*Lab 15*).

---
## Methodology

This course employs a practical, hands-on approach using interactive *Google Colab notebooks*. Each tutorial guides participants through specific tasks, running analyses in real-time and visualizing results directly within the browser. We utilize widely adopted, *open-source* software packages prevalent in the field.

---
### Key Software Utilized

*GROMACS*, *PyRosetta*, *MODELLER*, *AutoDock Vina*, *MDAnalysis*, *SMOG2*, *ColabFold*, *Biopython*, *py3Dmol*, *NGL Viewer*, *MAFFT*, *ModelTest-NG*, *RAxML-NG*, *Open Babel*, *PDB2PQR*, *MGLTools*, *pyDCA*, *Infernal*, and others via *Miniconda/Bioconda*.

---
## Outcome

Participants will gain valuable practical experience in applying diverse molecular modelling and simulation techniques using accessible, state-of-the-art tools within the *Google Colab* framework, empowering them to tackle complex biological questions computationally.


---
## Contents
The course consists of a series of tutorials, each focusing on a specific aspect of molecular modelling and simulation. The tutorials are designed to be run in *Google Colab*, allowing for easy access and execution without the need for local installations. Each tutorial is self-contained, providing step-by-step instructions and explanations.


| Tutorial | Description                           | Software                                                        |
|--------|-------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| Lab.00 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/lab00_software.ipynb) | Installing Software on Google Colab for IBM3202 tutorials (**OBSOLETE**)                           | pyRosetta [1], GROMACS [2], SBM-enhanced GROMACS [3]                                                        |
| Lab.01 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/lab01_intro.ipynb) | Warm-up on Colab and Brief Review of Biomolecular Databases                         |                                                                                                             |
| Lab.02 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/lab02_molviz.ipynb) | Visualizing and Comparing Molecular Structures in Google Colab using py3Dmol        | Biopython [4], py3Dmol [5], NGL Viewer [6]                                                                  |
| Lab.03 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/lab03_phylo.ipynb) | Phylogenetic Analysis using biopython and RAxML                                     | Biopython [4], miniconda [7], MAFFT [8], ModelTest-ng [9], RAxML-ng [10]                                    |
| Lab.04 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/lab04_cm.ipynb) | Comparative Modeling using MODELLER                                                 | Biopython [4], py3Dmol [5], MODELLER [11]                                                                   |
| Lab.05 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/lab05_MP_rosetta.ipynb) | Membrane Protein Modelling using PyRosetta                                          | pyRosetta [1], py3Dmol [5]                                                                                  |
| Lab.06 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/lab06_docking.ipynb) | Molecular Docking on Autodock                                                       | Biopython [4], py3Dmol [5], miniconda [7], Open Babel [12], pdb2pqr [13], MGLTools [14], Autodock Vina [15] |
| Lab.07 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/lab07_MDsims.ipynb) | Molecular Dynamics on GROMACS                                                       | GROMACS [2], Biopython [4], py3Dmol [5], NGL Viewer [6]                                                     |
| Lab.08 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/lab08_MDanalysis.ipynb) | Trajectory Analysis using MDanalysis                                                | py3Dmol [5], MDAnalysis [16]                                                                                |
| Lab.09 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/lab09_SMOGfolding_docker.ipynb) | Folding Simulations using Structure-Based Models                                    | SMOG2 Docker, udocker, SBM-enhanced GROMACS [3], Biopython [4], py3Dmol [5], NGL Viewer [6]                                 |
| Lab.10 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/lab10_SMOGdual_docker.ipynb) | Conformational changes using Structure-Based Models                                 | SMOG2 Docker, udocker, SBM-enhanced GROMACS [3], Biopython [4], py3Dmol [5], NGL Viewer [6]                                 |
| Lab.11 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/lab11_rnaDCA.ipynb) | Prediction of interactions from the coevolutionary analysis of sequence information | Biopython [4], py3Dmol [5], infernal [17], pyDCA [18]                      |
| Lab.12 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/lab12_abinitioRosetta.ipynb) | Protein folding ab initio using Rosetta                                             | pyRosetta [1], Biopython [4], py3Dmol [5]                         
| Lab.13 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/2021/lab13_protDCASBM.ipynb) | Combining DCA and SBM to predict protein structures | SMOG2, SBM-enhanced GROMACS [3], Biopython [4], py3Dmol [5], pyDCA [18]                          |
| Lab.14 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/2023/lab14_MSAtransformer.ipynb) | Combining MSA Transformer and SBM to predict protein structures | SMOG2, SBM-enhanced GROMACS [3], Biopython [4], py3Dmol [5], MSA Transformer    
| Lab.15 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bigbiolab/ColabMDS/blob/master/labs/2022/lab15_CF-GROMACS.ipynb) | Combining ColabFold and GROMACS to predict and simulate protein structures | GROMACS [2], Biopython [4], py3Dmol [5], NGL Viewer [6], ColabFold [19]      |

---
## Software References

1.  Chaudhury S, Lyskov S, Gray JJ. PyRosetta: a script-based interface for implementing molecular modeling algorithms using Rosetta. *Bioinformatics*. 2010;26:689–91. [doi:10.1093/bioinformatics/btq007](https://doi.org/10.1093/bioinformatics/btq007).
2.  Abraham MJ, Murtola T, Schulz R, Páll S, Smith JC, Hess B, et al. GROMACS: High performance molecular simulations through multi-level parallelism from laptops to supercomputers. *SoftwareX*. 2015;1–2:19–25. [doi:10.1016/j.softx.2015.06.001](https://doi.org/10.1016/j.softx.2015.06.001).
3.  Noel JK, Levi M, Raghunathan M, Lammert H, Hayes RL, Onuchic JN, et al. SMOG 2: A Versatile Software Package for Generating Structure-Based Models. *PLOS Comput Biol*. 2016;12:e1004794. [doi:10.1371/journal.pcbi.1004794](https://doi.org/10.1371/journal.pcbi.1004794).
4.  Cock PJA, Antao T, Chang JT, Chapman BA, Cox CJ, Dalke A, et al. Biopython: freely available Python tools for computational molecular biology and bioinformatics. *Bioinformatics*. 2009;25:1422–3. [doi:10.1093/bioinformatics/btp163](https://doi.org/10.1093/bioinformatics/btp163).
5.  Rego N, Koes D. 3Dmol.js: molecular visualization with WebGL. *Bioinformatics*. 2015;31:1322–4. [doi:10.1093/bioinformatics/btu829](https://doi.org/10.1093/bioinformatics/btu829).
6.  Rose AS, Hildebrand PW. NGL Viewer: a web application for molecular visualization. *Nucleic Acids Res*. 2015;43:W576–9. [doi:10.1093/nar/gkv402](https://doi.org/10.1093/nar/gkv402).
7.  Grüning B, Dale R, Sjödin A, Chapman BA, Rowe J, Tomkins-Tinch CH, et al. Bioconda: sustainable and comprehensive software distribution for the life sciences. *Nat Methods*. 2018;15:475–6. [doi:10.1038/s41592-018-0046-7](https://doi.org/10.1038/s41592-018-0046-7).
8.  Katoh K, Standley DM. MAFFT Multiple Sequence Alignment Software Version 7: Improvements in Performance and Usability. *Mol Biol Evol*. 2013;30:772–80. [doi:10.1093/molbev/mst010](https://doi.org/10.1093/molbev/mst010).
9.  Darriba Di, Posada D, Kozlov AM, Stamatakis A, Morel B, Flouri T. ModelTest-NG: A New and Scalable Tool for the Selection of DNA and Protein Evolutionary Models. *Mol Biol Evol*. 2020;37:291–4. [doi:10.1093/molbev/msz189](https://doi.org/10.1093/molbev/msz189).
10. Kozlov AM, Darriba D, Flouri T, Morel B, Stamatakis A. RAxML-NG: a fast, scalable and user-friendly tool for maximum likelihood phylogenetic inference. *Bioinformatics*. 2019;35:4453–5. [doi:10.1093/bioinformatics/btz305](https://doi.org/10.1093/bioinformatics/btz305).
11. Webb B, Sali A. Comparative Protein Structure Modeling Using MODELLER. *Curr Protoc Bioinforma*. 2014;47:5.6.1-5.6.32. [doi:10.1002/0471250953.bi0506s47](https://doi.org/10.1002/0471250953.bi0506s47).
12. O’Boyle NM, Banck M, James CA, Morley C, Vandermeersch T, Hutchison GR. Open Babel: An open chemical toolbox. *J Cheminform*. 2011;3:33. [doi:10.1186/1758-2946-3-33](https://doi.org/10.1186/1758-2946-3-33).
13. Dolinsky TJ, Czodrowski P, Li H, Nielsen JE, Jensen JH, Klebe G, et al. PDB2PQR: expanding and upgrading automated preparation of biomolecular structures for molecular simulations. *Nucleic Acids Res*. 2007;35 Web Server:W522–5. [doi:10.1093/nar/gkm276](https://doi.org/10.1093/nar/gkm276).
14. Morris GM, Huey R, Lindstrom W, Sanner MF, Belew RK, Goodsell DS, et al. AutoDock4 and AutoDockTools4: Automated docking with selective receptor flexibility. *J Comput Chem*. 2009;30:2785–91. [doi:10.1002/jcc.21256](https://doi.org/10.1002/jcc.21256).
15. Trott O, Olson AJ. AutoDock Vina: Improving the speed and accuracy of docking with a new scoring function, efficient optimization, and multithreading. *J Comput Chem*. 2010;31:455–61. [doi:10.1002/jcc.21334](https://doi.org/10.1002/jcc.21334).
16. Michaud-Agrawal N, Denning EJ, Woolf TB, Beckstein O. MDAnalysis: A toolkit for the analysis of molecular dynamics simulations. *J Comput Chem*. 2011;32:2319–27. [doi:10.1002/jcc.21787](https://doi.org/10.1002/jcc.21787).
17. Nawrocki EP, Kolbe DL, Eddy SR. Infernal 1.0: inference of RNA alignments. *Bioinformatics*. 2009;25:1335–7. [doi:10.1093/bioinformatics/btp157](https://doi.org/10.1093/bioinformatics/btp157).
18. Zerihun MB, Pucci F, Peter EK, Schug A. pydca v1.0: a comprehensive software for direct coupling analysis of RNA and protein sequences. *Bioinformatics*. 2020;36:2264–5. [doi:10.1093/bioinformatics/btz892](https://doi.org/10.1093/bioinformatics/btz892).
19. Mirdita M, Schütze K, Moriwaki Y, Heo L, Ovchinnikov S, Steinegger M. ColabFold: making protein folding accessible to all. *Nature Methods*. 2022;19:679–682. [doi:10.1038/s41592-022-01488-1](https://doi.org/10.1038/s41592-022-01488-1). 

---
## Tutorial References

1.  Abraham, M. J., Murtola, T., Schulz, R., Páll, S., Smith, J. C., Hess, B., & Lindahl, E. (2015). GROMACS: High performance molecular simulations through multi-level parallelism from laptops to supercomputers. *SoftwareX*, 1, 19-25. [doi:10.1016/j.softx.2015.06.001](https://doi.org/10.1016/j.softx.2015.06.001).
2.  Arantes, P. R., Polêto, M. D., Pedebos, C., & Ligabue-Braun, R. (2021). Making it Rain: Cloud-Based Molecular Simulations for Everyone. *Journal of Chemical Information and Modeling*, 61(10), 4852–4856. [doi:10.1021/acs.jcim.1c00998](https://doi.org/10.1021/acs.jcim.1c00998).
3.  Engelberger, F., Galaz-Davison, P., Bravo, G., Rivera, M., & Ramírez-Sarmiento, C. A. (2021). Developing and Implementing Cloud-Based Tutorials That Combine Bioinformatics Software, Interactive Coding, and Visualization Exercises for Distance Learning on Structural Bioinformatics. *J. Chem. Educ.*, 98(5), 1801–1807. [doi:10.1021/acs.jchemed.1c00022](https://doi.org/10.1021/acs.jchemed.1c00022).
4.  Gowers, R. J., Linke, M., Barnoud, J., Reddy, T. J. E., Melo, M. N., Seyler, S. L., Dotson, D. L., Domanski, J., Buchoux, S., Kenney, I. M., & Beckstein, O. (2016). MDAnalysis: A Python package for the rapid analysis of molecular dynamics simulations. In S. Benthall & S. Rostrup (Eds.), *Proceedings of the 15th Python in Science Conference* (pp. 98-105). Austin, TX: SciPy. [doi:10.25080/majora-629e541a-00e](https://doi.org/10.25080/majora-629e541a-00e).
5.  Lemkul, J. A. (2019). From Proteins to Perturbed Hamiltonians: A Suite of Tutorials for the GROMACS-2018 Molecular Simulation Package [Article v1.0]. *Living J. Comput. Mol. Sci.*, 1(1), 5068. [doi:10.33011/LIVECOMS.1.1.5068](https://doi.org/10.33011/LIVECOMS.1.1.5068).