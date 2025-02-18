```
repo init -g my -c master --config-name https://github.com/puzzzzzzle/StudyRepos
repo forall -c git checkout master
repo forall -c git submodule update --init
```