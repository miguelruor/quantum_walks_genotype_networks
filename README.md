# Quantum walks over genotype networks

## Abstract
In this paper, we expand the quantum genetic evolution model introduced by [Santiago-Alarcon et al. (2020)](https://royalsocietypublishing.org/doi/full/10.1098/rsif.2020.0567) based on 
continuous-time quantum walks over genotype spaces, graphs with nodes representing genotypes and edges representing a single step mutation. We simulate interactions of genotypes with 
their environment (including chemicals or another agents) through measurements of the quantum walk at random times given by a Poisson Process 
[(Varbanov et al. (2008))](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.78.022324), that collapse the wave function of the genetic quantum system. Using this measurement 
process, we defined the mean hitting time of the quantum walk to novel phenotypes in genotype space.

The new mathematical definition of the hitting time of a continuous-time quantum walk to a given marked set of states is different of the definition proposed by Varbanov et al. (2008). 
Furthermore, a new formula for the mean hitting time was developed using Wald's theorem and noticing that the stochastic process given by the results of the measurements of the quantum 
walk is a discrete Markov chain (resulting in an *embedded Markov chain* in the quantum walk), whose transition matrix is also showed in this thesis. 

We ran simulations of a continuous-time classical walk and a continuous-time quantum walk over three genotype spaces with around 20000 genotypes whose phenotype is their ability of 
binding transcription factors. These genotype spaces correspond to three biological model species: *Arabidopsis thaliana*, *Mus musculus*, and *Neurospora Crassa*. We simulated our quantum 
walk-based model in a high performance computer (HPC) platform to deal with the inherent computational cost of digital simulations of quantum phenomena. In order to do so, we successfully 
applied for an IBM Cloud Award, which has given us access to the advanced HPC platform available to run the simulations in parallel of the quantum walk long enough to let quantum walk explore 
the genotype space and discover all phenotypes we considerate in our data. We found that quantum hitting times are 1.5-x shorter than classical hitting times to new phenotypes. Our results 
demostrate that continuous-time quantum walks are the appropriate tool to explore genetic genotype networks, showing that our approach improves the discovery of evolutionary innovations 
compared to continuous-time classical walks.
