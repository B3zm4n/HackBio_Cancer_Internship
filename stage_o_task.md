     Autodock Vina

Introduction

Autodock vina is an open source program designed by Dr. Oleg Trott in the Molecular Graphics Lab at the Scripps Research Institute, and its used in molecular docking \[1]. Docking is the identification of the low energy binding modes of a small molecule or ligand within the active site of a macromolecule or receptor whose structure is known. It is also the computational determination of binding affinity between molecules. Simply put, its finding the binding free energy between a protein and ligand\[1]. It is designed mainly for predicting how small molecules bind to receptors of known 3D structures\[2]. 

Material and Method

How it works

For it input and output, it uses PDBQT molecular structure file format which can be generated and viewed with the use of MGLTools. All it requires is the structure of the molecule to be docked and the specification of the search space and binding site \[2]. ATD Vina take various steps to improve the quality of both input and output structures; 

• By paying attention to checking the synthatic correctness of the input structure and then reports errors to the user.

• The length of the invariance of the covalent bond is automatically verified in output structures.

• It avoids imposing restrictions on the input structure such as; size of search space, number of atoms, number of torsions, etc.

Discussion

In article “ Combining empirical knowledge, in silico molecular docking and ADMET profiling to identify therapeutic phytochemicals from Brucea antidysentrica for acute myeloid leukemia” by Lemessa Etana Bultum et. Al, they integrated traditional empirical techniques with modern computational techniques by focusing on the use of Autodock Vina for in silico molecular docking. Autodock was used to predict the binding affinity of the phytochemicals to key proteins involved in AML through which they identified compounds with strong potential to inhibit AML related targets by evaluating their binding energy and interaction patterns \[3].

Conclusion

In conclusion, we see that AutoDock Vina was played a crucial role in screening, evaluating, and identifying  the phytochemicals and compounds which might be effective in inhibiting cancer cell growth.

References

1\. O. Trott, A. J. Olson, AutoDock Vina: improving the speed and accuracy of docking with a new scoring function, efficient optimization and multithreading, Journal of Computational Chemistry 31 (2010) 455-461

2\. Morris, G. M., Goodsell, D. S., Halliday, R.S., Huey, R., Hart, W. E., Belew, R. K. and Olson, A. J. (1998), Automated Docking Using a Lamarckian Genetic Algorithm and and Empirical Binding Free Energy Function J. Computational Chemistry, 19: 1639-1662.

3\. Bultum, Lemessa Etana et al. “Combining empirical knowledge, in silico molecular docking and ADMET profiling to identify therapeutic phytochemicals from Brucea antidysentrica for acute myeloid leukemia.” PloS one vol. 17,7 e0270050. 27 Jul. 2022, doi:10.1371/journal.pone.0270050

4\.
