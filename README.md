# MODEL1006230071: Bertram2004_PancreaticBetaCell_modelA

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230071.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230071.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230071 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Calcium and glycolysis mediate multiple bursting modes in pancreatic islets.**   
Bertram R, Satin L, Zhang M, Smolen P, Sherman A. _Biophys J_ 2004
Nov;87(5):3074-87 [15347584](http://www.ncbi.nlm.nih.gov/pubmed/15347584) ,  
**Abstract:**   
Pancreatic islets of Langerhans produce bursts of electrical activity when
exposed to stimulatory glucose levels. These bursts often have a regular
repeating pattern, with a period of 10-60 s. In some cases, however, the
bursts are episodic, clustered into bursts of bursts, which we call compound
bursting. Consistent with this are recordings of free Ca2+ concentration,
oxygen consumption, mitochondrial membrane potential, and intraislet glucose
levels that exhibit very slow oscillations, with faster oscillations
superimposed. We describe a new mathematical model of the pancreatic beta-cell
that can account for these multimodal patterns. The model includes the
feedback of cytosolic Ca2+ onto ion channels that can account for bursting,
and a metabolic subsystem that is capable of producing slow oscillations
driven by oscillations in glycolysis. This slow rhythm is responsible for the
slow mode of compound bursting in the model. We also show that it is possible
for glycolytic oscillations alone to drive a very slow form of bursting, which
we call "glycolytic bursting." Finally, the model predicts that there is
bistability between stationary and oscillatory glycolysis for a range of
parameter values. We provide experimental support for this model prediction.
Overall, the model can account for a diversity of islet behaviors described in
the literature over the past 20 years.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Bertram R, Satin L, Zhang M, Smolen P, Sherman A.
(2004) - version=1.0**
](http://models.cellml.org/exposure/f7d6dbef9db48b6d62bf43598ebfb2d5)  
The original CellML model was created by:  
**Catherine Lloyd**   
c.lloyd@auckland.ac.nz  
The University of Auckland  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


