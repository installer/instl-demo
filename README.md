# test-repo

This repo is used to test installations via [instl](https://github.com/installer/instl)

## Dev (local)

### Windows

```
iwr 127.0.0.1/installer/instl/windows | iex
```

### Linux

```
curl -sSL 127.0.0.1/username/reponame/linux | bash
```

### macOS

```
curl -sSL 127.0.1/installer/instl/macos | bash
```

## Production

### Windows

```
iwr instl.sh/installer/instl/windows | iex
```

### Linux

```
curl -sSL instl.sh/username/reponame/linux | bash
```

### macOS

```
curl -sSL instl.sh/installer/instl/macos | bash
```
