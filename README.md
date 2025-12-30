# Dmytro's Homebrew Tap

## What is Homebrew?

Package manager for macOS (or Linux), see more at https://brew.sh

## What is a Tap?

A third-party (in relation to Homebrew) repository providing installable
packages (formulae) on macOS and Linux.

See more at https://docs.brew.sh/Taps

## How do I install these formulae?

```bash
brew install kpumuk/tap/<formula>
```

Or `brew tap kpumuk/tap` and then `brew install <formula>`.

Or, in a `brew bundle` `Brewfile`:

```ruby
tap "kpumuk/tap"
brew "<formula>"
```

## What packages are available?

With the following commands, you can install the latest generally available (GA) version of each product:

```bash
brew install kpumuk/tap/lazykiq
```

Prereleases (including as alpha's, beta's, and release candidates) will not be available in this tap.

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
