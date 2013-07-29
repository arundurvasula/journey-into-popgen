This book: http://books.google.com/books?id=l5Z1q-8s2hgC&lpg=PP1&pg=PP1#v=onepage&q&f=false Chapter 12
## Introduction
- Variation in neutral alleles can be reduced by selection at linked loci against deleterious alleles (Charlesworth, Morgan, and Charlesworth)
    - Neutral alleles are linked to deleterious alleles and when deleterious alleles are selected against they also select against neutral alleles because they are linked
    - Background selection (bs)
- CMC also derived formulas to approximate the reduction in nucleotide diversity
- CMC suggested that bs could be detectable in smaller populations with Tajima's test of neutrality based on D.  

## The model
- `Pi` -> nucleotide diversity
- `Mu` -> neutral mutation rate per site per generation
- `N` -> diploid population size
- `Sn` -> number of polymorphic sites per base pair in a sample size of n
- **Expected** value of pi is give like this:

        E(pi) = 4*N*mu
    
- **Expected** value of Sn is given by:
    
        E(Sn) = 4*N*mu*sum[j=1:n-1](1/j)
    
- Equilibrium is for a neutral locus that is isolated: unlinked to loci where selection occurs
- Consider the following model:
    - there is a neutral locus linked to several loci where a deleterious mutation can occur.
    - this locus is completely linked, so it can be considered one locus, called the "deleterious region"
    - this simple model will elucidate the role of recombination
- `U/2` -> total rate of mutation to deleterious alleles in the deleterious region per generation per gamete
- input of mutations will be assumed to be poisson distributed
    - poisson distribution describes during a time frame, how likely a value is given an average rate
    - more concretely: if a person receives 4 emails a day on average, it is likely that on some days he or she receives less or more than 4 emails. A poisson distribution will tell you the likelihood that the person receives 3, 5, 10, etc. emails during a period of observation
    - also known as the spread around an average rate of occurrence (http://en.wikipedia.org/wiki/Poisson_distribution)
- back mutation is assumed not to occur
- `i-gametes` -> gametes that carry i deleterious mutations
- `f_i` -> frequency in the population of i-gametes
- **f** -> is a vector of f_i

- in an infinite population, **f** will attain an equilibrium value called "mutation-selection balance"
- the values of **f** at equilibrium will depend on the details of the selection model: strength of selection against deleterious mutations, dominance, interaction between mutations, and mutation rates. 

## The coalescent process and gene genealogies
- `t` -> time measured in generations
- `2*mu*t` -> expected nucleotide diversity due to neutral variation