## golit

**golit** generates literate-programming-style HTML documentation
from a Go source file. It produces HTML with comments alongside your
code.

See the [golit-generated docs](http://mmcgrana.github.com/golit/) for
more information.


### Installation

golit requires `markdow` and `pygmentize` binaries on the path.

```console
$ go get github.com/mmcgrana/golit
```

### Usage

```console
$ golit input.go title > output.html
```


### Hacking

```console
$ cd golit
$ vi ...
$ go get
$ golit ...
```

### Update Docs

```console
$ ./doc
```
