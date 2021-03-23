# git-for-ds

A short `git` tutorial for Data Scientists

## Requirements

* Conda
* Set up the `ml_in_prod` conda environment explained [here](https://mlinproduction.github.io/env_setup/)
* Set up a Jupyter kernel linked to this environment: `ipython kernel install --user --name=ml_in_prod`

## Contents

* [Git concept recap](./Concept_recap.ipynb): A quick, graphical recap of basic git concepts

* [Chapter I](./Chapter_I.ipynb):
   - How to create a git repository (init, status)
   - The four main stages of a file in a repository: untracked, tracked, staged and committed (ignore, add, commit, rm)

* [Chapter II](./Chapter_II.ipynb): 
   - How to track changes of a file in a repository (log, show, diff)
   - How to maintain different versions of a file without going crazy (branch, checkout)
   - Time-travel with git (revert, checkout, reset)

* [Chapter III](./Chapter_III.ipynb):
   - How to work with friends on the same file... and remain friends (merge)
   - Working with remote repositories (clone, fetch, pull, push, pull requests)
   - Contributing flows (forks, feature branches)
