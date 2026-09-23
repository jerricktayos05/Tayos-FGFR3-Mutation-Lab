# From Gene Mutation to Disease: FGFR3 Mutation Analysis in Achondroplasia

*Student:* Jerrick Paul T.Tayos 

*Disease:* Achondroplasia  
*Gene:* FGFR3  
*Documented Variant:* NM_000142.5:c.1138G>A (p.Gly380Arg)  
*Reference Transcript Accession:* NM_000142.5  
*Reference Protein Accession:* NP_000133.1  
*Galaxy History Name:* Balanza_Achondroplasia_FGFR3_Mutation_Lab  
*Date of Analysis:* September 16, 2026

## Project Overview

This repository contains the sequence analysis and documentation for a Cell and Molecular Biology Laboratory activity investigating how a DNA mutation can affect a protein product and contribute to a disease phenotype.

The project focuses on the *FGFR3* gene and the documented *c.1138G>A (p.Gly380Arg/G380R)* variant associated with achondroplasia.

## Objectives

This project was conducted to:

- Identify a documented disease-associated mutation in the FGFR3 gene.
- Establish the normal FGFR3 sequence as the wild-type (WT) control.
- Translate the WT coding sequence and examine its predicted protein product.
- Reproduce the documented c.1138G>A mutation using Galaxy.
- Compare the WT and documented mutant protein sequences.
- Create an artificial mutation for comparison.
- Interpret how nucleotide changes can affect protein products and disease-related molecular function.

## Reference Sequences

The WT FGFR3 coding sequence was obtained from the NCBI RefSeq transcript *NM_000142.5*.

*Reference protein:* NP_000133.1

The WT CDS is *2,421 bp* and produces a predicted FGFR3 protein of *806 amino acids*.

## Documented Mutation

*Variant:* NM_000142.5:c.1138G>A (p.Gly380Arg)

The nucleotide substitution changes *G → A* at coding position 1138.

This changes the codon from:

*GGC → GAC*

resulting in the amino-acid substitution:

*Gly → Arg at position 380*

The mutation is a *missense variant*.

The mutation does not introduce a frameshift or premature stop codon, so the predicted protein remains *806 amino acids* long.

## Student-Created Artificial Mutation

A student-created artificial mutation, *c.7G>A*, was introduced into a separate copy of the WT FGFR3 CDS.

This changes:

*GCC → ACC*

The resulting amino-acid change is:

*Ala → Thr at position 3 (p.Ala3Thr)*

The mutation is a *missense substitution*.

Because only one nucleotide is substituted, the reading frame is not changed. No premature stop codon is introduced, and the predicted protein remains *806 amino acids* long.

The functional effect of this artificial mutation is unknown and is being examined only as part of the computational laboratory activity.

## Repository Structure

```text
Balanza_Achondroplasia_FGFR3_Mutation_Lab/
│
├── 01_reference/
│   ├── FGFR3_WT_CDS.fasta
│   └── FGFR3_WT_protein.fasta
│
├── 02_documented_mutation/
│   ├── FGFR3_c.1138G>A_mutant_CDS.fasta
│   └── FGFR3_c.1138G>A_mutant_protein.fasta
│
├── 03_artificial_mutation/
│   ├── FGFR3_c.7G>A_mutant_CDS.fasta
│   └── FGFR3_c.7G>A_mutant_protein.fasta
│
├── 04_results/
│   ├── WT_vs_documented_mutant_alignment.txt
│   ├── WT_vs_artificial_mutant_alignment.txt
│   └── results_summary.md
│
├── 05_report/
│   └── final_report.md
│
├── disease_gene_background.md
└── README.md

References

1. Legare, J. M., & Modaff, P. (2026). Achondroplasia. In GeneReviews®. University of Washington, Seattle.

2. NCBI ClinVar. NM_000142.5(FGFR3):c.1138G>A (p.Gly380Arg) AND Achondroplasia. The current ClinVar record classifies this germline variant as pathogenic.

3. NCBI RefSeq. FGFR3 transcript NM_000142.5 and protein NP_000133.1. Reference sequence information used for the FGFR3 sequence analysis.

4. NCBI ClinVar. FGFR3 c.1138G>A (p.Gly380Arg). ClinVar records describe this as a missense variant associated with achondroplasia.

5. GeneReviews®. Achondroplasia: Molecular Genetics. The p.Gly380Arg variant is associated with constitutive activation of FGFR3 and altered signaling affecting growth-plate chondrocytes.

6. Galaxy Project. Galaxy: An open, web-based platform for accessible, reproducible biomedical data analysis. Used for sequence processing and translation during the laboratory activity.

7. NCBI. National Center for Biotechnology Information. Reference sequence and variant databases used for FGFR3 analysis.
