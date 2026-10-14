# cvp1/tap

Homebrew formulae for macOS.

| Formula | What it is |
|---|---|
| [corral-light](https://github.com/cvp1/corral-light) | Run your AI assistants side by side in a browser, on your own machine |

```
brew install cvp1/tap/corral-light
brew services start cvp1/tap/corral-light
corral-light doctor
```

Update Corral Light with `corral-light update`: it runs `brew upgrade` only
when no pane is mid-turn, then restarts the hub on the new version.

The formula's source of truth is
[`packaging/homebrew/corral-light.rb`](https://github.com/cvp1/corral-light/blob/master/packaging/homebrew/corral-light.rb)
in the corral-light repo; a release copies it here with its tarball's checksum.
