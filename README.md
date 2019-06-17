# Spanish Unannotated Corpora (Updating to include more corpora)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3066517.svg)](https://doi.org/10.5281/zenodo.3066517)

This repository gathers a compilation of corpus in Spanish language.
Available to download here: [Zenodo](https://zenodo.org/record/3066517/files/preprocessed.zip?download)

## Data

*Number of lines*: 277550238 (278M)

*Number of tokens*: 2588948314 (2.6B)

*Number of chars*: 15836352897 (15.8B)

## Sources

*Spanish Wikis*: Wich include Wikipedia, Wikinews, Wikiquotes and more. These were first processed with wikiextractor (https://github.com/josecannete/wikiextractorforBERT) using the wikis dump of 20/04/2019.

*ParaCrawl*: Spanish portion of ParaCrawl (http://opus.nlpl.eu/ParaCrawl.php)

*EUBookshop*: Spanish portion of EUBookshop (http://opus.nlpl.eu/EUbookshop.php)

*MultiUN*: Spanish portion of MultiUN (http://opus.nlpl.eu/MultiUN.php)

*OpenSubtitles*: Spanish portion of OpenSubtitles2018 (http://opus.nlpl.eu/OpenSubtitles-v2018.php)

*DGC*: Spanish portion of DGT (http://opus.nlpl.eu/DGT.php)

*DOGC*: Spanish portion of DOGC (http://opus.nlpl.eu/DOGC.php)

*ECB*: Spanish portion of ECB (http://opus.nlpl.eu/ECB.php)

*EMEA*: Spanish portion of EMEA (http://opus.nlpl.eu/EMEA.php)

*Europarl*: Spanish portion of Europarl (http://opus.nlpl.eu/Europarl.php)

*GlobalVoices*: Spanish portion of GlobalVoices (http://opus.nlpl.eu/GlobalVoices.php)

*JRC*: Spanish portion of JRC (http://opus.nlpl.eu/JRC-Acquis.php)

*News-Commentary11*: Spanish portion of NCv11 (http://opus.nlpl.eu/News-Commentary-v11.php)

*TED*: Spanish portion of TED (http://opus.nlpl.eu/TED2013.php)

*UN*: Spanish portion of UN (http://opus.nlpl.eu/UN.php)

## Post-processing

Two post-processing scripts included (corpus_processing.py and split_punctuation.py). The available data was processed just with the first one.

Using process_corpus.py:
- Lowercase
- Removed urls
- Removed listing
- Replaced multiple spaces with single one
