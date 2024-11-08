# Useful Bioinformatics Commands

## Samtools Library
- `samtools fastq -@ 4 -o reads.fastq unaligned.bam`: Convert a BAM file into a FASTQ file; useful for realignment
- `samtools view -H input.bam`: View the header of a BAM file

## Snakemake
- `snakemake -np input`: Do a dry-run (`n`) and print out the resulting shell command (`p`)
- `snakemake --cores num_cores input`: Execute a workflow using a specified number of cores
