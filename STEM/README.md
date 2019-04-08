## STEM
### Download the STEM program from http://www.cs.cmu.edu/~jernst/stem/

### Create an input file using Excel
Input file should contain a column of hgnc or gene identifiers and RPKM values for each gene at each condition

Median RPKM values can be used for experimental conditions with mutiple biological replicates.  

Input file should be tab delimited

See STEM_input.txt as an example


### STEM commands
- Open stem.jar and follow the commands down below:
```
1. Select Normalize data
2. Select Human as Gene Annotation source
3. For STEM Clustering Method, choose 50 and 2
4. Execute
```
The colored graphs are representative of statistically significant genes.
