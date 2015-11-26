
B

* Bowtie:
An aligner. Clearly this is version 1 of Bowtie, and should, like many other versions of programs which have been superceded by later versions, be deprecated in favour of Bowtie2. However, it is not entirely deprecated which, though uncommon, is hardly a exception to the rule. This is most often due the speed and agility of the less sophisticated version, and its treatment of certain cases which the newer version of the program is more awkward with. In summary, there are certain cases, when it may be more beneficial to run this version 1 of Bowtie.

* Bowtie2
Second version of the Bowtie aligner. A common invocation:
bowtie2 -x indexes/e_coli -U simulated_reads/sim_reads.fq -S alignments/sim_reads_aligned.sam
Note the "-x" for index. This illustrates in fact the second stage of the alignment process because the first stage is the indexing of the reference genome. Bowtie2 will also index, but often this is not shown because it is assumed that the user knows that indexing is very often necessary.


* Eigensoft
Probably the most popular tool for PCA analysis, this consists of "smartpca" which does the main PCA analysis and also "eigenstrat" which takes into account the population structure.



* Orthomcl
For finding orthologs.

* Principal component analysis (PCA):
This is a widely used method casts a dataset onto an orthogonal, multidimensional system of axes of variation. Often, certain axes are very much more important than others, as revealed by their corresponding eigenvalues, and so the unimportant axes are often ignored, and so the method achieves the effect of reducing the dimensionality of problem, naking it easier to analyse.

* Stacks
This is a popgen tool, so it's about getting sequences from members of a population, that often are related. The site says it's also about tracking loci, but that's often the aspiration.
