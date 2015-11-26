# bioinfgloss

A tentative glossary of terms used within bioinformatics. Many of these are biology and genetics terms, and indeed there are plenty places on the internet to read their definitions, but because their nature is somewhat looser than the way computational terms are defined, the following includes accounting for this lack of tight meaning-to-word binding by at least admitting it exists.


A

* Alignment:
A "matching up" of one, two or more sequences in order to expose their similarity, and, by the same token, their differences. In the special case of a one sequence alignment, this concerns matching it with itself, a case which will give different results simply because there are different alignment algorithms and scoring methods. It is hard to overestimate the importance of alignments in bioinformatics, a fact which occasionally gets challenged in the shape of "alignment-free" algorithms. Much of this importance is due to the fact that the concept of variation is an extremely necessary one within evolution, and variation needs an alignment in order to manifest itself.


E

* Effective population size:
Simply put: the number of individuals that achieve reproductive success in a population.

* Evolution:
The manner in which change comes about in biological species over long periods of time. Note that it is not simply "mere change" because that could be chaotic, after all. There is clearly some organization to evolution, which necessarily must be self-organization if we want to exclude any external beings. Evolution can also be said to take place in non-biological entities too, like rounded pebbles on the shore (but never spherical, why not? Discuss.) and the meandering of rivers. Events occur within other events, and so are circumscribed by them


G

* Gene regulation:
This if often called upon to explain phenomena which occur outside of the instructions provided by an individual''s exome.

* Genotype:
The particular genetic sequence that an individual can be made up of. If there is only a single copy, then the individual is haploid, and only gener regulation can get int he way of 

* Genotyping:
Here we have the verbal equivalent of the word genotype, and it has several strings to its proverbial bow. It's mostly about diploids and working out what an individual is coded for at a particular locus. The simplest and very common genotype is for a SNP, so it's a question of find ing out whther the individual is AA, aa (and so, homozygous) or Aa, heterozygosity. But it's by no means the only type of genotypization (I'm sure that word does not exist) that can occur. I won't elaborate on these others. Another meaning, which comes up in 23andme is the idea that it's a short-cut to full sequencing because it focuses on sites which vary and ignores though that are the same. Often though it's not all the variant sites at all, but only those in certain sites which have a priori been identified as interesting. And of course it means getting both the nucleotides at a site for a diploid. In any case, there are times when genotyping and sequencing come together closely in meaning, and both actually are similarly fuzzy in the extent of work done. Sequencing is a rawer concept, meaning calling contiguous bases in DNA while genotyping is about calling variants - commonly the alleles of SNPs - but these can't be contiguous of course, and whther they are in order is another matter.

I

* Infinite sites model:
A term that dates from pre-sequencing days, which officially is defined as "Each gene is made of a sequence of sites, and each time a mutation occurs, it affects a site that was previously unaffected". Essentially this means that the number of mutations will be at least the number of sites affected, and never less. In other words, given a time period, mutations will not hit the same site twice (or more times) ever. And, in further words it means that each mutation will have its own site, and therefore mutation sites are unique. It's one of the common simplifications that are often used, similar to, say, the random mating assumption. So it's meant to make your life easier, but, if you don't understand what it means, it won't do. The naming of this term is not very apparent, but it must be remembered that by "model" we probably mean a mutation model, and the opened-ended nature of this assumption means that the mutations can be infinite. That's more or less it!

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

I

* Isoform:
Speaking clearly, this is one of the alternatively spliced forms of a certain gene. Speaking unclearly, well it can be anything you want really. This link backs this tight definition up: http://seqanswers.com/forums/showthread.php?t=42925


L

* Luria-Delbrück experiment
A famous experiment which established considerable weight for the mechanism of evolution via spontaneous random mutations. It is in fact, a rather simple experiment, both biologically, and indeed mathematically, but its central effect can sometimes seem elusive. Cultures of ecoli are allowed develop and then presented with a killer phage that kills all of them. No, not all of them. Similarly to the Asterix village in Goscinny and Uderzo's famous comic, a small amount survive and expand because they happen to have developed immunity to the phage ( this also a good example of a selective sweep). The central question is, is this immunity due to a reaction to the phage, or is it due to a prior mutation which accidentally occured before the phage was ever introduced? The conclusion of the experiment is the latter.


P

* Pooling samples
Though examining inter-sample variance is the usual aspiration, sometimes a good, and faster course-of-action is to lump them altogether in a group as a pool. Lump sounds too amateurish, so the word used is pool, suggesting that some thought goes into it, which it may do indeed.

R

* RNA-seq
Has become somewhat of an umbrella (unfocused) term, but in narrower terms it's a method of sequencing coding DNA, because RNA does not include non-coding regions, and furthermore this only represents DNA which has been expressed, so RNAseq is very dependent on the type of tissue the samples came from. This last fact is often omitted, and this could be for several reasons. Often samples from various tissues of interest and are then pooled together. Also the tissue of interest may already be in the context of the study. For example when the neurology or nervous system of an organism is of principle interest, it should be assumed that that is where the RNAseq mostly comes from, and one is especially interested in finding movel genes there.

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

Transcript:
This word can be used quite loosely, but it's really an expressed sequence, something obtained via -hopefully- some sort of assembly of RNAseq reads.
