**INTRODUCTION**

The type 1 insulin-like growth factor receptor (IGF1R) is a class II receptor tyrosine kinase (RTK), belonging to the insulin receptor family, that plays critical roles in cell growth and differentiation and can be activated by IGF1, IGF2, and insulin(Jie Li et al., 2019) Dysregulation of IGF1R has been implicated in human diseases, including both growth retardation and cancers (Arcaro.,2013) IGF1R is particularly important in the establishment and maintenance of the transformed phenotype, in mediating proliferation, and in the survival of tumor cells with anchorage-independent growth. IGF1R also exerts antiapoptotic  activity and has a substantial influence on the control of the cell and [body size](https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/body-size), enabling transformed cells to form macroscopic tumors and to survive the process of detachment required for metastasis (Carmen and Carlos, 2022). The binding site of the IGF1R protein is ATP(Adenosine triphosphate. This report uses IGF1R as a case study in evaluating the conformation of predicted homology and AlphaFold modeling

**Methodology**

IGFR1 in Apo, Agonist and Antagonist forms was retrieved from the PDB(Protein Data Bank) with the ID 1P40, which is the Apo unactivated, 6PYH for the agonist and 3LVP for the Antagonist forms. Their FASTA sequence was collected. 

- Homology modeling (SWISS-MODEL) was carried out for each form of the protein using the sequence stated above.

* AlphaFold Model was downloaded from their database as it had already been predicted.

* Visualization of the structures using Pymol was done. The modeled structures were compared to the crystal structures on PDB using align and RMSD measurements

**Results**

The RMSD analysis of the IGF1R proteins revealed that the AlphaFold Conformation of this protein is Apo because the value obtained when compared to the Swiss model is lower. Below are the Executive RMSD values of the comparisons between the AlphaFold and the Swiss model of the proteins in different forms.

AlphaFold versus Apo IGF1R,  RMSD = 1.014 (1926 to 1926 atoms)

Swiss versus Apo IGF1R, 

 RMSD =   25.447 (2258 to 2258 atoms)

AlphaFold versus Antagonist IGF1R,  RMSD =    1.083 (1748 to 1748 atoms) 

Swiss versus Antagonist IGF1R,  RMSD =   19.736 (1313 to 1313 atoms)

AlphaFold versus Agonist IGF1R,  RMSD =    8.943 (5212 to 5212 atoms) 

Swiss Versus Agonist IGF1R,  RMSD =   18.810 (10559 to 10559 atoms) 

**Discussion** 

The two Modeling techniques were evaluated in this study and it could be inferred that the Deep learning based model-Alphafold, provided a lower RMSD value of 1.014 which has an Apo conformation and is a more accurate model which can be relied on when a template is available while the Swiss model gave a less accurate model with a RMSD value of 18.810 with an Agonist conformation and it can be used when template access is unavailable. 

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXc_LEA1fw_kJaA1dyeLTR4KVVllym_5QPEiEjDRZ7bPOyxw9DKvSTbVaY9elwp6iMQ9SMIBpKzilYvCAU922_sb0CDCtv1pTUpCDqbDlQSCWDeIHwQjZwizZWXlQiDfHPnKXDw-T2EEp0t0Rk1lhiHZ9yEU?key=Fa1xiTQHd0grh7ITfhJq9w)

Agonist IGF1R 

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeJ7Hj_9q_kmBsBheEG7_6PqZaRW8P-MULBYCG6BPp5TsxnORskTL2-PMlwc7Sr_ThAiPCsSBN1eJeSyec0zt5wmDkORW6T4-HhhMmdsrTRxPi7rIztt9Tk2_wvoLKNXXYlQxLXHrsl2B57UMsMAyn721Du?key=Fa1xiTQHd0grh7ITfhJq9w)  

Antagonist IGF1R 

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXc0geMspfKGzNH43aKgmv3WKRBnL596a0jLY4aUm8FFO1srzLhskpMEUfWGJ1NNYWoJpRvXEgYcuEp_msnRsaLPRPNE3w4_lht7jDfMuho88jOaijYu1hJ--4eVzH3AbX_uqH732vEzbbalZhltvcRzAHAT?key=Fa1xiTQHd0grh7ITfhJq9w)

Apo IGF1R           

\


******References**

1. Jie L., Eunhee C., Hongtao Y., and Xiao Chen B.(2019) Structural Basis of the type 1 Insulin -like growth factor receptor. _Nature Communication_ 10, 4567. https\://doi.org/10.1038/s41467-019-12564-0

2. Carmen A., and Carlos M.(2022) Therapeutic peptidomimetics for cancer treatment.  Academic Press, Pages 473-505,ISBN 9780128201411,https\://doi.org/10.1016/B978-0-12-820141-1.00010-8.

3.  Arcaro, A. (2013). Targeting the insulin-like growth factor-1 receptor in human cancer. Front Pharm. 4, 30.
