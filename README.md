# subtreetest-main

Just ignore this. This is me testing.


## Add sub tree

```bash
git remote add sub git@github.com:bep/subtreetest-sub.git
git subtree add --prefix=sub/ sub master --squash
```

## Merge sub tree, pull --squash

git subtree pull --prefix=sub/ sub master --squash