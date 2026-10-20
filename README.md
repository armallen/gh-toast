# gh-toast

macOS popups for your GitHub notifications, using the `gh` CLI.

## Setup

```sh
brew install gh terminal-notifier
gh auth login
gh extension install armallen/gh-toast
gh toast install
```

To keep popups on screen, set **System Settings → Notifications →
terminal-notifier** to *Persistent*.

Uninstall with `gh toast uninstall`.
