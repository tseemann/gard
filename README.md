# gard
Gonococcal Antimicrobial Resistance Detection

##Introduction

`Gard` is a command-line software tool to identify Gonococcal
antimicrobial resistance markers in whole genome sequencing data.
It works directly on FASTQ files, bypassing any genome assembly step.
It identifies both SNPs and acquired genes contributing to resistance.

##Usage

```sh
% gard -1 gono_R1.fastq.gz -2 gono_R2.fastq.gz
```

##Feedback

Report bugs and give suggesions on the 
[Issues page](https://github.com/tseemann/gard/issues)

##License

[GPL Version 3](https://raw.githubusercontent.com/tseemann/gard/master/LICENSE)

##Authors
* Torsten Seemann
* Jason Kwong
* Robyn Lee
