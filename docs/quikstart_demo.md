![Screenshot](img/pop_wide.jpg) 


# Intro


POPout comes with example data for multiple toy traits.  Inside of the data directory you should see: 

        toy_bmi.pop    <--- toy bmi data
        toy_bp.pop     <--- toy blood pressure data
        toy_height.pop <--- toy height data
        toy_hg.pop     <--- toy handgrip data
        toy_vitD.pop   <--- toy vitaminD data
        TEST.pheno     <--- Example Phenotype data
        TEST.prs       <--- Example PRS data


The toy data files are in "POP format" which is column or comma separated data where the 
first column is the phenotype and the second column is the PRS values.  For more information 
on POP format and help getting your own data into POP format please see 
[Guide: Input Data](guide_input.md).



## Python3

To run the demo on all the toy traits using Python, please type: 
```
./POPout.py -o test data/toy_bp.pop data/toy_vitD.pop data/toy_hg.pop data/toy_bmi.pop data/toy_height.pop
```

This will create three output files: 
        

        test-result.txt    <--- POPout Results 
        test-dists.pdf     <--- Figure For POPout distributions 
        test-effects.pdf   <--- Figure showing POPout Effect Sizes    


Please continue to the next page for interpretation of these results. 


## R 

Alternatively, POPout can be run on a single POP-file using the following R script, which 
will print directly to the terminal:  

```
Rscript --vanilla POPout.R data/toy_bp.pop > test_result.txt
```


    



