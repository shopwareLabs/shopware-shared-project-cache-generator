# Generates shared project index for PhpStorm

Shared Index is an new Feature in PhpStorm to pre-index an project and share the index to all users. Users will download the index and reuse it.

This is currently in Work in PhpStorm and does not hit very often.

## How to use it?

Create a new file `intellij.yaml` in your project with the content:

```yaml
sharedIndex:
    project:
        - url: https://cdn.fos.gg/phpstorm/project/sw6_trunk
```

After saving the file PhpStorm will question to download the shared index
