# Bismark
A bisulfite read mapper and methylation caller

This is a branch of
[Bismark v0.14.3](http://www.bioinformatics.babraham.ac.uk/projects/bismark/)
by the Babraham Institute. The branch fixes some problems in process management
and error reporting.

## Changelog

- in genome preparation: script now synchronizes with child process instead of
  returning premature
- in genome preparation: exit values of bowtie-build calls are now handed up to
  the OS
