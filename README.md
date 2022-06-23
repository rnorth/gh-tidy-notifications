# gh-tidy-notifications

This is an extension for [GitHub CLI](https://cli.github.com/) that tidies GitHub notifications.

It simply applies a simple heuristic: marking 'done' any notification that relates to a Closed issue or Merged/Closed PR.

It's a simple way of tidying up notifications that probably aren't relevant to you any more. 
Don't use this if you need to pay special attention to closed or merged items.

## Installation

Prerequisites:
 * [GitHub CLI](https://cli.github.com/) is already installed and authenticated
 * [`jq`](https://stedolan.github.io/jq/) is installed

To install this extension:

```
gh extension install rnorth/gh-combine-prs
```

or (if using GitHub Enterprise):

```
gh extension install github.com/rnorth/gh-combine-prs
```

## Usage

```
gh tidy-notifications
```

## License

See [LICENSE](./LICENSE)
