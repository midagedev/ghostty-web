# IME screenshots

Evidence for the `ime-cursor-position` branch. Both captured from the same
harness — a terminal in a `position: relative` panel, cursor on the last
line — with Chrome DevTools `Input.imeSetComposition` setting the marked
text "한글". That is the same path a platform IME takes, so the browser
really renders these preedits; they are not synthetic CompositionEvents.

- `shots/before.png` — the branch's parent commit
- `shots/after.png` — the branch
