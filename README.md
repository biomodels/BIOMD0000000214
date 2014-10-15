# BIOMD0000000214: 

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000214.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000214.git@20140916`


# Model Notes


This model 2 described in the supplement of the article below. It is
parameterized for the WT at 24°C. To reproduce figure 6 the results have to be
rescaled to circadian time by multiplying time by 24/_tau_, with _tau_ being
the period of the free-running oscillator. For the wild-type parameter set
_tau_ is equal to 22.7149.  
Article:  
**Isoform switching facilitates period control in the Neurospora crassa circadian clock.**   
Akman OE, Locke JC, Tang S, Carré I, Millar AJ, Rand DA. _Mol Syst Biol._
2008;4:164. Epub 2008 Feb 12. PMID:
[18277380](http://www.ncbi.nlm.nih.gov/pubmed/18277380),
doi:[10.1038/msb.2008.5](http://dx.doi.org/10.1038/msb.2008.5)  
**Abstract:**   
A striking and defining feature of circadian clocks is the small variation in
period over a physiological range of temperatures. This is referred to as
temperature compensation, although recent work has suggested that the
variation observed is a specific, adaptive control of period. Moreover, given
that many biological rate constants have a Q(10) of around 2, it is remarkable
that such clocks remain rhythmic under significant temperature changes. We
introduce a new mathematical model for the Neurospora crassa circadian network
incorporating experimental work showing that temperature alters the balance of
translation between a short and long form of the FREQUENCY (FRQ) protein. This
is used to discuss period control and functionality for the Neurospora system.
The model reproduces a broad range of key experimental data on temperature
dependence and rhythmicity, both in wild-type and mutant strains. We present a
simple mechanism utilising the presence of the FRQ isoforms (isoform
switching) by which period control could have evolved, and argue that this
regulatory structure may also increase the temperature range where the clock
is robustly rhythmic.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2009 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use [ Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


