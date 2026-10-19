# Aryan — Portfolio (Kage edition)

Personal portfolio of Aryan (MCA, Bengaluru) — cybersecurity projects and
Python/backend work — built on the **Kage** landing page from the ThreeUI
Community catalog.

## Run locally

```
py -3 -m http.server 8000
# open http://localhost:8000
```

No build step, no paid services, no external assets at runtime (three.js and
fonts are bundled under `secret-pathways-assets/`). Review states:
`index.html?shot=0` … `?shot=5` jump to a section with reveals forced on.

## License and attribution

- Site design and scene code: **Kage**, ThreeUI Community, MIT License,
  Copyright (c) 2026 Meng To. See `LICENSE` (must stay with this project).
- three.js: MIT. Fonts (Onest, Fragment Mono): SIL OFL 1.1.
  See `THIRD_PARTY_NOTICES.md` and `FONT-LICENSES.md`.
- Portfolio content (text, project descriptions, experience): Aryan.
- Adapted from the ThreeUI Community distribution only; the older standalone
  `MengTo/kage` repository has no license and was not used.
