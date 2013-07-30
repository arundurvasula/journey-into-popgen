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
- `p^2 + 2pq + q^2 = 1`
- assumptions: the organism is diploid, reproduction is sexual (as opposed to clonal), generations are discrete and non-overlapping, the locus under consideration has two alleles, allele frequencies are identical among all mating types (i.e. sexes), mating is random (as opposed to assortative), there is random union of gametes, population size is very large, effectively infinite, migration is negligible (no population structure, no gene flow), mutation does not occur or its rate is very low, natural selection does not act (all individuals and gametes have equal fitness).
- HW provides a **null** model where no biological processes are acting
- HW suggests that the process of inheritance itself does not cause changes in allele frequency across generations. Therefore, changes in allele freq must be departures from the HW expected genotype freqs which are caused by processes that alter the outcome of inheritance (eg biological processes)
- HW loves Chi-squared 

### Fixation index and heterozygosity

- *F* measures the deviation from HW freqs
- **assortative mating** -> non random mating  
     - positive is when individuals with like genotypes mate
     - negative is the opposite
- **consanguineous mating**/**biparental inbreeding** describes mating among related individuals
    - increases the probability that the resulting progeny are homozygous compared to random mating. 
    - relatives share more alleles -> progeny get the same alleles
- `H_e` -> expected freq of heterozygotes (from HW)
- `H_o` -> observed freq of heterzygotes

        F = (H_e - H_o)/ H_e
- negative values indicate more heterozygotes compared to HW freq
- positive values indicate more homozygotes compared to HW freq
- **F** can be interpreted as the correlation between the two alleles sampled to make a diploid genotype
    - given that one allele has been sampled from the population, if the frequency of the second allele is ~ identical, there is a positive correlation (if A then A/ if a then a). If the second allele is not identical there is a negative correlation (if A then a/if a then A)

### Mating among relatives


    