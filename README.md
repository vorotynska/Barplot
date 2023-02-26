# Barplot

Percent stacked barplot.

The d3.stack() function is used to stack the data: it computes the new position of each subgroup on the Y axis.

 This document describes how to build a stacked barplot with tooltip with d3.js
 Here, the tricky part is to recover the subgroup name to show it in the tooltip. The trick is to use d3.select(this.parentNode).datum().key