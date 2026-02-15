`git bisect` helps you find the commit that introduced a bug by using binary search.
`git bisect --help` for Docs

### Start
```
git bisect start
```
If the current commit is bad you should type `git bisect bad`
If you are happy with current commit you type `git bisect good`
Continue this process to find the commit that introduce this bug

### Return to HEAD
`git bisect reset`
