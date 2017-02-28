# BMIP 2017 practical

Download the preprocessed PubMed abstracts for the practical in CoNLL format here:

* [pubmed-abstracts.conll.gz](http://130.237.129.23/static/pubmed-abstracts.conll.gz) (971M package)

For reference (i.e. you do not need to redo any of the following), this data was created as follows:

* Download a selection of abstracts relevant to the comorbidity topic from [PubMed](http://pubmed.com) in XML format
* Extract title and abstract texts using the tool available from <https://github.com/spyysalo/pubmed>
* Sentence-split and tokenize using simple heuristics
* Add lemma, part of speech and chunk using [GENIA Tagger](http://www.nactem.ac.uk/GENIA/tagger/)
* Add Soundex using the [Fuzzy](https://pypi.python.org/pypi/Fuzzy) implementation

If you have any questions or comments relating to this data or the text mining practical, please write Sampo (smp66) and Nigel (nhc30).
