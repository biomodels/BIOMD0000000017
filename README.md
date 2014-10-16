# BIOMD0000000017: Hoefnagel2002_PyruvateBranches

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000017.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000017.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000017 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
** Metabolic engineering of lactic acid bacteria, the combined approach: kinetic modelling, metabolic control and experimental analysis. **   
Hoefnagel MH, Starrenburg MJ, Martens DE, Hugenholtz J, Kleerebezem M, Van
Swam II, Bongers R, Westerhoff HV, Snoep JL _Microbiology_2002 Apr;
148(4):1003-13 [11932446](http://www.ncbi.nlm.nih.gov/pubmed/11932446),  
**Abstract:**   
Everyone who has ever tried to radically change metabolic fluxes knows that it
is often harder to determine which enzymes have to be modified than it is to
actually implement these changes. In the more traditional genetic engineering
approaches ’bottle-necks’ are pinpointed using qualitative, intuitive
approaches, but the alleviation of suspected ’rate-limiting’ steps has not
often been successful. Here the authors demonstrate that a model of pyruvate
distribution in Lactococcus lactis based on enzyme kinetics in combination
with metabolic control analysis clearly indicates the key control points in
the flux to acetoin and diacetyl, important flavour compounds. The model
presented here (available at http://jjj.biochem.sun.ac.za/wcfs.html) showed
that the enzymes with the greatest effect on this flux resided outside the
acetolactate synthase branch itself. Experiments confirmed the predictions of
the model, i.e. knocking out lactate dehydrogenase and overexpressing NADH
oxidase increased the flux through the acetolactate synthase branch from 0 to
75% of measured product formation rates.

The paper does not have any figure to be put as a curation figure in the
BioModels database. The model does reproduce the fluxes and control-
coefficients given in Figure 2 and Table 4. To reproduce the results, the
model was changed from the description in the article according to the model
on JWS: the parameter Kmpyr was changed to 2.5 from 25. The equillibrium
constant for PTA reaction (R4) was changed from 0.0281 to 0.0065. The Km for
oxygen in the NOX reaction (R13) was changed from 0.01 to 0.2. Slight
deviations between the values in the article and the model results may stem
from different algorithms used for finding the steady state.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2010 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


