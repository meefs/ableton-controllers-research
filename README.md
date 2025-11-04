# Ableton Controllers Research

A comprehensive, well-researched catalog of all natively supported Ableton Live control surfaces, organized by manufacturer with current product status, official links, and pricing information.

## Overview

This project provides a complete reference guide for Ableton Live compatible MIDI controllers and control surfaces. The catalog includes:

- **126+ control surfaces** across 18 manufacturers
- **Current and discontinued** products clearly marked
- **Official product links** to OEM pages
- **Pricing information** including MSRP and current market rates (2025)
- **Comprehensive research** with historical context on legacy products

## Features

- Clean, searchable markdown tables organized by manufacturer
- Professional GitHub Pages site built with Jekyll
- Responsive design for desktop and mobile viewing
- Navigation quick-links to jump between manufacturers
- Original Excel spreadsheet included for reference

## Live Site

View the catalog at: [https://meefs.github.io/ableton-controllers-research](https://meefs.github.io/ableton-controllers-research)

## Repository Contents

```
ableton-controllers-research/
├── index.md                               # Main catalog page with all tables
├── _config.yml                            # Jekyll configuration
├── _layouts/
│   └── default.html                       # Layout template
├── assets/
│   └── css/
│       └── style.css                      # Custom styling
├── ableton_control_surfaces_catalog.xlsx  # Original research data
├── README.md                              # This file
└── .gitignore                             # Git ignore rules
```

## Data Organization

The catalog is organized into sections by manufacturer:

- **Ableton** - Push series and Move controller
- **Akai Professional** - APC, MPD, MPK series
- **Alesis** - V, VI, VX keyboards and controllers
- **Arturia** - KeyLab, BeatStep, MiniLab series
- **Behringer** - BCF, BCR series
- **Blackstar** - Live Logic
- **Faderfox** - LV, LX series
- **IK Multimedia** - iRig Keys IO
- **Korg** - padKONTROL, Keystage
- **M-Audio** - Axiom, Code, Oxygen, and legacy series
- **Mackie** - Control series
- **Native Instruments** - Komplete Kontrol series
- **Novation** - Launch and Launchpad series
- **PreSonus** - ATOM, FaderPort series
- **Reloop** - KeyFadr, KeyPad
- **ROLI** - BLOCKS
- **Roland** - AIRA, FANTOM, FA series
- **Tascam** - FireOne

## Data Sources

Research was conducted using:

- Manufacturer official product pages
- Authoritative music production retailers (Sweetwater, B&H, Thomann)
- Wikipedia for historical context
- Sound on Sound reviews for technical specifications
- eBay and used market pricing for discontinued items

## Status Definitions

- **Verified** - Product is currently available or has verified current information
- **Discontinued** - Product is no longer manufactured but may be available used/secondhand

## Pricing Notes

Pricing information includes:

- **MSRP** (Manufacturer's Suggested Retail Price) when available
- **Current Market Price** for 2025
- Regional variations noted (USD/EUR/GBP)
- Used/Legacy product pricing when applicable

## Excel Source File

The original Excel spreadsheet (`ableton_control_surfaces_catalog.xlsx`) is included in this repository for those who prefer to work with the tabular data in spreadsheet format.

## Building Locally

To build and test this site locally:

```bash
# Install Ruby and Jekyll (if not already installed)
gem install jekyll bundler

# Navigate to the repository
cd ableton-controllers-research

# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# Visit http://localhost:4000 in your browser
```

## GitHub Pages Setup

To enable GitHub Pages for this repository:

1. Go to repository Settings
2. Navigate to Pages section
3. Set Source to `main` branch, `/root` folder
4. Save

GitHub will automatically build and publish your site.

## Contributing

If you find outdated information or missing products:

1. Research the product using manufacturer sources
2. Update the appropriate section in `index.md`
3. Commit with a clear message describing the change
4. Push to the repository

## License

This research catalog is provided as-is for educational and reference purposes.

## Last Updated

Generated November 3, 2025

---

For questions or corrections, please submit a pull request or issue on the GitHub repository.
