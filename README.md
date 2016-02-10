# Color-diff
Script to highlight diff in version control system

### Installation
1. `git clone git@github.com:vengatlnx/color-diff.git`
2. `cd color-diff`
3. `chmod 0755 ./color-diff`

Add to your `.bashrc` or `zshrc`:

`$ echo 'export PATH=$HOME/color-diff:$PATH' >> ~/.bashrc`

### Usage:
```
   $ svn diff | color-diff
   $ git diff | color-diff
```

### TODO:
    * Need to highlight change in diff
    * Need to add support for `diff` command

### LICENSE:
    [MIT Licence](https://github.com/vengatlnx/color-diff/blob/master/LICENSE)