# salmanlee.github.io

## develop

```
# localhost + default port
hugo server

# localhost + your port(example:8111)
hugo server --port 8111

# ip + port (example: 10.0.0.88:8111)
hugo server --bind 10.0.0.88 -b 10.0.0.88 --port 8111
```

## public

```
# default
hugo

# use other config(example: release-config.toml)
hugo --config release-config.toml
```

## deploy github master

```
 yarn deploy
```
