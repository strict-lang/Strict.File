# Lookup File

In order to lookup entries of the file-system, one has to use the Path-API
(located in the namespace `Strict.File.Path`). Paths represent the location
of a file or directory.

```strict
let path = Path.Parse("/proc/meminfo")
let file = path.LookupItem() as File
```
