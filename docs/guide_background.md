![Screenshot](img/slim/guide_logo1.png)





# Background

PRS methods require as input summary statistics from genome wide association
studies. If unfamiliar with GWAS or in need of a refresher consider reading
[this paper](https://www.ncbi.nlm.nih.gov/pubmed/29484742).

- Genome-wide association studies (GWAS) involve analyzing the genomes
  of a large group of individuals.  
- For a binary trait (like blue or brown eyes) this involves comparing
the frequency of genetic variations in each group to produce an
odds-ratio (measure of association) and a p-value to measure the
signficance of the realtionship at each SNP.
- For continuous measures (like height) this results in an effect size (measure of continuous association) 
  and p-value that measure the significance of our relationship.   
- GWAS results can be summarized in a sumstats file which looks like this:


CHR|ID|REF|A1|A1_FREQ|OBS_CT|SE|BETA|P|                                                                                                                                 
:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|                                                                                                                                                                                                  
1|rs100|A|T|0.1|100|0.01|1.10|0.01                                                                                                  
2|rs200|C|G|0.2|100|0.02|-1.10|0.05                                                                                                  
3|rs300|G|A|0.3|100|0.03|1.02|0.10                                                                                                  



# PRS basics

- Polygenic scores combine genetic variant associations genome-wide by 
  summing their effects to produce individual scores that predict the phenotype.   
- Different PRS methods use different statistical methods to select
  variants and estimate their effect sizes for use in the PRS.
- BridgePRS, like many other PRS methods, requires genotype and
  phenotype data from individuals (several hundred samples) in
  addition to GWAS summary statistics to estimate the PRS. 
- The predictive power of PRS is assessed in genotype and phenotype
  data from unseen samples. BridgePRS reports PRS accuracy by the
  residual variance explained $R^2$ (accounting for the variance
  explained by the non-genetic covariates included in the model). For
  binary traits Nagelkerke $R^2$ is used.


# POPout 

Explain what it is. 








