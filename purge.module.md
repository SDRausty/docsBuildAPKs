Delete Module from Git Repository:

Delete the relevant line from the .gitmodules file.
Delete the relevant section from .git/config.
Run `git rm --cached path/to/module` (no trailing slash).
Commit `git commit` and remove the now untracked module.

Reference https://gist.github.com/kyleturner/1563153
