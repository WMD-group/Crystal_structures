# Crystal_Structures

A collection of crystal structures from first-principles simulations of functional materials.

BiVO4
=====
Crystal structure of bismuth vanadate. Taken from ICSD record #33243 (1983). Note that the structure was originally reported in a non-standard setting (the monoclinic angle is set to gamma). To make more compatible with the lattice symmetry in VASP, the cell was transformed into a standard C2/C setting (the cell volume remains unchanged, but the monoclinic angle becomes beta). In some publications, the angles of gamma and beta are erroneously switched. 

#####Used in
- "Band Edge Electronic Structure of BiVO: Elucidating the Role of the Bi s and V d Orbitals" [Chemistry of Materials (2009)](http://pubs.acs.org/doi/abs/10.1021/cm802894z) 
- "The nature of electron lone pairs in BiVO4" [Applied Physics Letters (2011)](http://scitation.aip.org/content/aip/journal/apl/98/21/10.1063/1.3593012)


Kesterites
=====
Crystal structures for the kesterite and stannite forms of Cu2ZnSnS4 (CZTS). The structures were optimised using the PW91 (2009 data) or PBEsol (2015 data) exchange-correlation functional. Note that these files correspond to the conventional unit cells (16 atoms per cell), while a primitive cell (8 atoms per cell) also exists. 

#####Used in
- "Crystal and electronic band structure of Cu2ZnSnX4 (X=S and Se) photovoltaic absorbers: First-principles insights" [Applied Physics Letters (2009)](http://scitation.aip.org/content/aip/journal/apl/94/4/10.1063/1.3074499)
- "Wurtzite-derived polytypes of kesterite and stannite quaternary chalcogenide semiconductors" [Physical Review B (2010)](http://journals.aps.org/prb/abstract/10.1103/PhysRevB.82.195203)
- "Ab initio thermodynamic model of Cu2ZnSnS4" [Journal of Materials Chemistry A (2014)](http://pubs.rsc.org/en/Content/ArticleLanding/2014/TA/c4ta00892h#!divAbstract)


Spinels
=====
Normal and inverse spinel structures (fcc primitive unit cells). The normal spinel structure is an ordered lattice of A(tetrahedral)B(octahedral)2O4, while the inverse spinel structure is a disordered lattice of B(tetrahedral)AB(octahedral)O4. Site disorder in the inverse structure requires special treatment: we generated a representative structure using the SQS method (see http://www.brown.edu/Departments/Engineering/Labs/avdw/atat/).

#####Used in
- "Structural, magnetic, and electronic properties of the Co-Fe-Al oxide spinel system: Density-functional theory calculations" [Physical Review B (2007)](http://journals.aps.org/prb/abstract/10.1103/PhysRevB.76.165119)
- "Ternary cobalt spinel oxides for solar driven hydrogen production: Theory and experiment" [Energy and Environmental Science (2009)](http://pubs.rsc.org/en/Content/ArticleLanding/2009/EE/B822903A#!divAbstract)