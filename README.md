SKOSjs instance for Fusepool P3, working against Virtuoso
=======
This 'fusepool-virtuoso' branch contains specifics for [the SKOSjs instance](http://fusepool.openlinksw.com/DAV/SKOSjs/index.html) used for the [Fusepool P3 project](http://www.fusepool.eu/p3), against [our Virtuoso instance](http://fusepool.openlinksw.com/). The Select and Update endpoints are already set, as well as the username. For the password, ping me at mjovanovik@openlinksw.com.

The changes to SKOSjs have been made as part of the [Fusepool P3 FP7 EU project](http://www.fusepool.eu/p3).

The original SKOSjs specifics are shown below.

PROJECT
=======
SKOSjs is a javascript based editor for Simple Knowledge Organisation System (SKOS) data. It can be used with any SPARQL 1.1 endpoint. It is developed within the
ConnectMe Project (http://connectme.sti2.org/).

CONTACT
=======
Thomas Kurz
Salzburg Research Forschungsgesellschaft
Salzburg, Austria
thomas.kurz@salzburgresearch.at

Online demo
===========
[tkurz.github.com/skosjs](http://tkurz.github.com/skosjs/)

LICENSE
=======
Apache License, Version 2.0 (http://www.apache.org/licenses/LICENSE-2.0.html)

BUILD WEBJAR
============
Use maven to build the webjar. mvn package