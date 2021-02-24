+++
title = "duplicates"
+++

When you write TeX in e.g., vim, there is a notorious tendency
to have duplicate words appear in the final paper because of the word alignment in your
text editor. This usually happens as a result of feverish editing, but manifests itself
as having a word at the end of the line with a duplicate appearing at the beginning
of the next line (in the TeX). Of course they might not be so hidden in the
typeset document, so you might have a very obvious "the the" in your paper. 

If you're using a paper repo I built, you'll see a file called `dups` which
is a Perl script to detect such duplicate words, again stolen from [Matt Might][mm].

[mm]: http://matt.might.net/
