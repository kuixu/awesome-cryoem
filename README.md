# Awesome CryoEM
A collaborative list of awesome CryoEM (Electron Cryo-Microscopy) resources. Feel free to contribute!

<img src="imgs/cryoem1.png" width = "360px" height = "180px" alt="Cryo-EM" />

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

### Contributing

Please take a quick look at the [contribution guidelines](.github/CONTRIBUTING.md) first. If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you to all [contributors](https://github.com/barrykui/awesome-cryoem/graphs/contributors); you rock!

### Contents

- [Guides](#guides)
    - [Official Guides](#official-guides)
    - [Third party Guides](#third-party-guides)
- [Softwares](#softwares) 
- [Technologies](#technologies)
- [Computational Problems](#computational-problems)
- [Validation Metrics](#validation-metrics)
- [DataBases](#database)
- [Active Groups](#active-groups)


## Guides
*An awesome list of CryoEM related guides.* 




### Official Guides
[back to top](#readme) 

* [3 Mins Introduction of CryoEM](#) - 3 Mins Introduction of CryoEM for beginners.
* [Single-particle cryo-electron microscopy](http://www.nature.com/nmeth/journal/v13/n1/full/nmeth.3700.html) - 
* [Single-particle cryo-electron microscopy](http://www.nature.com/nmeth/journal/v13/n1/full/nmeth.3700.html) - 

### Third party Guides
[back to top](#readme) 

* [EMAN2 Video Tutorials](http://blake.bcm.edu/emanwiki/EMAN2/VideoTutorials)

## Softwares
[back to top](#readme) 

* [UCSF Chimera](https://www.cgl.ucsf.edu/chimera/) - An interactive visualization and analysis of structures.
* [Relion](http://www2.mrc-lmb.cam.ac.uk/relion/index.php/Main_Page) - A Bayesian approach to refinement of 3D reconstructions or 2D class averages.
    * [`New` 2.1 ](ftp://ftp.mrc-lmb.cam.ac.uk/pub/scheres/relion21_tutorial.pdf) - Tutorial (v2.1) (The quickest way to learning RELION) 
    * [Nature Protocol Paper](http://www.nature.com/nprot/journal/v11/n11/full/nprot.2016.124.html) - Resolving macromolecular structures from electron cryo-tomography data using subtomogram averaging in RELION

* [COOT](http://www2.mrc-lmb.cam.ac.uk/personal/pemsley/coot/) - A interactive visualization model building, model completion and validation.
* [EMAN2](http://blake.bcm.edu/emanwiki/EMAN2) - A scientific image processing software suite with a focus on CryoEM and CryoET.
* [PHENIX](https://www.phenix-online.org/) - Automated determination of molecular structures using X-ray crystallography and other methods.
* [Rosetta](https://www.rosettacommons.org/) - A software suite includes algorithms for computational modeling and analysis of protein structures.
    * [RosettaCM](http://www.sciencedirect.com/science/article/pii/S0969212613002979?via%3Dihub) - High-Resolution Comparative Modeling with RosettaCM
    * [RosettaES](http://www.nature.com/nmeth/journal/v14/n8/full/nmeth.4340.html) - RosettaES: a sampling strategy enabling automated interpretation of difficult cryo-EM maps(2017) 
* [FREALIGN: high-resolution refinement of single particle structures](#)
* [SIMPLE: Software for ab initio reconstruction of heterogeneous single-particles](#)
* [PRIME: probabilistic initial 3D model generation for single-particle cryo-electron microscopy](#)
* [SPIDER](http://spider.wadsworth.org) - System for Processing Image Data from Electron microscopy and Related fields.
* [CCP4](http://www.ccp4.ac.uk/) - Collaborative Computational Project No. 4 Software for Macromolecular X-Ray Crystallography.
    * [Buccaneer](#)
    * [SFTOOLS](#)
* [ResMap](http://resmap.sourceforge.net/) - computing the local resolution of 3D density maps.
* [DeepPicker](https://arxiv.org/abs/1605.01838) - Fully Automated Particle Picking using deep learning.
* [FindEM](http://www.ccpem.ac.uk/ccpem_projects.php) - CCP-EM projects, automated particle picking from electron micrographs, using Fortran
* [EMfold](http://www.meilerlab.org/index.php/servers/show?s_id=18) - Meiler Lab,  placement of helices is restricted to CryoEM density regions.
* [De novo protein structure determination from near-atomic-resolution cryo-EM maps](http://www.nature.com/doifinder/10.1038/nmeth.3287)
* [Atomic accuracy models from 4.5 Å cryo-electron microscopy data with density-guided iterative local refinement](http://www.nature.com/doifinder/10.1038/nmeth.3286)
* [cryoSPARC: algorithms for rapid unsupervised cryo-EM structure determination](http://www.nature.com/nmeth/journal/v14/n3/full/nmeth.4169.html)
    * [Building proteins in a day: Efficient 3D molecular reconstruction(CVPR2015)](#)
* [Pathwalker](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3307788/pdf/nihms350767.pdf) - Constructing and Validating Initial Cα Models from Subnanometer Resolution Density Maps with Pathwalking, TSP
* [EMBuilder](https://www.nature.com/articles/s41598-017-02725-w) - EMBuilder: A Template Matching-based Automatic Model-building Program for High-resolution Cryo-Electron Microscopy Maps

## Technologies
[back to top](#readme) 

* [Single Particle](#)
* [Tomography](#)
* [MircoED](#)

## Computational Problems
[back to top](#readme) 

* Particle Picking
    * Fully Automatic
      * [DeepPicker](https://arxiv.org/abs/1605.01838) - Fully Automated Particle Picking using deep learning.
      * [FindEM](http://www.ccpem.ac.uk/ccpem_projects.php) - CCP-EM projects, automated particle picking from electron micrographs, using Fortran
      * [DeepEM](http://arxiv.org/pdf/1605.05543v1.pdf) - A deep learning approach to single-particle recognition in cryo-electron microscopy,Yanan Zhu, Qi Ouyang, Youdong Mao.
    * Semi Automatic
* 2D Classification
* 3D Classification
    * [Relion](www2.mrc-lmb.cam.ac.uk/relion/index.php/Main_Page) - A Bayesian approach to refinement of 3D reconstructions or 2D class averages.
    * [cryoSPARC](http://www.nature.com/nmeth/journal/v14/n3/full/nmeth.4169.html) - cryoSPARC: algorithms for rapid unsupervised cryo-EM structure determination
    * [AuTom](http://www.sciencedirect.com/science/article/pii/S1047847717301284) - AuTom: A novel automatic platform for electron tomography reconstruction 

* Motion Correction
    * [Electron counting and beam-induced motion correction enable near-atomic-resolution single-particle cryo-EM](http://www.nature.com/nmeth/journal/v10/n6/full/nmeth.2472.html) - Xueming Li's work.  

* CTF Correction
* Model Building
    * [EMAN2](http://blake.bcm.edu/emanwiki/EMAN2) - A scientific image processing software suite with a focus on CryoEM and CryoET.
    * [PHENIX](https://www.phenix-online.org/) - Automated determination of molecular structures using X-ray crystallography and other methods.
    * [Rosetta](https://www.rosettacommons.org/) - A software suite includes algorithms for computational modeling and analysis of protein structures.
    * [De novo protein structure determination from near-atomic-resolution cryo-EM maps](http://www.nature.com/doifinder/10.1038/nmeth.3287)
    * [Atomic accuracy models from 4.5 Å cryo-electron microscopy data with density-guided iterative local refinement](http://www.nature.com/doifinder/10.1038/nmeth.3286)
    * [EMfold](http://www.meilerlab.org/index.php/servers/show?s_id=18) - Meiler Lab,  placement of helices is restricted to CryoEM density regions.
    * SSE based methods.
    * Backbone tracing methods.
    * [Pathwalker](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3307788/pdf/nihms350767.pdf) - Constructing and Validating Initial Cα Models from Subnanometer Resolution Density Maps with Pathwalking, TSP
    * [EMBuilder](https://www.nature.com/articles/s41598-017-02725-w) - EMBuilder: A Template Matching-based Automatic Model-building Program for High-resolution Cryo-Electron Microscopy Maps
    * [Book chapter, Review](https://www.sciencedirect.com/science/article/pii/S0076687916301136?via%3Dihub) - Tools for Model Building and Optimization into Near-Atomic Resolution Electron Cryo-Microscopy Density Maps
* Model Validation

## Validation Metrics
[back to top](#readme) 

* [RMSD](https://en.wikipedia.org/wiki/Root-mean-square_deviation_of_atomic_positions) - Root Mean Square Deviation
* [FSC](https://en.wikipedia.org/wiki/Fourier_shell_correlation) - Fourier shell correlation.
* [B-factor](http://www.cmbi.ru.nl/bdb/theory/) -  A measure of (local) mobility in the (macro)molecule.
* [GDT-HA](http://onlinelibrary.wiley.com/doi/10.1002/prot.21753/full) - The percentage of correctly aligned residues in the 5 Å LGA sequence-independent superposition of the model and experimental structure of the target.
* [GDT-TS](#)
* [AL0](#)

## DataBases
[back to top](#readme) 

* [EMDB](https://www.ebi.ac.uk/pdbe/emdb/index.html) - The Electron Microscopy Data Bank (EMDB)
* [EMPIAR](https://www.ebi.ac.uk/pdbe/emdb/empiar) - EMPIAR, the Electron Microscopy Pilot Image Archive, is a public resource for raw, 2D electron microscopy images.
    * [EMPIAR: a public archive for raw electron microscopy image data](http://www.nature.com/doifinder/10.1038/nmeth.3806)
* [PDB](http://www.rcsb.org/pdb/home/home.do) - Protein Data Bank
* [PDBe](http://www.ebi.ac.uk/pdbe) - Protein Data Bank in Europe
* [PDBj](http://www.pdbj.org) - Protein Data Bank Japan 
* [wwPDB](http://www.wwpdb.org) - WorldWide Protein Data Bank 
* [sbkb](http://www.sbkb.org) - Structural Biology Knowledgebase, A comprehensive resource for developments both in structural genomics and structural biology.


## Active Groups

* [MRC](http://www2.mrc-lmb.cam.ac.uk/) - MRC Laboratory of Molecular Biology
    * [Richard Henderson](http://www2.mrc-lmb.cam.ac.uk/group-leaders/h-to-m/richard-henderson/) - Richard Henderson Lab (**The Nobel Prize in Chemistry 2017**)
    * [Scheres](http://www2.mrc-lmb.cam.ac.uk/groups/scheres/) - Relion Author. 
* [Joachim Frank](http://franklab.cpmc.columbia.edu/franklab) -  Franklin Lab (**The Nobel Prize in Chemistry 2017**)
* [Bob Glaeser](http://mcb.berkeley.edu/faculty/all/glaeserr) - Single-particle electron cryo-microscopy.
* [Yifan Cheng](http://cryoem.ucsf.edu/) - TRPA1.
* [Yigong Shi](http://ygshi.life.tsinghua.edu.cn/home.htm) - Spliceosome, pre-mRNA splicing, γ-Secretase, Apoptosis.
* [Eva Nogales](http://cryoem.berkeley.edu/) - CryoEM. 
* [David Baker](http://www.ipd.uw.edu/people/ipd-faculty-staff/david-baker/) - Rosetta.
* [Frank DiMaio](https://faculty.washington.edu/dimaio/wordpress/) - CryoEM model building.
* [Xueming Li](http://life.tsinghua.edu.cn/faculty/faculty/2730.html) - Motion Correction.
* [Marcus Brubakero](http://www.cs.toronto.edu/~mbrubake/) - CryoEM 3D Molecular Reconstruction, Machine Learning, CVPR 2015.
* [Meiler Lab](http://www.meilerlab.org/index.php) - Computational Chemical and Structural Biology, `EMfold`.
* [Sriram Subramaniam](https://electron.nci.nih.gov/publications)

[3D-EM Laboratories](http://3dem.ucsd.edu/labs_a_c.shtm)


## Workshop Docs

* [EMAN2 ](http://blake.bcm.edu/emanwiki/EMAN2/Tutorials)
* [Resource from Meiler Lab](http://www.meilerlab.org/index.php/jobs/resources) - Rosetta Tutorials, Teaching Resources, etc.

## Websites

* [Software Tools For Molecular Microscopy](http://en.wikibooks.org/wiki/Software_Tools_For_Molecular_Microscopy)
* [3D-EM Laboratories](http://3dem.ucsd.edu/labs_a_c.shtm)


## TODO
- [x] more paper(from David Baker) to read;
- [x] more usefull tools should be added in;
- [x] SSE prediction based model building methods.
- [x] [De Novo modeling in cryo-EM density maps with Pathwalking](https://www.ncbi.nlm.nih.gov/pubmed/27436409).
- [x] [3.9 Å structure of the nucleosome core particle determined by phase-plate cryo-EM](https://www.ncbi.nlm.nih.gov/pubmed/27563056)
- [x] [Automated structure refinement of macromolecular assemblies from cryo-EM maps using Rosetta](http://biorxiv.org/content/biorxiv/early/2016/04/26/050286.full.pdf)



## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Kui Xu](https://github.com/barrykui) has waived all copyright and related or neighboring rights to this work.
