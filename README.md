# sir-gawain-and-the-green-knight

Text, translation, and annotation of Sir Gawain and the Green Knight

`raw/pg.txt` contains the Project Gutenberg text of Richard Morris’s 1869 edition.

`raw/brunetti.txt` contains a text and line-by-line glossary from Brunetti’s website.

`txt/base.tsv` contains a more machine-actionable columnar version I extracted from the above. The columns are:

- line number
- folio number
- side note reference
- fitt number
- stanza number
- line type (`b` = bob; `w` = wheel)
- text of line

`txt/stanza_notes.tsv` contains the sidenotes and footnotes from Morris. The columns are:

- fitt number
- stanza number
- note reference
- note text

`txt/kirtlan.txt` contains Ernest Kirtlan’s _Sir Gawain and the Green Knight: Rendered Literally Into Modern English_

`txt/brunetti.tsv` contains just the text on Brunetti’s site.

`txt/brunetti_gloss.tsv` contains a cleaned up version of Brunetti’s glosses.
