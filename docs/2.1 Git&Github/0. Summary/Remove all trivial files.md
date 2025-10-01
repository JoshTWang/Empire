#### Remove all .DS_Store

```sh
find . -name .DS_Store -print0 | xargs -0 git rm -f --ignore-unmatch

git commit -m "Remove .DS_Store from everywhere"

git push origin master
```

#### edit .gitignore

```sh
**/.DS_Store
Icon?
```

