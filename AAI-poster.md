# AAI 2022 poster presentation

## Abstract 

The ability to accurately identify peptide ligands for a given major histocompatibility complex class I (MHC-I) molecule has immense value for targeted anticancer and antiviral therapeutics. However, the highly polymorphic nature of the MHC-I protein makes universal prediction of peptide ligands challenging due to lack of experimental data describing most MHC-I variants, and the vast number of protein variants precludes comprehensive experimental determination. Therefore, there is a need for a framework to cluster MHC-I alleles to prioritize for experimental validation as well as identify alleles with potential disease associations.

To address this challenge, we have developed a deep convolutional neural network, HLA-Inception, capable of predicting MHC-I peptide binding motif using data derived from the structure of the MHC-I binding pocket. By approaching this problem from a 3-dimensional perspective, we can fully consider the impact of sidechain arrangement and topology of the MHC-I binding pocket on peptide binding motif, which is not inherently captured by the popular protein sequence-based approaches. Through a combination of homology modeling and biophysical simulations, we created protein structure models for all full-length HLA-ABC alleles. The topology and interaction forces within the MHC-I binding pocket were accounted for by solving the 3-dimensional electrostatic potential near the surface of the protein. HLA-Inception was then trained on all MHC-I alleles with known MHC-I binding motifs and applied to the full set of MHC-I models. We found that predicted peptide binding motifs fell into distinct and well-defined clusters which maintained known peptide binding and disease associations.

---
## Panel A: Input generation and model architecture

---
## Panel B: Motif clustering


---

## Panel C: MHC-I peptide binding predictions

### C1:
Natural presented peptides detected via mass spectromtery for 53 different MHC-I alleles were combined with an 100-fold excess of decoy peptides extracted from the human proteome. This peptides were then evaluated using position-weighted scoring matrices derived from predicted peptide binding motifs.

eq 1.

Precision-recall curves were then generated by calculating  both precision (true positive / true positive + false positives) and recall (true positives / total number of true positves in dataset)

- 


