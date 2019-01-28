Software to look into
* MUMmer
* LAGAN
* SOAPdenovo

OS environment: genobuntu
* Genome Assembly Ubuntu Package’ (http://sourceforge.net/ projects/genobuntu/, http://people.tamu.edu/?bilalwajidabbas/ Genobunu.html)

Genome assembly steps, metrics, and more
https://wurmlab.github.io/genomicscourse/2017/practicals/reference_genome/assembly
https://www.biostars.org/p/75489/

assemblathon is a resource
metassembler
clc genomics workbench

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
    - PEAR
   ~~~
  * Reference Guided
    * Must be closely related
  ~~~
  Software
    * bwa/bowtie
    * SMALT PILON
  ~~~ 
   * Hybrid approach
    * Assembly guided by a reference genome of a closely related organism
    ### probably the approach I want to take
   ~~~
    * AlignGraph
   ~~~
### Long Read error correction
LoRDEC for pacbio using illumnia short read
* assembly improvement  
  * polishing:
   Fixing short indels and miscalls
   * Software: PILON, IMAGE2
  * gap filling:
   Remove N's and extending contig ends
   * Software: Sealer (ABySS), PILON, GMcloser, IMAGE2 •
  * contig integration:
   merging two assemblies
  * automated snp calling for reference guided assemblies
* Assembly quality assesment
 * Software: Quast, SuRankCo, qaTools

### Hi-C assembly steps

Add software for each step
Describe process and purpose
