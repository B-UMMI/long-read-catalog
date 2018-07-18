# long-read-catalog
This repository intends to be a collective effort towards the construction of a useful catalog of tools appropriate to use on long-read sequencing data.

## Long-Read (General)

### QA/QC and Trimming

### Mapping
* [minimap 2](https://github.com/nanoporetech/minimap2) - A fast sequence mapping and alignment program

### Assembly
* [Unicycler](https://github.com/rrwick/Unicycler) - hybrid assembly pipeline for bacterial genomes (miniasm and spades with racon and pilon for polishing)
* [miniasm](https://github.com/lh3/miniasm) - Ultrafast de novo assembly for long noisy reads (though having no consensus step)
* [canu](https://github.com/marbl/canu) - A single molecule sequence assembler for genomes large and small

### Polishing
* [Racon](https://github.com/isovic/racon) - Ultrafast consensus module for raw de novo genome assembly of long uncorrected reads.

## Oxford Nanopore 

### QA/QC and Trimming
* [NanoPlot](https://github.com/wdecoster/NanoPlot) - Plots and Statistics for quality evaluation
* [NanoQC](https://github.com/wdecoster/nanoQC) - Quality control tools for long read sequencing data aiming to replicate some of the plots made by fastQC
* [NanoStat](https://github.com/wdecoster/nanostat) - Simple statistic summary 
* [Porechop](https://github.com/rrwick/Porechop) - adapter trimmer and demultiplexer for Oxford Nanopore reads
* [Filtlong](https://github.com/rrwick/Filtlong) - quality filtering tool for long reads

### Basecalling 
Comparison available [here](https://github.com/rrwick/Basecalling-comparison).
* Albacore - Oxford Nanopore's official command-line basecaller (requires account) 
* [Guppy]() - GPU basecaller (in development)
* [Scrappie](https://github.com/nanoporetech/scrappie) - research basecaller
* [DeepNano](https://bitbucket.org/vboza/deepnano) - developed by Vladimír Boža and colleagues at Comenius University 
* [Chiron](https://github.com/haotianteng/chiron) -  third-party basecaller developed by Haotian Teng and others in Lachlan Coin's group at the University of Queensland 

#### Demultiplexing
* [Deepbinner](https://github.com/rrwick/Deepbinner) - a signal-level demultiplexer for Oxford Nanopore reads
* [Porechop](https://github.com/rrwick/Porechop) - adapter trimmer and demultiplexer for Oxford Nanopore reads
* Albacore - Oxford Nanopore's official command-line basecaller (requires account) 

## PacBio 

### QA/QC and Trimming
