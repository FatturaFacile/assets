# FatturaFacile — Brand Assets & Media Kit

Official collection of brand assets, logos, design tokens, banners, and screenshots for the [FatturaFacile](https://github.com/FatturaFacile) open-source ecosystem.

---

## 📁 Repository Structure

```text
assets/
├── branding/
│   ├── logos/                # Primary, monochrome, and inverted logos (.svg, .png)
│   ├── icons/                # App icons, favicons, square variants (.svg, .ico, .png)
│   ├── badges/               # Shields and partner/technology badges (.svg)
│   └── fonts/                # Fonts used in the presentation (Inter, Merriweather), each with its OFL license
├── docs/                     # Presentation "Il progetto e come contribuire" (.pptx + .pdf, 18-slide version is current)
├── ui/
│   ├── banners/              # Social previews, GitHub headers, README banners
│   ├── screenshots/          # App screenshots (Desktop, Web, Mobile)
│   └── illustrations/        # Vector illustrations and empty-state graphics
└── guidelines/
    └── color-palette.md      # Hex codes, RGB, tokens, and typography specifications
```

---

## 🎨 Brand Identity & Colors

When using FatturaFacile assets in companion modules, websites, or documentation, please adhere to our core palette:

| Name | Hex Code | Purpose | Preview |
| :--- | :--- | :--- | :--- |
| **Primary Navy** | `#0F172A` | Backgrounds, primary text, contrast | `■` |
| **Accent Emerald** | `#10B981` | Action buttons, highlights, badges | `■` |
| **Surface Gray** | `#F8FAFC` | Light mode backgrounds, card containers | `■` |
| **Slate Gray** | `#64748B` | Secondary text, borders, placeholders | `■` |

### Fonts

The presentation in `docs/` uses **Inter** (body text) and **Merriweather** (titles). Both are variable fonts distributed under the [SIL Open Font License 1.1](https://openfontlicense.org/), included in `branding/fonts/<font>/OFL.txt`; they are not covered by the CC BY license below.

---

## 🚀 Usage Guidelines

### In GitHub READMEs (Direct Link)

You can embed raw assets across any FatturaFacile repository using GitHub raw content URLs:

```markdown
<!-- Header Banner -->
![FatturaFacile Banner](https://raw.githubusercontent.com/FatturaFacile/assets/main/ui/banners/readme-header.png)

<!-- Logo -->
<img src="https://raw.githubusercontent.com/FatturaFacile/assets/main/branding/logos/logo-horizontal.svg" alt="FatturaFacile Logo" width="220" />
```

### In Web / HTML Projects

Vector files (`.svg`) are preferred for web usage to preserve sharpness across high-DPI displays. High-resolution raster images (`.png`) are provided in `1x`, `2x`, and `4x` resolutions for platforms that do not support SVG.

---

## ⚖️ Permitted & Prohibited Uses

* **Do:** Use these assets to refer to the official FatturaFacile project, community forks, plugins, or official integrations.
* **Do:** Maintain the original aspect ratio and clear spacing around logos and badges.
* **Don't:** Modify colors, distort proportions, or use the brand marks in a way that implies official endorsement for an unrelated commercial product without permission.

---

## 📄 License

Fonts in `branding/fonts/` keep their own SIL OFL 1.1 license (see above). The graphical and brand assets in this repository are distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license, allowing free sharing and adaptation with appropriate attribution to **FatturaFacile**.

For software components and source code repositories, please refer to the respective project's [MIT License](https://opensource.org/licenses/MIT).