# Bismark
A bisulfite read mapper and methylation caller

This is a branch of
[Bismark v0.14.5](http://www.bioinformatics.babraham.ac.uk/projects/bismark/)
by the Babraham Institute. The branch fixes some problems in process management
and error reporting.

## Deprecation Warning

Bismark has moved to GitHub as of November 2015. So there is an [official Bismark repository](FelixKrueger/Bismark) now. The current official Bismark release incorporates all changes I made. Please ignore this branch.

## Changelog

- in genome preparation: script now synchronizes with child process instead of
  returning premature
- in genome preparation: exit values of bowtie-build calls are now handed up to
  the OS
