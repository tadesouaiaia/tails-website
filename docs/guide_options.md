
# Commands 

POPout can be run using our Python script with the following command: 

```
./POPout.py trait1.pop trait2.pop.... 
```

The following commands are supported: 


## 




## Names (--names) 

By default the file prefixes are used as trait names, to use custom trait names the user can 
provide a list of names equal in length to the number of POP files, for example: 

```
./POPout.py trait1.pop trait2.pop --names traitA traitB  
```

## Output Prefix (--out) 

The default output prefix is "out" but it can be changed as follows: 

```
./POPout.py trait1.pop trait2.pop --names traitA traitB  --out customOutput 
```

## Plot Format (--plotFormat) 

The default format for plots is "pdf" but this can be changed to png as follows: 

```
./POPout.py trait1.pop trait2.pop --names traitA traitB  --out customOutput --plotFormat png 
```

## Tail Size (--tailSize) 

By default POPout considers the lower and upper 1% as the trait tails.  This can be changed as follows*: 


```
./POPout.py trait1.pop trait2.pop --names traitA traitB  --out customOutput --plotFormat png --tailSize 5  
```


*Note that for this option, values between 1 and 25 are valid as are the values 0.5 (half a percent), 
0.25 (a quarter percent), and 0.1 (a tenth of a percent).  

 


