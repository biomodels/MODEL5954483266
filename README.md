# MODEL5954483266: 

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL5954483266.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL5954483266.git@20140916`

## Usage

Importing the model package.

`import MODEL5954483266 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is described in the article:  
**Kinetics of histone gene expression during early development of Xenopus laevis.**   
Koster JG, Destrée OH and Westerhoff HV. _J Theor Biol._ 1988 Nov
21;135(2):139-67. PMID: [3267765](http://www.ncbi.nlm.nih.gov/pubmed/3267765)  
**Abstract:**   
Using literature data for transcriptional and translational rate constants,
gene copy numbers, DNA concentrations, and stability constants, we have
calculated the expected concentrations of histones and histone mRNA during
embryogenesis of Xenopus laevis. The results led us to conclude that: (i) for
X. laevis the gene copy number of the histone genes is too low to ensure the
synthesis of sufficient histones during very early development, inheritance
from the oocyte of either histone protein or histone mRNA (but not necessarily
both) is necessary; (ii) from the known storage of histones in the oocyte and
the rates of histone synthesis determined by Adamson and Woodland (1977),
there would be sufficient histones to structure the newly synthesized DNA up
to gastrulation but not thereafter (these empirical rates of histone synthesis
may be underestimates); (iii) on the other hand, the amount of H3 mRNA
recently observed during early embryogenesis (Koster, 1987, Koster et al.,
1988) could direct a higher and sufficient synthesis of H3 protein, also after
gastrulation. We present a quantitative model that accounts both for the
observed H3 mRNA concentration as a function of time during embryogenesis and
for the synthesis of sufficient histones to structure the DNA throughout early
embryogenesis. The model suggests that X. laevis exhibits a major (i.e. some
14-fold) reduction in transcription of histone genes approximately 11 hours
after fertilization. This reduction could be due to a decrease in the number
of transcribed histone genes, a decreased rate constant of transcription with
continued transcription of all the histone genes, and/or a reduction in the
time during the cell cycle in which histone mRNA synthesis takes place.
Alternatively, the histone mRNA stability might decrease approximately 16-fold
11 hours after fertilization.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2011 The BioModels.net Team.  
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


