# Translating_RNA_to_Protein
If you know an RNA sequence, you can translate it into the corresponding protein sequence by using the genetic code. This is the same way the cell itself generates a protein sequence.

The genetic code for RNA (also called RNA codon table) shows how we uniquely relate a 4-nucleotide sequence (A, U, G, C) to a set of 20 amino acids. 
![Genetic code chart for RNA](https://cdn-images-1.medium.com/max/1600/1*rDWfkAvR4XT88PFd3_Tbmg.png)

# Using the above chart for RNA to Protein Translation
1. Get your RNA string
2. Then start reading sequences of 3 nucleotides (one triplet) at a time (example AUG GGC...)
3. Use the genetic code chart to read which amino acid corresponds to the current triplet (technically referred to as codons). The first circle starting from the center represents the first character of the triplet, the second circle represents the second character and the third circle represents the last character. After translating, you will get the protein sequence which corresponds to the aforementioned RNA sequence.
* UAA, UAG and UGA are known as termination signals where you stop the translation process.
