# Motorcycle Trip Packing List | Riders Share

An interactive, mobile-friendly packing checklist for motorcycle touring trips. Built as a single-page static app, ready for GitHub Pages deployment.

![Riders Share](https://images.prismic.io/riders-sharecom/aRyKgGGnmrmGp_Hh_logo_black_background_v2.png?auto=format,compress)

## Features

- **Trip type filtering** - Weekend, Week Trip, Long Tour, and Camping presets
- **85+ curated items** across 9 categories (Gear, Clothing, Toiletries, Tools, Electronics, Documents, Luggage, Miscellaneous, Camping)
- **Check-off tracking** with per-category progress and overall progress bar
- **Estimated pack weight** with light/moderate/heavy indicators
- **Search and filter** by priority (Essential, Optional, Weather) or unchecked items
- **Custom items** - add your own items to any category
- **Save/Load progress** - export and import your checklist as JSON
- **Print-friendly** - clean print stylesheet for paper checklists
- **localStorage persistence** - progress saves automatically between visits
- **Fully responsive** - works on mobile, tablet, and desktop

## Deployment

### GitHub Pages (Recommended)

1. Push this repo to GitHub
2. Go to **Settings > Pages**
3. Set source to **GitHub Actions** (or **Deploy from a branch** > `main` > `/ (root)`)
4. Your site will be live at `https://<username>.github.io/<repo-name>/`

### Manual

Simply serve `index.html` from any static host. No build step required.

## File Structure

```
/
├── index.html          # Full application (single-file, no dependencies)
├── README.md           # This file
├── LICENSE             # MIT License
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Actions workflow for Pages deployment
```

## Credits

- Content based on the [Riders Share Motorcycle Trip Packing Guide](https://www.ridersshare.com/blog/how-to-pack-for-a-motorcycle-trip)
- Built for [Riders Share](https://www.ridersshare.com) - the largest peer-to-peer motorcycle rental platform in the U.S.

## License

MIT License. See [LICENSE](LICENSE) for details.
