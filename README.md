# TrimGalore
Fork of Babraham Bioinformatics's Trim Galore

This fork is compatable with regluar Trim Galore, so there's no need to modify your scripts.

##Added features:
  1. Ability to specifiy custom paths to FastQC
    How? By specifying the flag `-path_to_fastqc my/unique/path/to/fastqc` when you use the `trimgalore` command
  2. Zipping works on Mac OSx
    No more zcat can't stat error
