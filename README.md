# EEOB 590B-TH Macroevolution & Lineage Diversification 
### A spring 2016 graduate seminar led by [Tracy Heath](http://phyloworks.org/) at Iowa State University on phylogenetic methods for understanding rates of diversification

## When and Where?
### Fridays 3:10 – 5:00 PM in 145 Bessey

## Seminar Description

This seminar course will focus on methods for understanding patterns of biodiversity in the Tree of Life. We will review current phylogenetic approaches for estimating rates of speciation and extinction through some lectures, studying recent papers applying these methods, and mini workshops.

##### Phylogenetic methods for diversification include:
* topological tests of variable rates of diversification
* speciation-extinction models
* methods for detecting shifts in diversification over time
* lineages through time plots
* state-dependent diversification
* understanding the diversification of rapidly evolving infectious diseases

## Software Needed
This seminar will involve some hands-on use of phylogenetic methods for diversification. Please download and install the following programs:

* A good text editor (e.g., TextWrangler, Sublime Text, Notepad++)
* BEAST 2: [http://beast2.org](http://beast2.org/)
* Tracer: [http://tree.bio.ed.ac.uk/software/tracer/](http://tree.bio.ed.ac.uk/software/tracer/)
* FigTree: [http://tree.bio.ed.ac.uk/software/figtree/](http://tree.bio.ed.ac.uk/software/figtree/)
* R: [https://cran.r-project.org/](https://cran.r-project.org/)
* R Phylogenetics Packages: Install the [Phylogenetics Task View](https://cran.r-project.org/web/views/Phylogenetics.html) to get most of the packages for comparative phylogenetics (this can take a while and may have some issues depending on version of R or operating system):

```
install.packages("ctv")
library("ctv")
install.views("Phylogenetics")
```
*If you have problems installing the phylogenetics task view, we can troubleshoot these in the first couple meetings.

Other helpful tools:

* RStudio: [https://www.rstudio.com/](https://www.rstudio.com/)

## Seminar Schedule

Week    |  Calendar Date        | Topic        | Description 
--------|---------------|--------------|-------------
~~00~~ | ~~Jan 12~~ | Organizational | Welcome, software needed, discussion of expectations. <span style="color:red">**_This meeting will be held on Tuesday, Jan 12 at 2:10 PM in 255 Bessey_**</span>
~~01~~ | ~~Jan 22~~ | Introduction to phylogenetic methods for diversification | Background on phylogenetic methods and macroevolutionary analysis of diversification. Plus software installation troubleshooting and a mini R tutorial. [Week01](https://github.com/phyloworks/macrodiv-seminar/tree/master/Week01)
~~02~~ | ~~Jan 29~~ | Divergence-time estimation | Bayesian methods for estimating time-calibrated phylogenies and why they are important for understanding diversification [Week02](https://github.com/phyloworks/macrodiv-seminar/tree/master/Week02)
~~03~~ | ~~Feb 5~~ | Bayesian divergence-time estimation in BEAST2 | Hands-on tutorial on estimating time-calibrated phylogenies using the program [BEAST2](http://beast2.org/). Bring your laptop. [Week03](https://github.com/phyloworks/macrodiv-seminar/tree/master/Week03)
04 | Feb 12 | Birth-death processes | Stochastic branching processes, their assumptions, and how these models are used to understand lineage diversification. [Week04](https://github.com/phyloworks/macrodiv-seminar/tree/master/Week04)
05 | Feb 19 | Paper & Methods | Discuss the applications and approaches of [Jetz et al. 2012 The global diversity of birds in space and time. *Nature*](http://www.nature.com/nature/journal/v491/n7424/full/nature11631.html).
06 | Feb 26 | Paper & Methods |Erica & Jermaine
07 | Mar 4 | Paper & Methods | Bryan & Nick
08 | Mar 11 | Paper & Methods | Dr. [April Wright](http://wrightaprilm.github.io/pages/about_me.html) will lead the discussion on her paper: [Wright et al. 2015. Which came first: The lizard or the egg? Robustness in phylogenetic reconstruction of ancestral states. *Journal of Experimental Zoology*](http://onlinelibrary.wiley.com/doi/10.1002/jez.b.22642/full) 
-- | Mar 18 | Spring Break | Whooo!
09 | Mar 25 | Paper & Methods | Hylia & Kelly
10 | Apr 1 | Open Lab | April Wright will lead an open-lab where you can apply methods to your own data. Or April can lead a discussion/class of her choosing.
11 | Apr 15 | Paper & Methods | Cameron & Jessica
12 | Apr 22 | State-dependent diversification with Emma Goldberg | Dr. [Emma Goldberg](http://eeg.github.io/lab/home.html) will be visiting the EEOB department from U. Minnesota. She will be giving the [EEOB Seminar on April 21](http://www.eeob.iastate.edu/dr-emma-goldberg-seminar-speaker). We will discuss state-dependent diversification methods in detail with Emma.
13 | Apr 29 | Future Directions | Discuss the current state of the field and future research needed to help researchers answer questions about lineage diversification.

## Some Suggested Papers for Discussion

#### Macroevolution of Species

* "[Molecular phylogenetics and the diversification of hummingbirds](http://www.sciencedirect.com/science/article/pii/S0960982214002759)". McGuire et al. *Current Biology*, 2014.
* "[Faster speciation and reduced extinction in the tropics contribute to the mammalian latitudinal diversity gradient](http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1001775)". Rolland et al. *PLoS Biology, 2014.
* "[Phylogeny and tempo of diversification in the superradiation of spiny-rayed fishes](http://www.pnas.org/content/110/31/12738.short)". Near et al. *PNAS*, 2013.
* "[Ecological and evolutionary determinants for the adaptive radiation of the Madagascan vangas](http://www.pnas.org/content/109/17/6620.short)". Jønsson et al. *PNAS*, 2012.
* "[Testing the museum versus cradle tropical biological diversity hypothesis: phylogeny, diversification, and ancestral biogeographic range evolution of the ants](http://onlinelibrary.wiley.com/doi/10.1111/evo.12105/abstract?)". Moreau & Bell. *Evolution*, 2013.
* "[Fossils, phylogenies, and the challenge of preserving evolutionary history in the face of anthropogenic extinctions](http://www.pnas.org/content/112/16/4909.short)" Huang et al., *PNAS*, 2015.
* "[Accurate and precise estimates of origination and extinction rates](http://www.bioone.org/doi/full/10.1666/13036)" Alroy. *Paleobiology*, 2014.
* Some interesting back-and-forth:
	* "[Extinction rates can be estimated from molecular phylogenies](http://rstb.royalsocietypublishing.org/content/344/1307/77.short)". Nee et al. *Phil. Trans. B*, 1994.
	* "[Extinction rates should not be estimated from molecular phylogenies](http://onlinelibrary.wiley.com/doi/10.1111/j.1558-5646.2009.00926.x/abstract?)". Rabosky. *Evolution*, 2010.
	* "[Extinction can be estimated from moderately sized molecular phylogenies](http://onlinelibrary.wiley.com/doi/10.1111/evo.12614/abstract?)". Beaulieu & O'Meara. *Evolution*, 2015.
	* "[Challenges in the estimation of extinction from molecular phylogenies: A response to Beaulieu and O'Meara](http://onlinelibrary.wiley.com/doi/10.1111/evo.12820/abstract?)". Rabosky. *Evolution*, 2015.

#### Evolutionary Dynamics of Infectious Disease

* "[Birth–death skyline plot reveals temporal changes of epidemic spread in HIV and hepatitis C virus (HCV)](http://www.pnas.org/content/110/1/228.short)". Stadler et al. *PNAS*, 2013.
* "[Insights into the Early Epidemic Spread of Ebola in Sierra Leone Provided by Viral Sequence Data](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4205153/)". Stadler et al. *PLoS Currents: Outbreaks*, 2014.


## Expectations of Enrolled Students

The grade for this seminar course will be based entirely on participation. Please come prepared to discuss papers and work on the methods. 

## Key Dates

* February 12: Charles Darwin's Birthday!
* March 14-18: Spring Break
* March 25: Last day to drop.

## Questions?

Please contact [Tracy Heath](http://phyloworks.org/) if you have questions about this seminar.
