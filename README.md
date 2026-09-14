# Omnilegent API documentation

Source for the public API reference at [docs.omnilegent.net](https://docs.omnilegent.net).

[Omnilegent](https://omnilegent.net) is a book reading tracker with a social layer. The service itself is closed source; this repository holds its API documentation, which is fully open.

## The API in one paragraph

Every token belongs to a single, human person and can only see what that person can see. There is no site-wide key, and there never will be.

Tokens are scoped, expire, and are revocable from your settings page. The API returns your own data, including your shelves, reading and book statuses, dates, ratings, notes, tags, plus ISBNs and minimal book identifiers. It does not return the licensed catalogue in bulk, and it does not let anyone enumerate entire catalogue of users or libraries.

## Status

The API is a work in progress, being designed based on feedback from users. This repository will fill in as endpoints land. Watch the repo or follow the [news page](https://omnilegent.net/news) for announcements.

## What's here

- `SHOWCASE.md`, things people have built against the API. Add yours by submitting a pull request.
- API reference, this is coming!

## Contributing

Docs fixes and API bug reports are welcome. See [CONTRIBUTING.md](https://github.com/omnilegent-dev/.github/blob/main/CONTRIBUTING.md).

Issues about the *service*, including any data import errors, account issues, something on the site not behaving properly, are not tracked here. Email [contact@omnilegent.net](mailto:contact@omnilegent.net?subject=Omnilegent%20feedback) if you want report those.

## Licence

Documentation and code samples are Apache-2.0 licensed.
