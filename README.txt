### Universal Dependencies - Danish Dependency Treebank Universal
Dependencies Danish v1.2 -- 2015-11-01

## LICENSE

GNU Public License, version 2

## DESCRIPTION

The Danish UD treebank has been converted from the Danish
Dependency Treebank (Buch-Kromman,2003) into Universal Dependencies
(UD). It consists of 5,512 sentences (100k words). The Danish
source texts and the Danish part-of-speech tags were created by the PAROLE-DK
project (Keson 1998) by the Danish Society for Language and Literature.

In the DDT formalism, determiners head nouns, and auxiliaries head
verbs. In order to promote content words to heads, we have applied a
cascade of graph transformations that make function words (determiners,
auxiliaries, conjunctions, etc) leaves in the dependency tree, instead
of intermediate elements between content heads.

The part-of-speech tags and labels from the original treebank have been
partially converted using mappings, and partially using the new
calculated tree structure as a reference to assign labels.

## BASIC STATISTICS

Tree count:  5512
Word count:  100733
Token count: 100733
Dep. relations: 39 of which 5 language specific
POS tags: 17
Category=value feature pairs: 46

## CHANGELOG

### NOTES FOR THE CURRENT RELEASE (1.2)

From v1.1 to v1.2, many improvements were made and integrated in the
conversion scripts. In particular, we split multiword units, fixed
issues with AUX and DET (some words that are not closed-class items
were labeled as such), changed the headness of infinitive phrases (for
at gøre), and added heuristics to introduce clausal dependency
relations. Further smaller modifications include the change of POS for
"som" and "der" from PART to "PRON", and fixing the lemma of quotes
from HTML-escaping to plain quotes (&quot => "). Release v1.1
contained many "dep" relations for constructions that were not yet
labeled in the first release (e.g. clausal dependents). The current
release reduces the number of "dep" rels significantly, from over 7k
in v1.1 to only 77 remaining cases in v1.2.

### NOTES FOR RELEASE v1.1 (first release for UD_Danish) -- 2015-05-15

This first release contains the original tokenization of DDT, where
multiword units like *i_dag* (today) or *selv_om* (even though) have
been underscored together. These units are made up of more than one
syntactic word and need to be split, with a subsequent reattaching of
the dependency tree, for the treebank to be fully compliant with UD
tokenization.

Relations across clauses are not labeled in this scheme, i.e., the
current conversion does not assign labels like csubj.

## CONTRIBUTORS (in order of last names)

- Anders Johannsen <ajohannsen@hum.ku.dk>
- Héctor Martínez Alonso <alonso@hum.ku.dk>
- Barbara Plank <bplank@cst.dk>

## REFERENCES

* Buch-Kromann, Matthias T., Line Mikkelsen, and Stine Kern Lynge.
  "Danish dependency treebank.". TLT. 2003.

* Keson, Britt (1998). Documentation of The Danish Morpho-syntactically Tagged PAROLE Corpus.
Technical report, DSL

--- Machine readable metadata ---

Documentation status: partial
Data source: semi-automatic
Data available since: UD v1.1
License: GNU GPL 2.0
Genre: news fiction spoken nonfiction
Contributors: Johannsen, Anders; Martínez Alonso, Héctor; Plank, Barbara


