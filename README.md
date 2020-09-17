# LibSSH-dataset

This dataset was mined with our mining approach available in the [git-ecco repository](https://github.com/GabrielaMichelon/git-ecco/tree/develop).
It contains for every release of the LibSSH system:

* the classification of the macros; 
* the considered set of features; 
* the Git commits where a feature was present; 
* the number of Git commits that a feature changed, i.e., had new revisions; 
* the number of deleted features per Git commit;
* the configuration for every changed block of code in a Git commit;
* the number of Git commits that a feature was removed; 
* the number of new and changed features per Git commit.