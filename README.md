# macos-brightness

Your friendly neighbordhood macOS brightness CLI. Sets the brightness of all displays.

Tested on macOS Mojave (10.14), should work on High Sierra (10.13) as well.

## Installing

```console
$ go get -u github.com/anoldguy/macos-brightness/cmd/brightness
```

## Usage

### Get current brightness

```console
$ brightness
75.66666603088379
```

### Set brightness percentage

```console
$ brightness -b 90.5
```

_I just needed a version of @manfredri's macos-brightness that worked across all monitors_