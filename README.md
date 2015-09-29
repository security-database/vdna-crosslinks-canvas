vDNA Crosslinks Canvas Work In Progress
====================

Work-in progress conversion of [Security-Database vDNA Crosslinks SVG](https://github.com/security-database/vdna-crosslinks) for performence issue with SVG.

Actually, speed problem with Canvas on lot's of nodes.

Original code have been simplified for test only with 2100 nodes.

[Grapher library](https://github.com/ayasdi/grapher) to convert Canvas into WebGL -> *Really Fast*

Actually, **index4.html** is perhaps the most advanded and will be the remplacement of SVG Security-database Crosslinks

Files
---

- index.html exemple is a simple version with d3js force, nodes color and collide
- index2.html exemple is a version with d3js force, waiting spin, pre calculation of the force, nodes color, collide, node hover with neighboring Repaint, Tooltips and windows resize
- index3.html exemple is a simple version with d3js force, nodes color, collide, zoom in/out, drag and [Grapher library](https://github.com/ayasdi/grapher) -> Really Fast
- **index4.html** exemple is a **complex version** with d3js force, nodes color, selector by severities - vendors - exploits, collide, node hover with neighboring Repaint, Tooltips, zoom in/out, pan and [Grapher library](https://github.com/ayasdi/grapher) -> *Again, Really Fast*

Todo
----

- On **index4.html** handle better wheel zoom only inside the graph and not scroll the page

Security-Database vDNA Crosslinks
-------------------

vDNA Crosslinks allows you to gather +80.000 security alerts data from [Security-Database](https://www.security-database.com) and export it as JSON. Export provide related alert information. By that we mean, all alerts linked to the first one at specified depth. We limit the depth from 0 (single) to 4, but on demand, we can override this value.

On this 'simple' exemple, we use D3.js Canvas library to manipulate and represent links bewteen alerts and severity propagation. Hope you'll like it.

[Security-Database](https://www.security-database.com) provides this information for free for anybody who want to play with, make graphs, stats, publish or anything else. Hope you'll enjoy playing with it and perhaps, let you have some idea ;)

License
-------

License is Apache Version 2.0