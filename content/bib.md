+++
title = "bibliography"
+++
The BibTeX code you get from the ACM Digital Library or IEEE Xplore or whatever (god forbit CiteCeer) is usually terrible.
You really need to fix it up manually:

* Remove all the useless fields like `publisher`, `keywords`, and `abstract`. For `inproceedings` (conference) entries, I prefer to keep `author`, `title`, `booktitle`, `series`, `month`, `pages`, and `year`. The goal here
is to make it easy for readers to find the reference.
* The key is to be consistent with references. Pick a style and stick with it. I always use something like: `Proceedings of the $3^{rd}$ Workshop on Hot Topics in Operating Systems` for `booktitle` in proceedings. I use the `series` bib key for the abbreivation, and I prefer *SOSP '07* to *SOSP 2007*. Minor, but try to stick with the conference's own numbering system. For example, HotOS prefers Roman numerals, e.g. *HotOS VIII*. 
* If you've got a page limit that includes references: Edit the conference name (`booktitle`) to be less rambly. Remove stuff like *Proceedings of the 32nd ACM SIGPLAN Conference on...* and use something succinct like *Programming Language Design and Implementation (PLDI)*. Include popular abbreviations in parentheses to help readers skim. When submitting to a venue with unjust page limit rules that include references, consider using the abbreviation by itself to save space (and as a form of protest).
* Check for capitalization in the title and surround it with curly braces. For example, use `{PRIMES} is in {P}` to make sure BibTeX doesn’t render it as *Primes is in p*. This is particularly important for system names and acronyms. 
* Many papers have subsequently published journal versions. E.g., on the ACM DL, you might find a citation that includes the bibtex for both a TOCS journal paper and an ISCA paper. Always prefer the original conference paper, unless you're citing something special about the (usually extended) journal content. 

If you find something on arXiv, always look for a real publication first before resorting to an arXiv citation.
