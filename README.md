# TrimGalore
Fork of Babraham Bioinformatics's Trim Galore

This fork is compatible with regular Trim Galore, so there's no need to modify your scripts.

##Added features:
  1. Ability to specify custom paths to FastQC
  2. Zipping works on Mac OSx - No more zcat can't stat error

##Added flags:
  1. `trimgalore -path_to_fastqc path/to/fastqc`, where `path/to/fastqc` is the path to your FastQC executable
