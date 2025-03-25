# AD_MapATACseq

Note --- I use Bowtie2 for mapping and aligning reads for ATACseq. You will need to use a Bowtie-indexed genome to map reads.
For N. crassa, a Bowtie index I created is set to the default genome. For any other fungus, you will need to index your genome using the following script with Bowtie loaded:

module load Bowtie2/2.5.2-GCC-11.3.0

bowtie2-build [options]* <reference_in> <bt2_base>

where reference_in is your reference genome FASTA file and bt2_base is the basename for the genome. 

