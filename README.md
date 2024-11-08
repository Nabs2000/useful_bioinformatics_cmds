# Useful Bioinformatics Commands

## Samtools Library
- `samtools fastq -@ 4 -o reads.fastq unaligned.bam`: Convert a BAM file into a FASTQ file; useful for realignment
- `samtools view -H input.bam`: View the header of a BAM file
- `samtools sort -T prefix -O mapped_input_reads.bam > sorted_reads.bam`: Sort the mapped input reads, specifying temporary files to prefix.xxx.bam

## Snakemake
- `snakemake -np target`: Do a dry-run (`n`) and print out the resulting shell command (`p`)
- `snakemake --cores num_cores target`: Execute a workflow using a specified number of cores to create target file
