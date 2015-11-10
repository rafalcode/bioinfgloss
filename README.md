# bioinfgloss

A tentative glossary of terms used within bioinformatics. Many of these are biology and genetics terms, and indeed there are plenty places on the internet to read their definitions, but because their nature is somewhat looser than the way computational terms are defined, the following includes accounting for this lack of tight meaning-to-word binding by at least admitting it exists.


A

* Alignment:
A "matching up" of one, two or more sequences in order to expose their similarity, and, by the same token, their differences. In the special case of a one sequence alignment, this concerns matching it with itself, a case which will give different results simply because there are different alignment algorithms and scoring methods. It is hard to overestimate the importance of alignments in bioinformatics, a fact which occasionally gets challenged in the shape of "alignment-free" algorithms. Much of this importance is due to the fact that the concept of variation is an extremely necessary one within evolution, and variation needs an alignment in order to manifest itself.


E

Effective population size:
Simply put: the number of individuals that achieve reproductive success in a population.

Evolution:


I

* Infinite sites model:
A term that dates from pre-sequencing days, which officially is defined as "Each gene is made of a sequence of sites, and each time a mutation occurs, it affects a site that was previously unaffected". Essentially this means that the number of mutations will be at least the number of sites affected, and never less. In other words, given a time period, mutations will not hit the same site twice (or more times) ever. And, in further words it means that each mutation will have its own site, and therefore mutation sites are unique. Itäs one of the common simplifcations that are often used, similar to, say, the random mating assumption.

* Insert (of paired short reads)
As part of the sequencing technology, fragments of DNA yield two short reads, one from either end. The insert, or also insert size, is the difference between the ends of both reads. So if the reads are 90bp, and the insert size is 200bp, you can assume that the fragment was 380bp long.

G

* Gene:
The molecular unit of heredity. It's not amiss to say that the definition, though quite stable in the 21st century, has gone through refinements in meaning in the past, and this fact reflects the "otherness" of the concept it belies: it has proved quite difficult to give it precise boundaries in meaning ever since Mendel first came up with the idea and called it "factor".

* Gene Expression Profiling
This allows identification of the type of cell from which the mRNA was extracted. Depending on the certain locations and role, certain genes will be off, and will produce no mRNA. They will therefore not be detected in RNAseq, although they may be detected in mRNA from other cells, it depends on t he experiment.

* Gene Expression Abundance Estimation
This should be about quantifying which genes are highly expressed, and (in many ways, by implication) genes which are lowly expressed or simply switched off.

* Genotype:
The available genetic code for an organism as given in its DNA. It's not too inaccurate to say that it forms the blueprint for the activities that the organism will comprise, though this is quite a big simpification too. It's perhaps easier to say that the genotype is the recipe for the proteins that the organism will consist of, and these protein will do all work. It's worthwhile to point out that blueprints are often merely plans, and also consist of bare instructions. There is a strong similarity too, to a computer program which has not yet been executed. WHen the genotype is executed, or in other senses, exercised, a phenotype results.

L

* Luria-Delbrück experiment
A famous experiment which established considerable weight for the mechanism of evolution via spontaneous random mutations. It is in fact, a rather simple experiment, both biologically, and indeed mathematically, but its central effect can sometimes seem elusive. Cultures of ecoli are allowed develop and then presented with a killer phage that kills all of them. No, not all of them. Similarly to the Asterix village in Goscinny and Uderzo's famous comic, a small amount survive and expand because they happen to have developed immunity to the phage ( this also a good example of a selective sweep). The central question is, is this immunity due to a reaction to the phage, or is it due to a prior mutation which accidentally occured before the phage was ever introduced? The conclusion of the experiment is the latter.

S

Selective sweep:
Another tongued-tied attempt to avoid calling a spade, a spade. In much more brutal terms, a selective sweep is an annihilation of a significant part of a population due to (one expects) particularly strong, selective pressure. A good example is the Luria-Delbrück experiment, whereby cultures of Ecoli are presented with a nasty phage which destroys all of them. Oh, not all of them, no. Please see Luria-Delbrück entry for more information.

T

* Tandem Repeat
A sequence segment that repeats itself a regular distance apart. If this distance is the same as its length, the "tandem" may be left out.

* Tandem Repeat Finder (TRF)
Very established tool often used by default by everyone for identifying tandem repeats. Only available as a binary.

* Tajima's D
A statistic giving information on the amount of variation in DNA from individuals (usually of a population). In an alignment of DNA from several individuals, the actual pairwise differences in nucleotides at each position is calculated, this is theta. Then pi, the number of expected differences is calculated from the number of segregating, or variant, sites, and this is subtracted from theta. If the answer is negative, it means we have below average variation, given the number of segregating sites. If this this happens to be substantially negative, it may suggest a selective sweep and give us information about the history of the population. It's worthwhile that variation can occur along two parameters here: via the number of segregating sites, and the amount of variation within those sites. As is common in statistical measures, Tajima's D lump both of these together.

