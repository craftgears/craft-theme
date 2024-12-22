# Craft Theme

## Features

## Installation

```bash
git submodule add https://github.com/craftgears/craft-theme.git themes/craft-theme
```

`config/_default/module.toml`

```toml
[[imports]]
path = "github.com/craftgears/craft-theme"
```

`go.mod`

```go
replace github.com/craftgears/craft-theme => ./themes/craft-theme
```

## Configuration

## exampleSite

```bash
$ cd exampleSite
$ npm install
$ hugo server -D
```


