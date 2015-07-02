# Bismark
A bisulfite read mapper and methylation caller

This is a branch of
[Bismark v0.14.3](http://www.bioinformatics.babraham.ac.uk/projects/bismark/)
by the Babraham Institute. The branch fixes a problem appearing in genome
preparation which occasionally lets the script return premature, leaving a
zombie bowtie-build instance.
