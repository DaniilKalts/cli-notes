### go build

**Usage:** Compile Go sources. <br />
**More information:** https://pkg.go.dev/cmd/go#hdr-Compile_packages_and_dependencies. <br />

Compile a 'package main' file (output will be the filename without extension):

```
go build path/to/main.go
```

Compile, specifying the output filename:

```
go build -o path/to/binary path/to/source.go
```

Compile a package:

```
go build -o path/to/binary path/to/package
```
