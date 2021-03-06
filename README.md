# Tidy Git Clone
Tidy Git Clone (TGC) is a tool to clone git repos to a consistent directory (based on golangs directory scheme).

By default TGC clones into $HOME/git and then organizes repos by host and subpath.  For example, the git repo `https://examplegithost.com/somedomain/somerepo.git` would be cloned into the folder `$HOME/git/src/examplegithost.com/somedomain/somerepo`.

This can be overwritten by specifiying a TIDY_GIT_HOME directory.


# Installation
```
git clone https://github.com/njenan/tidy-git-clone.git
cd tidy-git-clone
make install
```


# Usage
```
tidy-git-clone example/repo/path.git
```


# License
Tidy Git Clone is licensed under the terms of GPL-2.0

See [LICENSE](./LICENSE) for details.

