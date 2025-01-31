# Input Data



## POP Files 


The POP (PRS on Phenotype) file specification simply requires two columns of whitespace or comma-separated 
data where the first column contains PRS values and the second the corresponding Phenotype values.  Note that the 
header is optional for our Python scripts but required by R: 

PRS|Phenotype|
|:-:|:-:|
-2.2|-1.5|
-1.3|-0.4|
-0.3|-0.1|
-0.6|0.2|
1.6|0.9|
2.1|1.3|
2.5|2.1|



If you have PRS and Phenotype data with sample IDs in the first column then you can create a POP file 
using our Python script as shown with example data: 

!!! tip "Creating a POP File"
    The following command will create POP file named my_file.pop. 
    ```
    ./POPout.py --makePOPfile data/TEST.prs data/TEST.pheno -o my_file

    ```
    






