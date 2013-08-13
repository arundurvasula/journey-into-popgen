Hamilton, Matthew. *Introduction to Population Genetics*. Oxford: Wiley-Blackwell, 2009. Print.
## Chapter 1

- **expectations** can be defined as the expected value of a random variable (especially the average)
- popgen consists of constructing and testing expectations for genetic variation in populations of individual organisms.
- first principles: Mendelian inheritance, mutation, mating patterns, gene flow, and natural selection
    - need to keep these in mind at all times
- **parameters** are idealized quantities. They are assumed to have exact values.
    - idealized means messy real-life details of how to measure quantities are ignored
- **parameter estimates** are given by sampling a population and measuring the parameter you're interested in.
    - in all populations, a parameter will have **one** true value. In order to get that value, you need to measure every individual. Therefore, in the interest of getting things done, we use parameter estimates.

- What good is a theory if it is based on so many assumptions?
    - a theory can elucidate assumptions and generate testable predictions. These predictions can be found false and eliminated. 
    - Reducing the complexity of a population is useful to determine the variables that influence a population parameter.
    
## Chapter 2

### Mendel

- 1st law: independent segregation of alleles at a single locus: two members of a gene pair segregate separately into gametes so that half of the gametes carry one allele and the other half carries the other allele
- 2nd law: independent assortment

### Hardy-Weinberg

- `p^2` -> major allele freq
- `q^2` -> minor allele freq
- `2pq` -> heterozygote freq

		p^2 + 2pq + q^2 = 1

- assumptions: the organism is diploid, reproduction is sexual (as opposed to clonal), generations are discrete and non-overlapping, the locus under consideration has two alleles, allele frequencies are identical among all mating types (i.e. sexes), mating is random (as opposed to assortative), there is random union of gametes, population size is very large, effectively infinite, migration is negligible (no population structure, no gene flow), mutation does not occur or its rate is very low, natural selection does not act (all individuals and gametes have equal fitness).
- HW provides a **null** model where no biological processes are acting
- HW suggests that the process of inheritance itself does not cause changes in allele frequency across generations. Therefore, changes in allele freq must be departures from the HW expected genotype freqs which are caused by processes that alter the outcome of inheritance (eg biological processes)
- HW loves Chi-squared 

### Fixation index and heterozygosity

- *F* measures the deviation from HW freqs
- **assortative mating** -> non random mating  
     - positive is when individuals with like genotypes mate
     - negative is the opposite
- **consanguineous mating** or **biparental inbreeding** describes mating among related individuals (inbreeding)
    - increases the probability that the resulting progeny are homozygous compared to random mating. 
    - relatives share more alleles -> progeny get the same alleles
- `H_e` -> expected freq of heterozygotes (from HW)
- `H_o` -> observed freq of heterzygotes

        F = (H_e - H_o)/ H_e
- negative values indicate more heterozygotes compared to HW freq
- positive values indicate more homozygotes compared to HW freq
- *F* can be interpreted as the correlation between the two alleles sampled to make a diploid genotype
    - given that one allele has been sampled from the population, if the frequency of the second allele is ~ identical, there is a positive correlation (if A then A/ if a then a). If the second allele is not identical there is a negative correlation (if A then a/if a then A)

### Mating among relatives

- Consanguineous mating alters genotype frequencies but not allele frequencies
- Given a diallelic locus AA, when there is positive genotypic assortative mating, the heterozygote (*H*) genotype frequency will be halved every generation, eventually being lost in the population. The number of A and a alleles will stay the same (allele frequencies), but the number of heterozygotes vs homozygotes (genotype frequencies) will change. 
- While heterozygotes decrease by 1/2 every generation, homozygotes increase by 
 		
 		H/2*(1-1/2*t)
 where t is the number of generations

- Effects of consanguineous mating can also be thought of as increasing the probability that two alleles at one locus in an individual are in herited from the same ancestor. 
	- Results in a homozygous locus
	- considered **autozygous** because the alleles are inherited by a common ancestor.
- **Allozygous** means two alleles were not inherited from the same ancestor in recent past.
- Degree of relatedness is expressed as 2 times the probability of autozygosity. 
- *f* is coefficient of inbreeding which is inbreeding in the autozygous sense.
- Identity by descent is transmission from a common ancestor. 
- Inbreeding depression is a deleterious consequence of inbreeding and is associated with a decline in the average phenotype in a population.
- The opposite, heterosis, is a phenomenon in which hybrids show increased viability and reproduction as a result of increased heterozygosity.
- Dominance hypothesis of inbreeding depression: recessive alleles that cause lowered fitness are more frequently found in homozygous genotypes under consanguineous mating. This exposes the deleterious phenotype and the genotype will decrease in frequency in a population by natural selection. 
	- Reduction in frequency of deleterious alleles in called **purging of genetic load**. It increases the frequency of alleles that do not have deleterius effects when homozygous so that the average phenotype in a population returns to the initial average before the inbreeding. 
- Over dominance hypothesis: doesn't predict a purging effect with inbreeding, only that the frequency of heterozygotes will decrease and not recover until mating patterns change.
	- Even if heterozygotes appear and have a fitness advantage, each generation of mating will reconstitute the homozygous genotypes (Mendelian segregation) so that purging cannot occur.
- Degrees of inbreeding depression depend on the phenotype begin considered: in plants, earlier traits (e.g. germination) are less affected than later traits (e.g. growth, reproduction). 
- Inbreeding is a complicated term and can refer to many things:
	- consanguinity or kinship of two different individuals
	- autozygosity of two alleles either within an individual or sampled at random
	- the fixation index and HW expected/observed frequencies, especially when there is an excess of homozygotes
	- inbreeding depression
	- the description of the mating system of a population or species (as inbred)
	- genetic subdivision of a species into populations that exchange limited levels of gene flow such that individual populations increase in autozygosity
	- the increase in homozygosity in a population due to its finite size

### Gametic disequilibrium

- 1902 paradox (Sutton & Boveri): haplotypes should appear in frequencies proportional to the product of allele frequencies, but there are not enough chromosomes to represent each trait. Therefore, if chromosome segregation does not account for different phenotypes, something else has to
- Recombination!
- Now, the frequency of a two-locus gamete haplotype will depend on two factors: 
	a. allele frequencies
	b. amount of recombination between the two loci

- Model based on recombination:

		A_1        B_1
		--------------
		--------------
		A_2        B_2

    