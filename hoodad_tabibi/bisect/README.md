`git bisect` helps you find the commit that introduced a bug by using binary search.<br>
Run `git bisect --help` for Docs

### Start
```
git bisect start
```
This will move you to a commit
If the current commit is bad you should type `git bisect bad`<br>
If you are happy with the current commit you type `git bisect good`<br>
Continue this process until you find the commit that introduced the bug.

### Return to HEAD
`git bisect reset`
