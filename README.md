# amberb617/tap

Homebrew formulae for [unpick](https://github.com/amberb617/unpick), which vets AI agent skills, MCP
servers, plugins and rules files on your own machine before you trust them.

```
brew install amberb617/tap/unpick
```

Or `brew tap amberb617/tap`, then `brew install unpick`. In a `Brewfile`:

```ruby
tap "amberb617/tap"
brew "unpick"
```

The formula includes the terminal home screen, the watcher and the local web UI. YARA-X and the
on-device fallback judge stay optional: see `unpick backends` and `unpick judges`.
