# From Gene Mutation to Disease: Investigating How DNA Sequence Changes Affect Protein Products and Human Phenotypes

**Student:** Jerrick Paul T. Tayos  
**Disease:** Achondroplasia  
**Gene:** FGFR3  
**Documented Variant:** NM_000142.5:c.1138G>A (p.Gly380Arg)

## Disease Background

Achondroplasia is a genetic skeletal disorder caused by pathogenic variants in the FGFR3 gene. It mainly affects normal skeletal development, particularly the growth of the long bones.

Achondroplasia is associated with increased FGFR3 signaling. Excessive FGFR3 signaling affects chondrocytes in the growth plates, which are important for normal endochondral bone growth. Abnormal regulation of these cells can interfere with normal skeletal development and contribute to the characteristic features of achondroplasia.

## Gene and Normal Protein Function

The FGFR3 gene stands for fibroblast growth factor receptor 3. The gene is located on chromosome 4p16.3.

FGFR3 encodes a receptor tyrosine kinase located in the cell membrane. The protein contains an extracellular region, a transmembrane region, and an intracellular tyrosine kinase domain.

Under normal conditions, FGFR3 participates in signaling pathways that regulate cell proliferation, differentiation, and survival. It also plays an important role in regulating chondrocyte activity during skeletal development.

FGFR3 signaling involves downstream pathways that help regulate cellular growth and differentiation.

## Documented Mutation

The documented disease-associated variant investigated in this experiment was NM_000142.5:c.1138G>A (p.Gly380Arg), also known as G380R.

The mutation is a single-nucleotide substitution in the FGFR3 coding sequence. The change from G to A at nucleotide position 1138 changes the codon from GGC to GAC, resulting in the replacement of glycine (Gly) with arginine (Arg) at amino-acid position 380.

Therefore, the variant is classified as a missense mutation.

Because the mutation is a single-nucleotide substitution rather than an insertion or deletion, the reading frame remains unchanged. The overall predicted protein length also remains unchanged.

## Hypothesis

Before constructing the documented mutation, it was hypothesized that changing nucleotide 1138 from G to A would change the encoded amino acid at position 380 from glycine (Gly) to arginine (Arg).

The expected sequence change was:

DNA: c.1138G>A

Codon: GGC → GAC

Protein: Gly380 → Arg380

Because the mutation is a single-nucleotide substitution rather than an insertion or deletion, the reading frame and overall protein length were expected to remain unchanged. No premature stop codon was expected.

## Methods

The normal FGFR3 coding sequence was obtained from the NCBI RefSeq transcript NM_000142.5, with the corresponding reference protein NP_000133.1.

The WT FGFR3 coding sequence was uploaded to Galaxy and translated using the standard genetic code in reading frame 1. The resulting WT protein sequence was saved for comparison.

A copy of the WT coding sequence was then used to reproduce the documented c.1138G>A mutation. Nucleotide position 1138 was changed from G to A using the sequence editor.

The modified coding sequence was translated using the same settings used for the WT sequence. The resulting mutant protein was compared with the WT protein to determine the amino-acid change and whether the mutation affected the reading frame or protein length.

A separate copy of the WT FGFR3 coding sequence was used to create an artificial mutation, c.7G>A. This changed the codon from GCC to ACC.

The artificial mutant sequence was also translated and compared with the WT protein sequence.

## Results

The WT FGFR3 coding sequence was 2,421 bp long and produced a predicted protein of 806 amino acids. Translation began with the start codon ATG in reading frame 1.

The predicted WT results were:

CDS length: 2421 bp

Protein length: 806 amino acids

Reading frame: Frame 1

Start codon: ATG

For the documented mutation, nucleotide 1138 changed from G to A. This changed the codon from GGC to GAC.

The resulting amino-acid substitution was:

Gly380 → Arg380

Translation produced a protein that remained 806 amino acids long. No frameshift, amino-acid insertion or deletion, or premature stop codon was observed.

Therefore, the documented mutation was classified as a missense mutation.

## WT Versus Documented Mutant Protein Comparison

The documented mutant protein differed from the WT protein at amino-acid position 380.

WT: Glycine (Gly) at position 380

Documented mutant: Arginine (Arg) at position 380

WT protein length: 806 amino acids

Documented mutant protein length: 806 amino acids

Frameshift: None

Premature stop codon: None

Amino acids inserted or deleted: None

The sequence change can be summarized as:

WT codon: GGC

Mutant codon: GAC

WT amino acid: Gly380

Mutant amino acid: Arg380

Thus, the documented mutation resulted in a single amino-acid substitution without changing the overall protein length or reading frame.

## Artificial Mutation Experiment

An artificial mutation, c.7G>A, was introduced into a separate copy of the WT FGFR3 coding sequence.

This changed the codon from GCC to ACC.

The resulting amino-acid change was:

Ala3 → Thr3

Because both the original and mutant codons represent amino acids but encode different amino acids, the artificial mutation was classified as a missense mutation.

After translation, the artificial mutant protein remained 806 amino acids long. No frameshift or premature stop codon was observed.

The predicted results were:

Mutation: c.7G>A

Codon change: GCC → ACC

Amino-acid change: Ala3 → Thr3

Mutation type: Missense

Protein length: 806 amino acids

Frameshift: None

Premature stop codon: None

This experiment demonstrates that a single-nucleotide substitution can change an amino acid without changing the overall length of the protein.

## Molecular Interpretation: Gene → Mutation → Protein → Cellular Effect → Phenotype

The molecular consequence of the documented mutation can be summarized as:

FGFR3 gene → c.1138G>A mutation → GGC to GAC codon change → p.Gly380Arg (G380R) → altered FGFR3 receptor → increased FGFR3 signaling → abnormal chondrocyte regulation → reduced normal bone growth → achondroplasia phenotype.

The c.1138G>A substitution changes glycine to arginine at amino-acid position 380. Although the mutation does not cause a frameshift or change the protein length, the amino-acid substitution can affect the behavior and function of the FGFR3 receptor.

The Gly380Arg mutation is associated with increased FGFR3 signaling. Excessive FGFR3 signaling can affect chondrocytes in the growth plate and interfere with their normal proliferation and differentiation.

Because chondrocytes are important for endochondral bone growth, abnormal FGFR3 signaling can contribute to reduced longitudinal growth of bones and the characteristic skeletal features associated with achondroplasia.

The computational analysis demonstrates the DNA and predicted protein sequence changes, while experimental biological evidence is needed to determine the exact effects of the mutation on receptor activity and cellular signaling.

## Limitations

The experiment was based primarily on DNA sequence manipulation and computational translation using Galaxy.

The analysis demonstrates the predicted effects of the nucleotide substitutions on the amino-acid sequence, reading frame, and protein length. However, it does not directly measure FGFR3 protein expression, receptor activity, protein stability, protein folding, or cellular signaling.

The artificial c.7G>A mutation was created for educational purposes. Its exact biological effect was not experimentally tested, so its functional consequence should be considered a prediction.

## Conclusion

The documented FGFR3 c.1138G>A mutation produced a single amino-acid substitution from glycine to arginine at position 380, resulting in the protein change p.Gly380Arg (G380R).

The mutation did not change the reading frame or overall protein length. The predicted protein remained 806 amino acids long.

The artificial c.7G>A mutation produced a different missense change, Ala3Thr, while also maintaining the same reading frame and overall protein length.

Overall, this experiment demonstrates how a single DNA nucleotide substitution can produce an amino-acid change without altering the overall length of a protein. In achondroplasia, the documented FGFR3 mutation is associated with abnormal receptor signaling that affects chondrocyte regulation and skeletal growth.

## References

GeneReviews. (2021). *Achondroplasia*. NCBI Bookshelf.

https://www.ncbi.nlm.nih.gov/books/NBK1152/

National Center for Biotechnology Information. (n.d.). *ClinVar: NCBI's archive of interpretations of clinically relevant variants*.

https://www.ncbi.nlm.nih.gov/clinvar/

National Center for Biotechnology Information. (n.d.). *FGFR3 fibroblast growth factor receptor 3 [Homo sapiens (human)]*. NCBI Gene.

https://www.ncbi.nlm.nih.gov/gene/2261

National Center for Biotechnology Information. (n.d.). *Homo sapiens fibroblast growth factor receptor 3 (FGFR3), transcript variant 1, mRNA*. NCBI Nucleotide.

https://www.ncbi.nlm.nih.gov/nuccore/NM_000142.5

National Center for Biotechnology Information. (n.d.). *Protein: NP_000133.1*. NCBI Protein.

https://www.ncbi.nlm.nih.gov/protein/NP_000133.1
