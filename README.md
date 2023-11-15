# MPhilThesis
This is the MPhil thesis of Yang Zhang, supervised by Dr. Richard Bryce and Dr. Neil Burton at the University of Manchester.

## Thesis Title
Simulation of protein dynamics for mechanistic insight and drug design

## Abstract
Wnt pathway is a key cellular signal responsible for carcinogenesis and embryonic development. Excessive Wnt signal induces intracellular accumulation of beta-catenin which improves DNA replication and cell abnormal proliferation. 

R-spondin is an essential fine-tuning signal for Wnt signal; studies have suggested that it could perform as a hinge to connect E3 Ubiquitin ligase RNF43 and LGR5 protein with high affinity and then promote the elimination of RNF43 in the cell surface. RNF43 is responsible for the degradation of the Wnt receptor, and with too much R-spondin signal, the degradation of the Wnt receptor is inhibited and Wnt strength is improved which would cause significant cell abnormal proliferation. With the aim of modulating R-spondin interactions, we firstly examined the druggability of R-spondin, LGR5 and RNF43 through energy-based and shape-based binding pocket prediction methodologies; we find that RNF43 and R-spondin in an open conformation (which we call "Open2") are predicted as highly druggable. After refining 1.3 billion compounds to 20.7 million, molecular docking of this subset was performed against these proteins, based on their drug binding site information. Ninety-three top-ranked compounds were then simulated by molecular dynamics: 43 of these compounds were successfully identified that could bind well with their corresponding protein structures. We then performed free energy calculations and energy decomposition to quantify the binding affinity and energy contribution of each residue in these complexes. 

This research aims to identify compounds that could potentially inhibit the binding between R-spondin, RNF43 and LGR5 in order to probe its anti-cancer activity. From binding pocket identification and molecular dynamics (MD) simulation, RNF43 is predicted to be the most druggable among the protein structures. In our ligand optimization process, increasing the hydrophobicity of a compound to promote binding with the upper cavity on RNF43 could dramatically increase the binding stability of the ligand. An observation also occurred in the simulation of compounds bound to protein LGR5, as benzonitrile and chlorobenzene group tend to form highly stable hydrophobic interactions with the Trp168/Thr192 cavity on LGR5. 

The binding stability of compounds to the Closed conformation of R-spondin is aided by Cys94 hydrogen bond interactions and by hydrophobic residues including Ile63, Leu63 and Leu64. However, Closed R-spondin is sensitive to the length of ligand, as many compounds with different length were tested and only limited length molecules succeeded. 

The cavity on Open2 R-spondin is deep but unstable: in some simulations, the cavity was not stable enough to sustain interactions. Three groups of residues including residues near Leu64 (Furin-like 1 domain), Cys94 (hinge area) and Glu103 (Furin-like 2 domain) are important for the maintenance of Open2 R-spondin and ligand binding stability. 

In conclusion, this study provides insight into the structure, energy and dynamics of ligands targeting four R-spondin signalling related protein structures; and can provide valuable input into the choice and design of inhibitors of Wnt signalling, as chemical tools and potential drug molecules.

## Access 
I recommend accessing the dissertation directly via the University of Manchester's Research Information Management System:

[eScholar](https://www.escholar.manchester.ac.uk/uk-ac-man-scw:323328)

[PURE](https://research.manchester.ac.uk/en/studentTheses/simulation-of-protein-dynamics-for-mechanistic-insight-and-drug-d)

Other resources:

[Google Scholar](https://scholar.google.com/scholar?q=Simulation+of+protein+dynamics+for+mechanistic+insight+and+drug+design)

[ProQuest](https://www.proquest.com/docview/2568539566)

[Copy in this repo](Thesis.pdf)

## Citation
```
@phdthesis{zhang2020simulation,
  title={Simulation of protein dynamics for mechanistic insight and drug design},
  author={Zhang, Yang},
  year={2020},
  school={The University of Manchester (United Kingdom)}
}
```

## License
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://research.manchester.ac.uk/en/studentTheses/simulation-of-protein-dynamics-for-mechanistic-insight-and-drug-d">Simulation of protein dynamics for mechanistic insight and drug design</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://miemiemmmm.github.io/">Yang Zhang</a> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a></p>

