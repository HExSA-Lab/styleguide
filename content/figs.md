+++
title = "figures"
+++

Good figures can make or break your paper. The key is that they should
make it easy and quick for the reader to interpret your data. Here are some guidelines that
I find myself repeating to students:

* Learn a plotting package (matplotlib, plotly, gnuplot) early on and stick with it. Script your
plot generation. You will thank me later.
* Show error bars or confidence intervals when possible. Be clear about which one you're using. For example,
explicitly state in your text if you're using 95% confidence intervals.
* Make sure bars/lines/points are distinguishable. Colors are better than nothing, but patterns are
more reliable in bars. Use differnt point styles for scatter/line plots. Use line styles for line plots too (e.g., dashed, dotted, etc.).
* When using colors for anything meaningful, print them out in black and white to make sure they
can be distinguished. Many reviewers (and readers) print papers this way to review. Also
[take into consideration][color] that some of your readers may be colorblind.
* Font sizes in figure text is almost always too small. Try to make it larger in your plotting package, and double-check how it looks in your PDF after typesetting. Assume your reader will get angry if they have to squint
to read your figures. 
* If you're using a log-plot, or a false origin make sure readers know.


[color]: https://matplotlib.org/3.1.0/tutorials/colors/colormaps.html
