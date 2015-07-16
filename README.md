# jqplot-bar-highlighter-plugin

This repo contains few fixes to jqplot bar chart plugins: 

1. jqplot.barRenderer.js - bar chart does not pick up the correct highlightColors options. Fix adapted: http://stackoverflow.com/questions/7980475/jqplot-highlights-per-bar. Replace pidx with sidx at following line:

var opts = {fillStyle: s.highlightColors[pidx]};

2. jqplot.highlighter.js - contains the fixes for "The highlighter point and tooltips is always on the middle of a set of bars when using multiple bar series"

Fix adapted: https://bitbucket.org/cleonello/jqplot/issues/514/the-highlighter-point-is-always-on-the

