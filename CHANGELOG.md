## 0.4.2 (July 10, 2013)

- Fixed the issue of not showing page title
- Fixed the issue of not stripping YAML frontmatter
- Fixed the issue that moo crashes if highlight.js doesn't know how to highlight a language

## 0.4.0 (June 2, 2013)

- Single file code base
- Added pandoc support
- New Github CSS

## 0.3.2 (May 21, 2013)

- Fixed issue #6

## 0.3.1 (May 17, 2013)

- Fixed issue #4

## 0.3.0 (May 16, 2013)

Completely rewritten in node.js.

- damn fast markdown parsing thanks to [robotskirt][rs]
- instant update push by server-sent events (replace AJAX polling)
- automatically strip YAML front-matter (for Jekyll)
- syntax highlight with [highlight.js](hljs)

[rs]: https://github.com/benmills/robotskirt
[hljs]: https://github.com/isagalaev/highlight.js

## 0.2.0 (March 14, 2013)

First stable release.

- replace Flask with bottle.py
- use cherrpy as server
- export to html mode

