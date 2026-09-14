# Contributing

Thanks for contributing to the growing Omnilegent ecosystem of projects. This file applies to every repository in the `omnilegent-dev` organisation.

## What's in scope

- Fixes and improvements to the API documentation
- Bug reports against the API (wrong response, missing field, incorrect docs)
- Client libraries and SDKs
- Showcase entries for the kinds of things you've built

## What's out of scope

- The Omnilegent service itself is closed source. Feature requests and bugs about the site, imports, or accounts are not tracked here. If you have questions or comments, email contact@omnilegent.net.
- Anything that requires access beyond a personal token acting as one user. There is no site-wide key and no bulk catalogue access, by design.

## Licence terms

By contributing you agree that your contribution is licensed under Apache-2.0, the licence of the repository you're contributing to.

No separate contributor agreement is required. If you can't agree to those terms, please don't open the pull request.

## Pull requests

- One unit of change per PR. Small PRs are fine, but no PRs crossing several features or bugs at once please.
- For docs, check the rendered result before submitting.
- For SDKs, include a test that exercises the change against a mocked response, don't require a live token to run the suite.

## Showcase entries

Add yourself to `SHOWCASE.md` in the `docs` repository. One entry per project, in the existing format. Entries should be working, public, and
yours, link to the repo or the release page, not a landing site.

## Conduct

See `CODE_OF_CONDUCT.md`. Short version: be decent, assume good faith, and remember there's just one person on the other end of this.
