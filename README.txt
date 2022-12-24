-------------------------------------------------------------------------------
                Ravnursson Faroese Speech Models for PockeSphinx
-------------------------------------------------------------------------------

Author: Carlos Daniel Hernández Mena

Date: October 2022

Place: Language and Voice Lab (LVL), University of Reykjavik, Iceland.

Head of Laboratory: Jón Guðnason

Recommended use : automatic speech recognition

-------------------------------------------------------------------------------
Description:
-------------------------------------------------------------------------------

The "Ravnursson Faroese Speech Models for PockeSphinx" is a set of different 
types of models intended to perform Automatic Speech Recognition in Faroese 
using the PyPi version of PocketSphinx https://pypi.org/project/pocketsphinx/

The models included in the set are: an acoustic model for PocketSphinx, a 
3-gram language model in binary format and a pronouncing dictionary in the 
format of the CMU Pronouncing Dictionary, available at 
http://www.speech.cs.cmu.edu/cgi-bin/cmudict

-------------------------------------------------------------------------------
Models
-------------------------------------------------------------------------------

- Acoustic Models

The acoustic models were created using the desktop version of SphinxTrain
for Linux (https://cmusphinx.github.io/wiki/download/). The training data
was taken from the the corpus "Ravnursson Faroese Speech and Transcripts", 
which is available at Clarin.is (http://hdl.handle.net/20.500.12537/276). Only 
the training portion of the corpus was used to create the models (100 hours).

- Language Model

This 3-gram language model in binary format was created using the SRI 
Language Modeling Toolkit (SRILM) http://www.speech.sri.com/projects/srilm/
with the text in Faroese provided in the "Basic Language Resource Kit" 
(BLARK 1.0) for Faroese (https://maltokni.fo/en/resources) developed by the 
Ravnur Project in 2022.

- Pronunciation Model

The pronunciation dictionary contains more than 28000 pronunciations and it 
was based on the pronounciations provided at the BLARK 1.0.

--------------------------------------------------------------------------------
Citation
--------------------------------------------------------------------------------

When publishing results based on these models please refer to:

   Mena, Carlos. "Ravnursson Faroese Speech Models for PockeSphinx". Web 
   Download. Reykjavik University: Language and Voice Lab, 2022.

Contact: Carlos Mena (carlos.mena@ciempiess.org), Jon Gudnason (jg@ru.is)

License: GNU General Public License v3.

--------------------------------------------------------------------------------
Acknowledgements
--------------------------------------------------------------------------------

This project was funded by the Language Technology Programme for Icelandic 
2019-2023. The programme, which is managed and coordinated by Almannarómur, 
is funded by the Icelandic Ministry of Education, Science and Culture.

Special thanks to Annika Simonsen and to The Project Ravnur for make their
BLARK 1.0 publicly available.

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

