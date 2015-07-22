vDNA Crosslinks Canvas Work In Progress
=======================================

Work-in progress conversion of [Security-Database vDNA Crosslinks SVG](https://github.com/security-database/vdna-crosslinks) for performence issue with SVG.

Actually, speed problem with Canvas on lot's of nodes.

Original code have been simplified for test only with 2100 nodes.


Files
-----

- index.html exemple is a simple version with d3js force, nodes color and collide
- index2.html exemple is a version with d3js force, nodes color, collide, node hover with neighboring Repaint, Tooltips and windows resize


Security-Database vDNA Crosslinks
---------------------------------

vDNA Crosslinks allows you to gather +80.000 security alerts data from [Security-Database](https://www.security-database.com) and export it as JSON. Export provide related alert information. By that we mean, all alerts linked to the first one at specified depth. We limit the depth from 0 (single) to 4, but on demand, we can override this value.

On this 'simple' exemple, we use D3.js library and CoffeeScript to manipulate and represent links bewteen alerts and severity propagation. Hope you'll like it.

[Security-Database](https://www.security-database.com) provides this information for free for anybody who want to play with, make graphs, stats, publish or anything else. Hope you'll enjoy playing with it and perhaps, let you have some idea ;)


License
-------

License is Apache Version 2.0