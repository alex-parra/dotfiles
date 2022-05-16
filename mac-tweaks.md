## Disable Dock show delay

```shell
$ defaults write com.apple.Dock autohide-delay -float 0 && killall Dock
```

## Disable screenshot shadow

```shell
$ defaults write com.apple.screencapture disable-shadow -bool TRUE && killall SystemUIServer
```

## Key repeat

```shell
$ defaults write -g ApplePressAndHoldEnabled -bool FALSE
```

## Finder path bar start at ~

```shell
$ defaults write com.apple.finder PathBarRootAtHome -bool TRUE; killall Finder
```
