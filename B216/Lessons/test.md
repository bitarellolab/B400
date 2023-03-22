Download the files


```
%%shell

mkdir fastqdata
cd fastqdata
```

```
%%shell

wget https://raw.githubusercontent.com/bitarellolab/Teaching/main/B216/filestoshare/fastq/Female2-oral1.fastq
wget https://raw.githubusercontent.com/bitarellolab/Teaching/main/B216/filestoshare/fastq/Male5-oral1.fastq
wget https://raw.githubusercontent.com/bitarellolab/Teaching/main/B216/filestoshare/fastq/Male5-oral2.fastq 
```


```
%%
conda install -c bioconda fastqe
```



```
fastqe *fastq
```


```

```
