# Go (aka golang)

## Version manager:

[GVM](https://github.com/moovweb/gvm) is the most widely used package manager. It handles version management very well, but also has some feature bloat in form of an included package manager.

There also is [Solistras bugfix branch](https://github.com/Solistra/goenv/tree/bugfix) of the unmaintained [goenv](https://github.com/wfarr/goenv) which is based on rbenv.

## Package manager:

Since packages can be installed via a simple `go get github.com/user/repo`, small projects don't tend to use a package manager, but rely on stable master branches.

Bigger projects often use [godep](https://github.com/tools/godep) for package management which allows easier installation of many packages and locking of code revisions.

