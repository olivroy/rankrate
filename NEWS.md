# rankrate 1.1.0

* Removed bugs in estimation of object quality vector, p.
* Removed "LP" estimation option, which is overly complex and has no apparent estimation advantages. We recommend using the "ASTAR" option instead, which provides exact MLE search and is generally faster.
* Allow for identification of multiple MLEs, if ties between objects. When this occurs, estimation functions produce a message.
* Added vignettes.

# rankrate 1.0.0

* First release.
