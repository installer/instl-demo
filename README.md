# test-repo

This repo is used to test installations via [instl](https://github.com/installer/instl)

## Production

> Use these commands to test the production build of instl:

### Windows

```
iwr instl.sh/installer/instl-demo/windows | iex
```

### Linux

```
curl -sSL instl.sh/installer/instl-demo/linux | bash
```

### macOS

```
curl -sSL instl.sh/installer/instl-demo/macos | bash
```

## Dev (local)

> Use these commands to test a local version of instl.
> Useful for debugging and testing

### Windows

```
iwr 127.0.0.1/installer/instl-demo/windows | iex
```

### Linux

```
curl -sSL 127.0.0.1/installer/instl-demo/linux | bash
```

### macOS

```
curl -sSL 127.0.1/installer/instl-demo/macos | bash
```
