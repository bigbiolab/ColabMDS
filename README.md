
# Cloud-Based Molecular Dynamics Simulations Using GROMACS: A Practical Workflow on Google Colab

1.  **Colab gmx Installation** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulshamrat/ColabMDA/blob/main/notebooks/04-colab-gmx-install.ipynb) ``` Installing GROMACS 2023x for MD simulations in Colab. ``` 

2.  **Colab MD Simulation 2024** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulshamrat/ColabMDA/blob/main/notebooks/05-colabmd-simulation-2024.ipynb) ``` Performing MD simulation with GROMACS in Colab. ``` 

03. **Colab MD Analysis** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulshamrat/ColabMDA/blob/main/notebooks/03-colabmd-analysis.ipynb) ``` Using MDAnalysis and MDtraj to perform MD trajectory analysis. ```

![](https://github.com/bigbiolab/ColabMDS/blob/main/images/flowchart.png)


## Summary
This GitHub repository presents a customized and enhanced workflow for conducting Molecular Dynamics (MD) simulations using GROMACS on Google Colab, designed to facilitate accessible, reproducible, and cloud-based molecular modeling. The project builds upon and significantly extends the functionalities of the original repository [ColabMDA](https://github.com/paulshamrat/ColabMDA), which provided a foundational framework for executing GROMACS simulations in a Jupyter Notebook environment.

This modified version incorporates additional flexibility, improved user guidance, and workflow adaptations tailored to support the supplementary computational analyses associated with the following peer-reviewed publication: ([Molecular dynamics simulation of wild and mutant proteasome subunit beta type 8 (PSMB8) protein: Implications for restoration of inflammation in experimental autoimmune encephalomyelitis pathogenesis](https://www.sciencedirect.com/science/article/pii/S2405844024171976)).

The repository serves multiple purposes:
- It provides a cloud-optimized Jupyter Notebook interface that eliminates the need for local high-performance computing resources, thereby democratizing access to MD simulations.
- It reproduces the simulation pipeline used in the above publication, which analyzed the structural and dynamic consequences of pathogenic mutations in the PSMB8 protein, a key subunit of the immunoproteasome involved in inflammatory signaling pathways and autoimmune neurodegeneration (EAE model).
- It acts as a pedagogical resource for training purposes, supporting researchers and students in computational biology, structural bioinformatics, and translational immunology.

The repository contains:
- Updated bash scripts and Python cells for installing and running GROMACS on Google Colab.
- Documentation to guide users through protein preparation, solvation, energy minimization, equilibration, and production MD steps.
- Optional modules for trajectory analysis, RMSD/RMSF plotting, and data export for downstream interpretation.


---

**Acknowledgement:**

We would like to thanks the authors who developed jupyter notebook framework for molecular dynamics simulation on google colab. Please always refer the original GROMACS manual for the simulaiton guide. We are grateful to the Authors of the follwoing article which made possible to adapt this md simulation protocol.

- F. Engelberger, P. Galaz-Davison, G. Bravo, M. Rivera, and C. A. Ramírez-Sarmiento, “Developing and Implementing Cloud-Based Tutorials That Combine Bioinformatics Software, Interactive Coding, and Visualization Exercises for Distance Learning on Structural Bioinformatics,” J. Chem. Educ., vol. 98, no. 5, pp. 1801–1807, May 2021, doi: 10.1021/acs.jchemed.1c00022.

- J. A. Lemkul, “From Proteins to Perturbed Hamiltonians: A Suite of Tutorials for the GROMACS-2018 Molecular Simulation Package [Article v1.0],” Living J. Comput. Mol. Sci., vol. 1, no. 1, pp. 5068–5068, 2019, doi: 10.33011/LIVECOMS.1.1.5068.

- P. R. Arantes, M. D. Polêto, C. Pedebos, and R. Ligabue-Braun, “Making it Rain: Cloud-Based Molecular Simulations for Everyone.,” Journal of chemical information and modeling, vol. 61, no. 10. United States, pp. 4852–4856, Oct. 2021. doi: 10.1021/acs.jcim.1c00998.

- R. J. Gowers, M. Linke, J. Barnoud, T. J. E. Reddy, M. N. Melo, S. L. Seyler, D. L. Dotson, J. Domanski, S. Buchoux, I. M. Kenney, and O. Beckstein. MDAnalysis: A Python package for the rapid analysis of molecular dynamics simulations. In S. Benthall and S. Rostrup, editors, Proceedings of the 15th Python in Science Conference, pages 98-105, Austin, TX, 2016. SciPy, doi:10.25080/majora-629e541a-00e.

- Gowers, R. J., Linke, M., Barnoud, J., Reddy, T. J., Melo, M. N., Seyler, S. L., ... & Beckstein, O. (2016, July). MDAnalysis: a Python package for the rapid analysis of molecular dynamics simulations. In Proceedings of the 15th python in science conference (Vol. 98, p. 105). Austin, TX: SciPy.

- Abraham, M. J., Murtola, T., Schulz, R., Páll, S., Smith, J. C., Hess, B., & Lindahl, E. (2015). GROMACS: High performance molecular simulations through multi-level parallelism from laptops to supercomputers. SoftwareX, 1, 19-25.


All these datasets are uploaded as 
Paper:
**Dataset of Molecular Dynamics Simulations for the Upregulated Biomarker PSMB8: 3UNF and its G210V Mutant in Experimental Autoimmune Encephalomyelitis.** 
[![Molecular dynamics simulation of wild and mutant proteasome subunit beta type 8 (PSMB8) Protein: Implications for restoration of inflammation in experimental autoimmune encephalomyelitis pathogenesis](https://zenodo.org/badge/DOI/10.5281/zenodo.8070983.svg)](https://www.sciencedirect.com/science/article/pii/S2405844024171976?via%3Dihub)

Dataset:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8070983.svg)](https://zenodo.org/records/8157201)

*Last tested on: 2025-05-05*
