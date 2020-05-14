# Directory

## Lookup file in directory

```strict
let directory = Path.Parse("images").Lookup() as Directory?
if directory exists 
  let imageFile = directory.Lookup("cat.png") as File?
  imageFile exists
```
