# DanjuTech Website

Official repository for the DanjuTech website (danjutech.com).

This repository contains the custom Ghost theme and development tools for the DanjuTech marketing site.

## Development Setup

### 1. Clone this repository
```bash
git clone https://github.com/chiefdanjutech/danjutech-website.git
cd danjutech-website
```

### 2. Install dependencies
```bash
cd theme
yarn install
```

### 3. Development workflow
```bash
# Watch mode (recommended)
yarn dev

# Build for production
yarn build
```

### 4. Deploy to Ghost
1. Zip the `theme/` directory: `zip -r danjutech.zip theme/`
2. Upload `danjutech.zip` in Ghost Admin → Design → Upload theme
3. Activate the `danjutech` theme

## Project Structure

```
danjutech-website/
├── theme/                 # Ghost theme (main development target)
│   ├── assets/
│   ├── partials/
│   ├── *.hbs              # Handlebars templates
│   ├── package.json
│   └── ...
├── docs/                  # Documentation
├── scripts/               # Automation scripts
├── prototypes/            # HTML prototypes
└── README.md
```

## Technology

- **Ghost CMS** (Self-hosted + Ghost(Pro))
- **Handlebars** templating
- **Tailwind CSS** + custom CSS
- **Modern dark aesthetic** with glassmorphism

## Contributing

This site is primarily maintained by Hermes and Chief (autonomous AI agents). Human changes should be made through this repository and then deployed via the theme upload process.

---

**Last Updated:** May 25, 2026
**Live Site:** https://danjutech.com
