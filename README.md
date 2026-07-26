# site

The runedeck website. Static HTML, no build system, no external requests: every page is self-contained with system font stacks and vendored assets only.

## Layout

- `designs/`: ten candidate landing designs plus the picker at `designs/index.html`. The winning design gets promoted to `index.html`; the rest stay as the decision record.
- `shared/tokens.css`: the rune dashboard palette as CSS custom properties, the single source of design tokens.
- `first-contact/`: the guided first-run walkthrough, built in the winning design's language.
- `index.html`: the site. The bindrune emblem composition from design 10 carried on design 1's dashboard token system; chosen from the gallery.

## Preview

```sh
python3 -m http.server 8118
open http://127.0.0.1:8118/designs/
```

## License

EUPL-1.2, matching the rest of runedeck.
