# subtreetest-main

Just ignore this. This is me testing.


## Add sub tree

```bash
git remote add sub git@github.com:bep/subtreetest-sub.git
git subtree add --prefix=sub/ sub master --squash
```

## Pull and squash changes from sub

git subtree pull --prefix=sub/ sub master --squash


## Push changes to sub

git subtree push --prefix=sub/ sub master
git subtree push --prefix=sub/ sub-local dev


## Notes

* https://www.atlassian.com/blog/git/alternatives-to-git-submodule-git-subtree