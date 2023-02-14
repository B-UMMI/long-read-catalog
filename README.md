# long-read-catalog
This repository intends to be a collective effort towards the construction of a useful catalog of tools appropriate to use on long-read sequencing data.

## Long-Read (General)

### QA/QC and Trimming
* [Filtlong](https://github.com/rrwick/Filtlong) - quality filtering tool for long reads
* [chopper](https://github.com/wdecoster/chopper) - intended for long read sequencing such as PacBio or ONT, filters and trims a fastq file

### Mapping
* [minimap 2](https://github.com/nanoporetech/minimap2) - A fast sequence mapping and alignment program

### Assembly
Comparison available [here](https://github.com/rrwick/Long-read-assembler-comparison).
* [Unicycler](https://github.com/rrwick/Unicycler) - hybrid assembly pipeline for bacterial genomes (miniasm and spades with racon and pilon for polishing)
* [miniasm](https://github.com/lh3/miniasm) - Ultrafast de novo assembly for long noisy reads (though having no consensus step)
* [canu](https://github.com/marbl/canu) - A single molecule sequence assembler for genomes large and small
* [Flye](https://github.com/fenderglass/Flye) - Fast and accurate de novo assembler for single molecule sequencing reads

### Polishing
* [Racon](https://github.com/isovic/racon) - Ultrafast consensus module for raw de novo genome assembly of long uncorrected reads.

### Structural Variation
* [Sniffles](https://github.com/fritzsedlazeck/Sniffles) - structural variation caller using third generation sequencing (PacBio or Oxford Nanopore)

### Read Simulation
Comparison available [here](https://github.com/rrwick/Badread/tree/master/comparison)
* [Badread](https://github.com/rrwick/Badread) - a long read simulator that can imitate many types of read problems
* [LongISLND](https://github.com/bioinform/longislnd) - Long In silico Sequencing of Lengthy and Noisy Datatypes
* [SiLiCO](https://github.com/ethanagbaker/SiLiCO) - a simulator of long read sequencing in pacbio and oxford nanopore

### Misc
* [MetaMaps](https://github.com/DiltheyLab/MetaMaps) - simultaenously carries out read assignment and sample composition estimation
* [krocus](https://github.com/andrewjpage/krocus) - MLST from long reads
* [ngmlr](https://github.com/philres/ngmlr) -  long-read mapper designed to align PacBio or Oxford Nanopore (standard and ultra-long) to a reference genome with a focus on reads that span structural variations
* [MEGAN-LR](https://link.springer.com/article/10.1186/s13062-018-0208-7#Abs1) -  long-read and contig binning algorithm
* [MAIRA](https://www.wsi.uni-tuebingen.de/lehrstuehle/algorithms-in-bioinformatics/software/maira) -  real-time taxonomic and functional analysis of long reads on a laptop


## Oxford Nanopore 

### QA/QC and Trimming
* [NanoPlot](https://github.com/wdecoster/NanoPlot) - Plots and Statistics for quality evaluation
* [NanoQC](https://github.com/wdecoster/nanoQC) - Quality control tools for long read sequencing data aiming to replicate some of the plots made by fastQC
* [NanoStat](https://github.com/wdecoster/nanostat) - Simple statistic summary 
* [Porechop](https://github.com/rrwick/Porechop) - adapter trimmer and demultiplexer for Oxford Nanopore reads (abandonware since Oct 2018)
* [poretools](https://github.com/arq5x/poretools) - a toolkit for working with Oxford nanopore data
* [MinIONQC](https://github.com/roblanf/minion_qc) - fast and simple quality control for MinION sequencing data
* [nanofilt](https://github.com/wdecoster/nanofilt) - Filtering and trimming of long read sequencing data 

### Basecalling 
Comparison available [here](https://github.com/rrwick/Basecalling-comparison).
* Albacore - Oxford Nanopore's official command-line basecaller (requires account) 
* [Guppy]() - GPU basecaller (in development)
* [Scrappie](https://github.com/nanoporetech/scrappie) - research basecaller
* [DeepNano](https://bitbucket.org/vboza/deepnano) - developed by Vladimír Boža and colleagues at Comenius University 
* [Chiron](https://github.com/haotianteng/chiron) -  third-party basecaller developed by Haotian Teng and others in Lachlan Coin's group at the University of Queensland 

### Demultiplexing
* [Deepbinner](https://github.com/rrwick/Deepbinner) - a signal-level demultiplexer for Oxford Nanopore reads
* [Porechop](https://github.com/rrwick/Porechop) - adapter trimmer and demultiplexer for Oxford Nanopore reads (abandonware since Oct 2018)
* Albacore - Oxford Nanopore's official command-line basecaller (requires account) 
* [qcat](https://github.com/nanoporetech/qcat) - Python command-line tool for demultiplexing Oxford Nanopore reads from FASTQ files

### Polishing
* [nanopolish](https://github.com/jts/nanopolish) - Software package for signal-level analysis of Oxford Nanopore sequencing data.
* [npScarf](https://github.com/mdcao/npScarf) - scaffolds and completes draft genomes assemblies (spades) in real-time with Oxford Nanopore sequencing.

### Structural Variation
* [nanoSV](https://github.com/mroosmalen/nanosv) - SV caller for long-read (only tested in nanopore)

### Read Simulation
* [NanoSim](https://github.com/bcgsc/nanosim) - Nanopore sequence read simulator

### Misc
* [nanocomp](https://github.com/wdecoster/nanocomp) - Comparison of multiple long read datasets


## PacBio 

### QA/QC and Trimming
* [proovread](https://github.com/BioInf-Wuerzburg/proovread) - PacBio hybrid error correction through iterative short read consensus

### Demultilexing
* [lima](https://github.com/PacificBiosciences/barcoding) - Lima, the PacBio barcode demultiplexer, is the standard tool to identify barcode sequences in PacBio single-molecule sequencing data. 

### Alignment
* [blasr](https://github.com/PacificBiosciences/blasr) - The PacBio® long read aligner

### Read Simulation
* [PBSIM](https://github.com/pfaucon/PBSIM-PacBio-Simulator) - This is an updated mirror of the original PacBio Read Simulator

### Misc
* [pb-jelly](https://sourceforge.net/p/pb-jelly/wiki/Home/) - highly automated pipeline that aligns long sequencing reads (such as PacBio RS reads or long 454 reads in fasta format) to high-confidence draft assembles.
