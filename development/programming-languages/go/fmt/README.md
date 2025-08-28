### go fmt

**Usagge:** Format Go source files, printing the changed filenames. <br />
**More information:** https://pkg.go.dev/cmd/go#hdr-Gofmt__reformat__package_sources. <br />

Format Go source files in the current directory:

```
go fmt
```

Format a specific Go package in your import path ($GOPATH/src):

```
go fmt path/to/package
```

Format the package in the current directory and all subdirectories (note the ...):

```
go fmt ./...
```
