# dygraph-extra
This repository is a cloned of the original [dygraph-extra](http://cavorite.com/labs/js/dygraphs-export/)

taken the modification from [joh024's repository](https://github.com/joh024/dygraph-extra)
The modifications are:

Fixed y label positioning.
Automatic detectection of fonts for the labels, rather than relying on predefined or user-supplied fonts. This still isn't perfect, but should be closer to the actual dygraph.
Fix overflow of legends for too many series (legends now wrap).
A method for registering dygraphs via a drawcallback, primarily useful for those using the R version of dygraphs.
A function for downloading one or more registered dygraphs where the dygraphs to download are identified by their id and where multiple plots are zipped together using JSZip.
Functions to address some bugs/annoyances with dygraphs:
correct automatic resize on visiblity change.
correct clearance of selection on mouseleave.
