If you're like me you have a dir like ~/Workspace/Github where all your git repos live. I often find myself making a change in a repo, getting side tracked and ending up in another repo, or off doing something else all together. After a while I end up with several repos with modifications. This script helps me pick up where I left off by checking the status of all my repos, instead of having to check each one individually.

Usage:

```bash
git-status [directory]
```

This will run `git status` on each repo under the directory specified. If called with no directory provided it will default to the current directory.