This repository demonstrates that, contrary to what [the documentation](https://jekyllrb.com/docs/configuration/options/) says, Jekyll's option `include` ignores folder names.

## How to build?

```
bundle exec jekyll build
```

## Expected output

```
_site/
  excluded/
    included/
      this-file-should-be-included
```

## Actual output

```
_site/
  (empty)
```
