# Omnilegent

*Omnilegent* (adj.): Being widely read; having read across literature, history, science, philosophy and more.

[Omnilegent](https://omnilegent.net) is a place to keep track of what you read, see what the people you trust are reading, and pass books between you. It was built by one person, from scratch, because no existing site did those three things together without ads, affiliate links, or an investor waiting behind them.

## What lives here

The Omnilegent service itself is **not open source** and is not hosted on GitHub. This organization holds the parts that are open:

- **[docs](https://github.com/omnilegent-dev/docs)**, the public API reference, published at [docs.omnilegent.net](https://docs.omnilegent.net)
- **Client libraries**, official and community SDKs, as they appear
- **Showcase**, integrations, sync tools, and clients other people have built

If you want to build something that reads or writes your own Omnilegent library, a sync plugin for your e-reader, a Stream Deck plugin, a terminal client, an Obsidian plugin, a dashboard, this is where to start and showcase what you've built!

## The API in one paragraph

Every token belongs to a single, human person and can only see what that person can see. There is no site-wide key, and there never will be.

Tokens are scoped, expire, and are revocable from your settings page. The API returns your own data, including your shelves, reading and book statuses, dates, ratings, notes, tags, plus ISBNs and minimal book identifiers. It does not return the licensed catalogue in bulk, and it does not let anyone enumerate entire catalogue of users or libraries.

## What Omnilegent will not do

- **No advertising.** Not now, not at scale, not even "tasteful" ads. Not now, not ever.
- **No affiliate links.** Buy links go straight to the seller. No commission incentive.
- **No selling or marketing your data.** Private is private. Private notes never leave your own page.
- **No paywalled features.** Everyone gets every feature all the time. No "Pro" tiers with additional features.
- **No data lock-in.** One-click CSV and JSON export, any time, in real-time.

The full version of all features and the origin story, with the running costs published as a live receipt, can be found on the [About page](https://omnilegent.net/about).

## Contributing

Docs fixes, API bug reports, SDKs and showcase entries are welcome. See [CONTRIBUTING.md](https://github.com/omnilegent-dev/.github/blob/main/CONTRIBUTING.md).

Issues about the *service*, including any data import errors, account issues, something on the site not behaving properly, are not tracked here. Email [contact@omnilegent.net](mailto:contact@omnilegent.net?subject=Omnilegent%20feedback) if you want report those.
