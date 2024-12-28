# PD-L1-Inhibitors-Through-Molecular-Docking-
Supporting materials and appendices for the study on PD-L1 inhibitors in cancer immunotherapy (ABA et al. 2025)

**ABSTRACT**
Significant progress has been made in cancer treatment, particularly with the development of innovative chemotherapeutic agents. However, the discovery and development of highly effective therapeutics remain a pressing and challenging goal, highlighting the need for continued research to address the complexities of this disease. The objective of this study is to identify new molecules capable of inhibiting the function of the Programmed Death-Ligand 1 (PD-L1) receptor. This will strengthen immunotherapeutic defense and support the immune system in the fight against tumors. The study will use molecular docking techniques, along with the prediction of pharmacokinetic properties (absorption, distribution, metabolism, excretion) and toxicity (ADMET) profiles. Molecules were retrieved from the PubChem and ChEMBL databases, and Programmed Cell Death Ligand 1 (PD-L1) was obtained from the Protein Data Bank (PDB). Molecular docking was performed using AutoDock Vina. PyMOL and Discovery Studio Visualizer (DSV) were employed for molecular visualization. The SwissADME server was used to predict the molar refractivity, saturation, and promiscuity of the hit compounds, and therapeutic chemistry criteria guided the screening process. pkCSM was utilized to assess absorption, distribution, metabolism, excretion, and toxicity (ADMET). Based on the results we identified N-phenethylcinnamamide as the most promising candidate for binding to the (PD-L1) receptor. This compound exhibits strong binding to the receptor's active site, and displays promising pharmacokinetic properties and ADMET profile, suggesting its potential for oral administration. New derivatives were designed based on the structure of N-phenethylcinnamamide to enhance its pharmacokinetic properties and led to the identification of 11 novel derivatives, three of which are phytochemical compounds. These derivatives demonstrated considerable potential as PD-L1 inhibitors, and highlighting the potential of plant-derived molecules in cancer immunotherapy development.

  **Keywords:** _ADMET · Cancer · Derivatives · Docking · Immunotherapy · Inhibitors · N-Phenethylcinnamamide · PD-1 · PD-L1 · Pharmacokinetic_

N-Phenethylcinnamamide is an organic compound that has a cinnamamide skeleton to which a phenylethyl group is bonded. This compound can exist in different isomeric forms due to the possibility of rotation around the carbon bonds in the phenylethyl group. It can also undergo various chemical modifications on its cinnamamide backbone or phenylethyl group. After optimization, Fifty-five molecules derived from the base molecule (N-Phenethylcinnamamide), and are presented in Table 1. 

**Table 1:** Fifty-five N-Phenethylcinnamamide derivatives, numbered from 2 to 56 and the base compound (N-Phenethylcinnamamide) numbered 1.

![55](https://github.com/user-attachments/assets/28eb422d-ecf0-4de9-8b51-cf000e0af7f9)


After substantial filtering, seventeen compounds were evaluated for their pharmacological properties, and eleven were identified as suitable for oral administration, supported by favorable pharmacokinetic assessments and a comprehensive ADMET profile. These eleven compounds, determined by the numerical codes 25, 43, 5, 11, 42, 55, 2, 48, 29, 3, and 51, demonstrated promising potential as PD-L1 inhibitors. The interaction and 2D structures of these eleven hit ligands interacting with the PD-L1 protein are shown in Table 2, listed in decreasing order of affinity energy.
![1](https://github.com/user-attachments/assets/95855f3b-21b5-480f-a288-5c16ce8ff2c1)
![2](https://github.com/user-attachments/assets/ad8660d0-f874-4804-86ee-c9427ccaa3b2)
![3](https://github.com/user-attachments/assets/8ccc36f1-7eec-47a2-9580-155196562250)
![4](https://github.com/user-attachments/assets/cdacfc80-d838-422f-8eb0-1206c9072bbc)
![5](https://github.com/user-attachments/assets/43c440a6-0c9e-46ac-a2ea-1270f8d556e5)
![6](https://github.com/user-attachments/assets/4d09f760-3b33-4e36-8297-4f4be3a01c17)

ADMET properties of the ligands hit and N-Phenethylcinnamamide compound are listed in the table below (Table 2)
**Table 2:** ADMET scores of hit compounds and N-Phenethylcinnamamide compound.
| Variables                                   | Base    | 25      | 43      | 5       | 11      | 42      | 55      | 2       | 48      | 29      | 3       | 51      |
|--------------------------------------------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|
| **Absorption**                             |         |         |         |         |         |         |         |         |         |         |         |         |
| Solubility in water (log mol/L)            | -3.978  | -3.385  | -3.173  | -3.258  | -3.140  | -3.509  | -3.394  | -3.235  | -3.242  | -3.165  | -3.100  | -3.641  |
| Caco-2 permeability (log Papp in 10−6 cm/s)| 1.532   | 0.987   | 0.936   | 1.254   | 0.922   | 1.273   | 1.021   | 1.277   | 0.949   | 0.920   | 0.865   | 0.987   |
| Intestinal absorption in humans (% absorbed)| 92.741 | 87.868  | 90.259  | 91.346  | 90.025  | 90.490  | 89.846  | 91.234  | 90.323  | 90.031  | 89.913  | 91.390  |
| Skin permeability (log Kp)                 | -2.453  | -2.830  | -2.796  | -2.878  | -2.795  | -2.920  | -2.794  | -2.786  | -2.739  | -2.809  | -2.795  | -2.878  |
| P-glycoprotein substrate (yes/no)          | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     |
| P-glycoprotein I inhibitor (yes/no)        | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      |
| P-glycoprotein II inhibitor (yes/no)       | No      | No      | No      | No      | No      | No      | Yes     | No      | No      | No      | No      | No      |
| **Distribution**                           |         |         |         |         |         |         |         |         |         |         |         |         |
| Volume of distribution steady-state in humans (log L/kg)| 0.243 | 0.037  | 0.205  | 0.250  | 0.311  | 0.061  | 0.049  | 0.260  | 0.502  | 0.261  | 0.252  | 0.027  |
| Fraction unbound in human (Fu)             | 0       | 0.125   | 0.149   | 0.062   | 0.149   | 0.064   | 0.052   | 0.056   | 0.242   | 0.149   | 0.147   | 0       |
| BBB permeability (log BB)                  | 0.553   | -0.635  | -0.744  | 0.018   | -0.552  | 0.050   | -0.912  | 0.035   | -0.799  | -0.552  | -0.501  | -0.093  |
| CNS permeability (log PS)                  | -1.129  | -2.348  | -2.348  | -2.152  | -2.331  | -2.176  | -2.692  | -2.178  | -2.495  | -2.327  | -2.357  | -2.504  |
| **Metabolism**                             |         |         |         |         |         |         |         |         |         |         |         |         |
| Substrate of cytochrome P450 2D6 (yes/no)  | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      |
| Substrate of cytochrome P450 3A4 (yes/no)  | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     |
| Inhibitor of cytochrome P450 1A2 (yes/no)  | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | No      | Yes     | Yes     | Yes     | Yes     | Yes     |
| Inhibitor of cytochrome P450 2C19 (yes/no) | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | No      | Yes     |
| Inhibitor of cytochrome P450 2C9 (yes/no)  | Yes     | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      | Yes     |
| Inhibitor of cytochrome P450 2D6 (yes/no)  | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      |
| Inhibitor of cytochrome P450 3A4 (yes/no)  | No      | No      | No      | No      | No      | No      | Yes     | No      | No      | No      | Yes     | Yes     |
| **Excretion**                              |         |         |         |         |         |         |         |         |         |         |         |         |
| Total clearance (log mL/min/kg)            | 0.382   | 0.120   | 0.129   | 0.328   | 0.254   | 0.194   | 0.268   | 0.313   | 0.197   | 0.265   | 0.245   | 0.344   |
| Renal OCT2 substrate (yes/no)              | Yes     | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      |
| **Toxicity**                               |         |         |         |         |         |         |         |         |         |         |         |         |
| AMES toxicity (yes/no)                     | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      |
| Max tolerated dose in humans (log mg/kg/d) | 0.738   | 0.206   | -0.250  | 0.122   | -0.220  | 0.133   | -0.103  | 0.370   | -0.226  | -0.213  | 0.076   | -0.057  |
| hERG I inhibitor (yes/no)                  | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      |
| hERG II inhibitor (yes/no)                 | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     | Yes     |
| Oral rat acute toxicity (LD50) (mol/kg)    | 2.163   | 1.971   | 2.112   | 2.172   | 2.198   | 2.153   | 1.827   | 2.081   | 2.237   | 2.170   | 2.110   | 1.920   |
| Oral rat chronic toxicity (LOAEL) (log mg/kg bw/d)| 1.161 | 1.924   | 2.105   | 1.565   | 1.270   | 1.427   | 2.147   | 1.559   | 2.539   | 1.271   | 1.254   | 1.742   |
| Hepatotoxicity (yes/no)                    | Yes     | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      |
| Skin sensitization (yes/no)                | Yes     | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      | No      |
| T. Pyriformis toxicity (log µg/L)          | 1.666   | 0.964   | 0.918   | 1.437   | 0.992   | 1.531   | 0.743   | 1.356   | 0.506   | 1.008   | 1.018   | 1.066   |
| Minnow toxicity (log mM)                   | 0.620   | 1.633   | 0.730   | 1.062   | 1.603   | 1.188   | 1.573   | 1.085   | 2.152   | 1.514   | 1.625   | 0.778   |


**Conclusion :** 
The promising results of this study lay a solid foundation for in-depth testing of the identified compounds, both in-vitro and in-vivo, to validate their efficacy as PD-L1 inhibitors. Such validation is a pivotal step toward the development of innovative approaches in cancer immunotherapy.Furthermore, these investigations will provide valuable insights into the broader therapeutic potential of the plants from which some of these compounds are derived, highlighting the relevance of natural products in cancer treatment.
Additionally, the potential for enhanced therapeutic efficacy and tumor suppression through the combination of these molecules with existing anticancer drugs warrants further investigation. A comprehensive understanding of these interactions could facilitate the optimization of drug dosages, the reduction of adverse effects, and, consequently, the improvement of patient outcomes.In summary, the implementation of these experimental strategies will contribute to the expansion of available therapeutic options in the ongoing effort to combat cancer. 




**Authors**: ABA Mohamed, EL OUAFI Zainab, BENMOUSSA Imane, ACHEMCHEM Fouad, AlNOUNOU Mohammad, HAMDI Salsabil, Al IDRISSI Najib, JHILAL Faissal, BENMOUSSA Adnane and BAKKALI Fadil. Exploring Novel PD-L1 Inhibitors Through Molecular Docking: A Promising Approach in Cancer Immunotherapy. Lecture Notes in Networks and Systems. Springer.(2025)
