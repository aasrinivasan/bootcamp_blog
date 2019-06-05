# Study of ColEL Using Expression Public Data

### Finding relavant data in short read archive

We searched [NCBI RSA](https://www.ncbi.nlm.nih.gov/sra) with the following query:
````
(((((("escherichia coli"[Organism]) 
AND "illumina"[Platform])
AND "transcriptomic"[Source]) 
AND "rna seq"[Strategy]) 
AND ("2018"[Publication Date] : "2019"[Publication Date]))) 
AND "Escherichia coli"[orgn:__txid562] 
````

### Possible good hit: PRJNA459526
