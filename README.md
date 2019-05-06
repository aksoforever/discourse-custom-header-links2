# discourse-custom-header-links2

This is a fork of the original
[discourse/discourse-custom-header-links](https://github.com/discourse/discourse-custom-header-links),
with two additional features:

- Links not showing up on mobile or desktop are moved to the Discourse hamburger
  menu (if specified in settings).
- A user-defined class can be set for links.

If you are a user of the original component, all you need to do is to copy your
former settings to the new component and add "`, true`" at the end of each link
definition. This will enable the "move to hamburger menu" feature.

![Screenshots](screenshots.png)
