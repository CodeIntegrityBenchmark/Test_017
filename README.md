# Test_017
This project is part of a benchmark / test suite used to check the different git histories created through different development processes. The test suite is meant to be processed by SPHA-Code-Integrity.

## Textual Description
Expected Commits against integrity rules :
* All Commits expect the ones that are done via the PR, i.e. commits merged from feature-2 branch.

## Changes Made In This Repo

* Create a feature branch from main and make a commit on that branch.
* Create a second commit on the main branch.
* Make a commit on the feature branch.
* Merge the feature branch with the main branch without PR.
* Create a feature-2 branch based on the feature-1 branch merged commit and make a commit on the feature-2 branch
* Update the main branch with a commit.
* Update the feature-2 branch with the expected results JSON.
* Now merge the feature-2 branch with the main branch using a PR.
