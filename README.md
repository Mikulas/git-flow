### `git find <method fqn>`

Splits `<method fqn>` to namespace, class and function name. Tries to find a file defining this namespace and class and then finally calls git log on the function.

### `git afix`

For every staged file, commit which last changed the file is found. Consolidating all files with same base commit, fixups commits are created.

### `git blist [-v]`

Pretty `git branch` view with `pr/` and `base/` support. Flag `-v` shows pull request.
