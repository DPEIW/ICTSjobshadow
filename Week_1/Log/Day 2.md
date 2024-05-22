#ICTS #may2024 
8 - 5 - 2024

**10:30 to 11:15**

In the bus learned about normal distributions and probability contours. Probability contours are ellipses that show the distribution of a two-dimensional probability density function.

A chi-squared test, or Khi2 test, is a statistical hypothesis test that compares the observed distribution of data to an expected distribution.

**11:30**
Supercomputer at ICTS 

"sonic"
https://it.icts.res.in/
14 nodes
HPC - high performance computing
	has to communicate data through the nodes
HTC - high throughput computing
	does not need to communicate data through different nodes

AMD Epyc 7413 
2 socket per node
24 cores per socket = 48 cores per node, 96 threads in total
256 gb ram on signing nodes
384 gb on the computing nodes
running centos

Recently acquired 2x
Nvidia A40 gpu with 48gb vram

data analysis
	uses gpu and the HTCs


**12:00 to 1:00**

Group meeting/discussion on interesting paper found on Arxiv
[Members of Astrophysics Relativity Group at ICTS](https://www.icts.res.in/research/astrorel/members) 

- [Alorika Kar] talked about "Quick recipes for gravitational-wave selection effects
	- https://arxiv.org/abs/2404.16930
	- https://arxiv.org/pdf/2404.16930

- [Ankur Barsode] talked about "Lens Stochastic Diffraction: A signature of compact structures in gravitational wave data"
	- https://arxiv.org/pdf/2404.17405
		- if you have single lens - 2 images
		- you can have multiple lenses but the fainter images are all going to overlap on each other and you are going to get a stochastic signal and it will come from the same location as the main image. 
		- multiple images from multiple lenses all overlapping with each other
		- Questions
			- How many lenses
				- probably 10 - 15 is what he is using 
			- There should be a threshold 
				- didnt go that much into the details
			- why is it important
				- you can use non detection to constrain blackholes??
- [Prasad R] talked about "Dynamical ejecta from binary neutron star mergers: Impact of residual eccentricity and equation of state implementation"
	- https://arxiv.org/pdf/2404.18674
		- ejected mass is whatever is remaining after neutron stars merge 
		- ejecta is ejected more if neutron star is spinning more
		- Concerned about
			- accuracy of simulation
			- internal reactions
				- keeping everything fixed and see how it reacts
- [Prasad R] also talked about "Black hole-neutron star mergers with massive neutron stars in numerical relativity"
	- https://arxiv.org/pdf/2404.18714
- [Krishnendu N V] talked about "Numerical parameterization of stationary axisymmetric black holes in a theory agnostic framework"
	- https://arxiv.org/pdf/2404.17055
- [Vaishak P] "NOTES ON THE PRACTICAL APPLICATION OF NESTED SAMPLING: MULTINEST, (NON)CONVERGENCE, AND RECTIFICATION"
	- https://arxiv.org/pdf/2404.16928
- [Koustav Narayan Maity] "Neutron stars and the cosmological constant problem"
	- https://arxiv.org/pdf/2404.19012

Mainly the PHD fellows were the ones discussing and asking questions and answering each other's doubts on each of the research papers. 

After lunch, **2:00**

worked on python notebook, extracting original parameters from noise of a damped sinusoid wave. 

refer "Day 2_assgt.ipynb for more info"

**EOS**
- should consider installing and learning docker, so i can use vsc and develop inside a linux environment 
- vaishak likes using powerful computer resources to find solutions to problems that need answering, not like google and microsoft who use supercomputers to give users better ads
- 