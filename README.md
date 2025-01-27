# nimibook

A port of [mdbook](https://rust-lang.github.io/mdBook/index.html)
to [nim](https://nim-lang.org/),
powered by [nimib](https://pietroppeter.github.io/nimib/).

Currently a PoC with minimal functionality hacked together to support [sciNim/getting-started](https://github.com/SciNim/getting-started).

# Usage

* 1) Write your content using [nimib](https://pietroppeter.github.io/nimib/) in the ``book`` folder.

* 2) Use the Toc DSL to link chapters to Nim file in ``genbook.nim``.

* 3) Generate your books in the ``docs`` folder using ``nimble genbook``.

<!-- index.hbs adapted from mdbook to mustache
required fields:
- language
- default_theme
- description
- path_to_root
- preferred_dark_theme
- theme_option (light, rust, coal, navy, ayu)
- book_title
optional stuff:
- is_print
- base_url
- favicon_svg/favicon_png
- print_enable
- additional_css
- mathjax_support
- search_enable
- git_repository_url (git_repository_icon)
- git_repository_edit_url
- previous (link)
- next (link)
- livereload
- google_analytics
- playground_line_numbers
- playground_copyable
- playground_js
- search_js
- additional_js
partials:
- head
- header
- toc
assets required:
- css/variables.css
- css/general.css
- css/chrome.css
- FontAwesome/css/font-awesome.css
- highlight.css
- tomorrow-night.css
- ayu-highlight.css
- clipboard.min.js
- highlight.js
- book.js
-->
