beamer-stub
==============

Scratch template For Rweave + Beamer presentations.

To create a new presentation from this template (modified from https://help.github.com/articles/duplicating-a-repository on 15 MAY 2013):

1. create new github repo: new-repo

2. go to appropriate filesystem location on command line (where you want new presentation to live)

3. then:
```
$ git clone --bare https://github.com/pearsonca/beamer-stub.git # Make a bare clone of this repo
$ cd beamer-stub.git
$ git push --mirror https://github.com/pearsonca/new-repo.git # Mirror-push to the new repo
$ cd ..
$ rm -rf beamer-stub.git # Remove temporary local repo
```