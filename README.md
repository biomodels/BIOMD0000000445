# BIOMD0000000445: MODEL1209110002

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000445.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000445.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000445 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Pokhilko2013 - TOC1 signalling in Arabidopsis circadian clock

In this model, Pokhilko _et al._ has incorporated the negative transcriptional
regulations of the core clock genes by TOC1 and the up-regulation of TOC1
expression by ABA signalling, to their previous model
[BIOMD0000000412](http://identifiers.org/biomodels.db/BIOMD0000000412)

This model is described in the article:

[Modelling the widespread effects of TOC1 signalling on the plant circadian
clock and its outputs.](http://identifiers.org/pubmed/23506153)

Pokhilko A, Mas P, Millar AJ.

BMC Syst Biol 2013; 7: 23

Abstract:

BACKGROUND: 24-hour biological clocks are intimately connected to the cellular
signalling network, which complicates the analysis of clock mechanisms. The
transcriptional regulator TOC1 (TIMING OF CAB EXPRESSION 1) is a founding
component of the gene circuit in the plant circadian clock. Recent results
show that TOC1 suppresses transcription of multiple target genes within the
clock circuit, far beyond its previously-described regulation of the morning
transcription factors LHY (LATE ELONGATED HYPOCOTYL) and CCA1 (CIRCADIAN CLOCK
ASSOCIATED 1). It is unclear how this pervasive effect of TOC1 affects the
dynamics of the clock and its outputs. TOC1 also appears to function in a
nested feedback loop that includes signalling by the plant hormone Abscisic
Acid (ABA), which is upregulated by abiotic stresses, such as drought. ABA
treatments both alter TOC1 levels and affect the clock's timing behaviour.
Conversely, the clock rhythmically modulates physiological processes induced
by ABA, such as the closing of stomata in the leaf epidermis. In order to
understand the dynamics of the clock and its outputs under changing
environmental conditions, the reciprocal interactions between the clock and
other signalling pathways must be integrated. RESULTS: We extended the
mathematical model of the plant clock gene circuit by incorporating the
repression of multiple clock genes by TOC1, observed experimentally. The
revised model more accurately matches the data on the clock's molecular
profiles and timing behaviour, explaining the clock's responses in TOC1 over-
expression and toc1 mutant plants. A simplified representation of ABA
signalling allowed us to investigate the interactions of ABA and circadian
pathways. Increased ABA levels lengthen the free-running period of the clock,
consistent with the experimental data. Adding stomatal closure to the model,
as a key ABA- and clock-regulated downstream process allowed to describe TOC1
effects on the rhythmic gating of stomatal closure. CONCLUSIONS: The
integrated model of the circadian clock circuit and ABA-regulated
environmental sensing allowed us to explain multiple experimental observations
on the timing and stomatal responses to genetic and environmental
perturbations. These results crystallise a new role of TOC1 as an
environmental sensor, which both affects the pace of the central oscillator
and modulates the kinetics of downstream processes.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000445](http://identifiers.org/biomodels.db/BIOMD0000000445).

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024).

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


