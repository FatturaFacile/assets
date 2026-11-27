# FatturaFacile Assets

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Brand assets and media kit for the [FatturaFacile](https://github.com/FatturaFacile) open-source ERP: logos, icons, fonts and the project presentation.

This repository contains no code. It is only a collection of files that other FatturaFacile repositories and community material can reuse.

## Contents

```text
assets/
├── branding/
│   ├── logos/        # Logo in SVG, PNG, PDF and source formats (Illustrator, Photoshop and VectorCraft sources)
│   ├── icons/        # Favicon and app icons (SVG, PNG, ICO, PSD) and the web favicon set in favicon/
│   └── fonts/        # Inter and Merriweather (variable and static TTF), each with its OFL.txt
├── docs/             # Presentation "Il progetto e come contribuire" (.pptx and .pdf)
├── LICENSE
├── SECURITY.md
├── qodana.yaml                # Qodana static analysis settings
└── sonar-project.properties   # SonarQube settings
```

## Brand colors

| Name | Hex | Use |
| :--- | :--- | :--- |
| Primary Navy | `#0F172A` | Backgrounds, primary text, contrast |
| Accent Emerald | `#10B981` | Buttons, highlights, badges |
| Surface Gray | `#F8FAFC` | Light backgrounds, cards |
| Slate Gray | `#64748B` | Secondary text, borders, placeholders |

## Fonts

The presentation in `docs/` uses **Inter** (body) and **Merriweather** (titles). Both are distributed under the [SIL Open Font License 1.1](https://openfontlicense.org/); the license text is in `branding/fonts/<font>/OFL.txt`.

## Using the assets

Link a file from another repository with its raw URL on the `dev` branch:

```markdown
<img src="https://raw.githubusercontent.com/FatturaFacile/assets/dev/branding/logos/fattura_facile_logo_trasparente.svg" alt="FatturaFacile logo" width="220" />
```

Prefer SVG for the web. Keep the original proportions and colors of the logo, and do not use the brand marks to suggest an official endorsement of an unrelated product.

## Testing and linting

There is nothing to build or run. Static analysis only (see Qodana and SonarQube files above).

## CI and branching

- `dev` is the default branch. Open pull requests against `dev`; `main` is not a target for pull requests.
- The `Build` workflow (`.github/workflows/build.yml`) runs a SonarQube scan on pull requests and pushes to `main`.
- A `Telegram Notifications` workflow posts repository activity to the team chat.
- Pull requests need approval from the code owners listed in `.github/CODEOWNERS`.

## Related repositories

| Repository | Role |
| :--- | :--- |
| [`FatturaFacile`](https://github.com/FatturaFacile/FatturaFacile) | Organization overview and repository map |
| [`website`](https://github.com/FatturaFacile/website) | Public website, [fatturafacile.eu](https://fatturafacile.eu) |
| [`web-api`](https://github.com/FatturaFacile/web-api) | Backend API |
| [`web-frontend`](https://github.com/FatturaFacile/web-frontend) | Web ERP client |

## Documentation

The project wiki is at [FatturaFacile/FatturaFacile wiki](https://github.com/FatturaFacile/FatturaFacile/wiki).

## License

The repository is released under the [MIT License](LICENSE). Fonts keep their own SIL Open Font License 1.1 (see above).
