# bioinfgloss

A tentative glossary of terms used within bioinformatics. Many of these are biology and genetics terms, and indeed there are plenty places on the internet to read their definitions, but because their nature is somewhat looser than the way computational terms are defined, the following includes accounting for this lack of tight meaning-to-word binding by at least admitting it exists.

E

Effective population size:
Simply put: the number of individuals that achieve repdocutive success.


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

T

* Tandem Repeat
A sequence segment that repeats itself a regular distance apart. If this distance is the same as its length, the "tandem" may be left out.

* Tandem Repeat Finder (TRF)
Very established tool often used by default by everyone for identifying tandem repeats. Only available as a binary.

* Tajima's D
A statistic giving information on the amoutn of variation in DNA from individuals (usually of a population). In an alignment of DNA from several individuals, the actual pairwise differences in nucleotides at each position is calculated, this is theta. Then pi, the number of expected differences is caluclated from the segregating sites, and this is subtracted from theta. If the answer is negative, it means we have below average variation, which, if not small, suggests little variation, a selective sweep maybe. If positive, then variation is quite high, suggesting a population which is breeding successfully and often over a long period of time.
