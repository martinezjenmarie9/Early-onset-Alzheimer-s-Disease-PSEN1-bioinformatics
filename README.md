# Bioinformatics Lab Activity: Exploring a Human Disease Gene Using UCSC Genome Browser and NCBI ClinVar

 **Name:** Jen Marie A. Martinez
 **Assigned Gene:** PSEN1 (Presenilin 1)
 **Associated Disease:** Early-Onset Alzheimer's Disease

## Part B: Locate Your Gene in the UCSC Genome Browser

### Gene Details
 **a. Official gene symbol:** PSEN1
 **b. Full gene name:** Presenilin 1
 **c. Chromosome:** Chromosome 14 (chr14)
 **d. Genome assembly used:** GRCh38/hg38
 **e. Genomic coordinates shown in UCSC:** chr14:73,136,507-73,223,691
 **f. DNA strand (+ or -):** + (Forward strand)
 **g. Approximate gene size or length:** ~87 kb (87,185 bp)

### Required Proof: Screenshot 1
*UCSC Genome Browser view of `PSEN1` displaying the gene structure, coordinate ruler, and chromosome details.*

![PSEN1 UCSC Genome Browser View](image_110d42.png)

## Part C: Understand the Gene Structure: Exons, Introns, and Transcripts

### Gene Structure Analysis (`PSEN1`)
 **a. Number of exons:** 10 to 12 distinct exon blocks identified in the selected transcript model (12 total exons, 10 protein-coding).
 **b. Multiple transcripts visible:** Multiple transcript isoforms are visible stacked near the top of the RefSeq gene tracks.
 **c. Difference between exon and intron:** Exons are sequences retained in the mature mRNA that code for proteins or form UTRs, whereas introns are intervening sequences that are transcribed into pre-mRNA but spliced out prior to translation.
 **d. Intron vs. Exon length:** The introns generally appear much longer than the exons, represented by long connecting lines spanning wide genomic distances between narrow exon blocks.

### Required Proof: Screenshot 2
*UCSC Genome Browser view displaying `PSEN1` gene structure, transcripts, and functional tracks.*

![PSEN1 Gene Structure View](image_10b3fc.png)

## Part D: Turn On and Examine Genome Browser Tracks

### Track Analysis Answers (PSEN1)
 **a. Gene annotation track used:** NCBI RefSeq and MANE Select Plus Clinical[cite: 6].
 **b. ClinVar-related variant marks visible:** Multiple ClinVar variant marks are distributed across the PSEN1 gene region.
 **c. Differential conservation:** Certain genomic positions display high conservation peaks while others remain low.
 **d. Region correspondence:** The high conservation peaks correspond primarily to the coding exons.
 **e. Biological importance of conservation:** Strong sequence conservation across multiple vertebrate species implies that natural selection has actively preserved the sequence over millions of years of evolution. If a genomic region or residue can change very little without harming the organism, it typically indicates that it serves a vital functional role, such as coding for essential amino acids or maintaining structural and regulatory integrity.

### Required Proof: Screenshot 3
*UCSC Genome Browser view showing `PSEN1` with enabled ClinVar variant tracks and the 100 Vertebrates Conservation track.*

![PSEN1 Tracks View](image_1028e1.png)

## Part E: Select One Variant in NCBI ClinVar

### Selected Variant Details (PSEN1)
 **Variant Identifier / Variation ID:** 18143
 **HGVS Name / Protein Change:** G206A, G202A
 **Clinical Classification:** Pathogenic
 **Associated Condition:** Early-Onset Familial Alzheimer's Disease
 **Review Status:** Criteria provided, multiple submitters (2 stars)
 **ClinVar Page URL:** [https://www.ncbi.nlm.nih.gov/clinvar/variation/18143/]

### Required Proof: Screenshot 4
*UCSC Genome Browser zoomed-in view locating the pathogenic variant `p.Gly206Ala` (Variation ID: 18143) on chromosome 14.*

![PSEN1 ClinVar Variant View](image_filename.png)

## Part F: Find Your Selected Variant Back in UCSC

### Variant Mapping Analysis (p.Gly206Ala / Variation ID: 18143)
 **a. Relative location:** Situated internally within the *PSEN1* gene span on chromosome 14.
 **b. Region type:** Exon
 **c. Coding vs. Non-coding:** Coding region (missense substitution resulting in an amino acid change).
 **d. Potential functional effect:** The substitution alters a conserved domain within the Presenilin-1 protein, disrupting normal proteolytic processing and driving early-onset Alzheimer's disease pathogenesis.
 **e. Additional evidence needed:** Functional enzyme assays, multi-generation family co-segregation studies, and biochemical validation.

### Required Proof: Screenshot 5
*UCSC Genome Browser view displaying the selected variant mapped accurately to the exon structure of the PSEN1 gene model[cite: 5].*

![PSEN1 Variant Position View](image_0543b3.png)

## Part G. Short Reflection

1. **What did UCSC show you about your gene that was not obvious from simply reading about the gene's function?**

Reading about a gene just tells you what job it does in the body, but the genome browser actually shows you its physical neighborhood. Seeing the tracks let me visualize how the gene is structured compared to its actual coding pieces, and how different animal species share those exact same spots. It made it real by showing the actual DNA letters and how crowded the region is with other genetic signals.

2. **Why is knowing the exact genomic location of a disease-associated variant useful?**

Pinpointing the exact coordinate acts like a precise GPS address for the mutation. It lets researchers and doctors instantly see whether the typo falls inside a critical working zone like an exon or if it's hiding out in a different area. Without that exact address, you'd just be guessing where the problem is across millions of base pairs.

3. **What is one limitation of predicting a variant's effect only from its genomic location?**

Just knowing where a mutation sits on the chromosome doesn't automatically tell you what happens inside a living cell. A change might look a certain way on a map or sit in an exon, but it could still have weird downstream effects or turn out to behave differently depending on the cellular environment. You can't fully understand the real-world biological impact just by looking at a map coordinate.

4. **What was the most interesting feature you observed about your assigned gene?**

The coolest part was seeing the conservation track show strong alignment right over the important regions while the rest of the DNA varied. It was wild to look at the screen and realize that multiple species share those exact same stretches of code because evolution keeps them tightly protected.

