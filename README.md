# PosOne — Public Docs & Media

Visual artifacts and public-facing documentation for **PosOne**, an in-development point-of-sale terminal.

The application source code lives in a private sibling repository. This repo exists so that screenshots embedded in private-repo issue comments are reachable by GitHub's anonymous image proxy.

## Layout

```
screenshots/
  issue-N/      # PNG captures from e2e/demo.spec.ts in the main repo
                # one folder per closed-issue close comment
```

Going forward, every UI-touching issue closes with screenshots committed here and referenced from the close comment via `https://raw.githubusercontent.com/ypnpri/PosOne-docs/main/screenshots/issue-N/<file>.png`.
