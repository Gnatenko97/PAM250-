# PAM250-
Recreation of PAM250 matrix from amino acid substitutions


The Goal of this proggram is to recreate method by which substitution matrix PAM250 was created based on number of amino 
acids substitutions of two clsely related bacterial strain domains. 

Method 
1) Protein seqence of 5 bacteria was obtained from MicrobesOnline
2) Emboss-Needle used to align amino acids 
3) Algorithm calculates substitution freqency and gnerates PAM250 matrix 

Bacteria Stains Used 
1. Escherichia coli str. K-12 substr. MG1655
2. Geobacter sulfurreducens PCA
3. Desulforudis audaxviator MP104C
4. Zymomonas mobillis subsp. mpbilis ZM4
5. Bacillus subtilis subsp. subtilis str. 168


  The purpose of this program is to calculate Sij = log2(Mij/Eij), for one 
pair of amino acids, i and j.  Sij is one value in the substitution matrix.
Examile the heat map for Sii and Sjj with PAM250. 

Here is the recreated heatmap of PAM250
![GitHub Logo](/heatmap.png)

Here is the original heatmap of PAM250
![GitHub Logo](/PAM250.jpg)



Contributions:
Alis Zemlo 
Vlad Gnatenko 
