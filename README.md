# vcf2tsv
a tool that takes the output files of different callers and creates maf-like, row-based output. As of 7/6/15 it is used in
the bic pipeline, but will likely be obviated by vcf2maf.

It can handle the output from mutect, varscan, unified genotyper, haplotypecaller, somatic sniper and strelka. For mutect, it
produces a file that draws from both the vcf and out file.
