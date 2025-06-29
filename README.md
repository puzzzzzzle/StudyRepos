```
repo init -g my -b master -u  https://github.com/puzzzzzzle/StudyRepos
repo forall -c git checkout master
repo forall -c git submodule update --init --recursive
```