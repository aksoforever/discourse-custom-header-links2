# discourse-custom-header-links2

This is a fork of the original
[discourse/discourse-custom-header-links](https://github.com/discourse/discourse-custom-header-links).

## Change #1: bug fix

The issue
"[Links reload Discourse](https://meta.discourse.org/t/custom-header-links-links-reload-discourse/113907)"
has been fixed.

The fix consisted in reverting
[this commit](https://github.com/discourse/discourse-custom-header-links/commit/bfda9d3b50bd8e027024b62aa0b7e68611248073),
called "adds auto-route to avoid losing queryParams on successive clicks".
Consequently, the fix might cause **_queryParams loss on successive clicks_**,
whatever that means.

## Change #2: new features

- Links not showing up on mobile or desktop are moved to the Discourse hamburger
  menu (optionally)
- Links can be styled individually

# Screenshots
