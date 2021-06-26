# **Tool for Annotation and Classification of Genes and Variants (TAGCVar)**
Our developed pipeline (TACGVar) efficiently annotates large numbers of variants files and helps estimate specific tissue enrichment over the association of miRNA.

# **Overview**
![pasted image 0](https://user-images.githubusercontent.com/80075365/123517696-76a2e400-d670-11eb-917d-bb1560d1e560.png)

# **Publication and Citation**
Paper still in progress

# **Usage**
**Step 0 Step 1: Annovar Annotaion**
This part of the pipeline is used to create an ANNOVAR formatted output file so that the 3' UTR Prevalenece Script can use it as an input file. The input file we used was a SNP list for easy processing. A shortened version follows,
```rs1775421
rs1775420
rs1818038
rs770685
rs12116874
rs707583
rs707582
rs770718
rs11260662
rs9439587
rs9329417
rs10157819
rs9439605
rs12143743
```

but the input file should be in the format of .sumstats.add.txt and looks as follows;

# **Output**
The ANNOVAR output result is as follows; [image]

The
