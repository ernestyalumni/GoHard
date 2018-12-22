# GoHard
Examples in Go


cf. [How to Write Go Code](https://golang.org/doc/code.html)

## Workspaces

Workspace is a directory hierarchy with two directories at its root:

* `src` contains Go source files, and 
* `bin` contains executable commands.

## Package names

The first statement in a Go source file must be 
```
package name
```

where `name` is the package's default name for imports.

Go's convention is that package name is the last element of the import path: the package imported as "`crypto/rot13`" shoudl be named `rot13`.

