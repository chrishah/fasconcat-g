# fasconcat-g
Ubuntu 16.04 with FASTconCAT v1.04 installed

```bash
docker run -it --rm chrishah/fasconcat-g:1.04 FASconCAT-G.pl
#quit with 'q'
```

__Example:__ Concatenate all fasta files ('\*.fas') into a supermatrix in fasta format
```bash
docker run -it -v $(pwd):/in/ -w /in/ --rm chrishah/fasconcat-g:1.04 FASconCAT-G.pl -a -a -s
```
