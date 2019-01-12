
### initial assembly steps 
* quality control and pre-processing
  * remove barcodes
  * remove poor quality reads
  * filter duplicates  
  ~~~
  software
    * Sickle
    * Quake
    * Prinseq
    * FastQC
  ~~~  
* initial read assembly
  * De Novo
  ~~~ 
  Software
    * SPAdes
    * ABySS
    * Velvet
    * EDENA
    * DISCOVAR
   ~~~
  * Reference Guided
    * Must be closely related
  ~~~
  Software
    * bwa/bowtie
    * SMALT PILON
  ~~~ 
  
* assembly improvement  
  * polishing/gap filling
  * contig integration
  * automated snp calling for reference guided assemblies
* Assembly quality assesment

### Hi-C assembly steps

Add software for each step
Describe process and purpose
