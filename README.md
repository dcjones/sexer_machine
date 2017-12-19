
# sexer_machine

A simple tool to determine sex from a collection RNA-Seq samples.

It works by counting the proportion of alignments to the Y chromosome and XIST
gene and fitting a 2-dimensional, 2-component Beta mixture model.

Use it kinda like this:
```
sexer_machine genes.gff3 *.bam > results.csv
```

Needs the following packages:
  * ArgParse
  * BioAlignments
  * Distributions
  * GenomicFeatures
  * Optim


