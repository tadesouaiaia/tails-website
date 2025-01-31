# Output Data


Running POPout (as described in the quick-start tutorial) will create an output file with the following 
information: 


---|len|pv1|pv2|e1|e1Lo|e1Hi|e2|e2Lo|e2Hi|QC|emp1|emp2|
:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
toy_bp|12648|0.098|8.9e-06|-0.14|-0.30|0.025|-0.14|-0.30|0.025|True|0.92|0.01|
toy_vitD|2146|0.594|0.928|0.02|-0.05|0.085|0.02|-0.05|0.085|True|0.17|0.67|
toy_hg|2146|3.4e-08|3.4e-10|0.99|0.75|1.224|0.99|0.75|1.224|True|0.01|0.01|
toy_bmi|2146|1.9e-06|0.322|0.86|0.59|1.129|0.86|0.59|1.129|True|0.01|0.88|
toy_height|8582|0.017|5.7e-04|0.41|0.08|0.735|0.41|0.08|0.735|True|0.03|0.01|


For each trait, the columns denote:

Column|Data|
|:-:|:-:|
---|Trait Name|
len|Sample Size|
pv1|Lower Tail Pvalue|
pv2|Upper Tail Pvalue|
e1|Lower Tail POPout Effect Size|
e1Lo|Lower Tail 95% CI - Lower End|
e1Hi|Lower Tail 95% CI - Upper End|
e2|Upper Tail POPout Effect Size|
e2Lo|Upper Tail 95% CI - Lower End|
e2Hi|Upper Tail 95% CI - Upper End|
QC|QC-Test Result|
emp1|Rank Based Empirical Pvalue|
emp2|Rank Based Empirical Pvalue|

For more information on how these values are calculated please see our 
[manuscript](https://pubmed.ncbi.nlm.nih.gov/39605697/). 




