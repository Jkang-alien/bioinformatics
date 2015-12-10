# bioinformatics
open bioinformatics program

### Tech Tree
see details in [wiki](https://github.com/Xcollege/bioinformatics/wiki)
```
[NGS root]-[RNAseq analysis]
         |-[ChIPseq analysis]
         ...
         
[RNAseq analysis]-[DE: differential expression analysis] 
          \-[AS: alternative splicing]_[isoform oriented]
           \                    \_[event oriented]
            \-[PA: PolyAseq analysis]-[3'UTR focussed]-[trend shifting test]
                         \                       \-[independence test]
                          \-[PCPA focussed]-[independence test]
                          
                          
                       
...
```


### Project Template
  * background 
  * problem
  * method and implementation (source code)
  * conclusion and discussion
  * reference
  
### Source Code Guideline
  * make BASH functions in linux/mac command line environment 
  * run : <program> [option] <input arguments> .. <output>
