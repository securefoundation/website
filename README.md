# SecureFoundation Website

## Dependencies

Tested with [Hugo](https://github.com/spf13/hugo/releases) 0.19:

```
$ hugo version
Hugo Static Site Generator v0.19 linux/amd64 BuildDate: 2017-02-27T04:38:34-08:00
```

Requires
[pygments-lexer-babylon](https://github.com/richardbann/pygments-lexer-babylon)
for JSX syntax highlighting with pygments.

```
# pip install pygments-lexer-babylon
```

## Hacking

Hugo will run a local web server that automatically reloads based on changes to the source:

```
$ hugo server
```

## Building

We can build the static site to a destination directory like so:

$ hugo -d ~/securefoundation.github.io
