# Baotracker

An interactive, multi-layered sunburst chart for tracking goals, study subjects, habits and projects. Inspired by [Baobab](https://wiki.gnome.org/Apps/DiskUsageAnalyzer), the GNOME disk usage analyzer, but it maps what you're working on instead of what's filling your hard drive.

Everything lives in a single HTML file. No server, no account, no install.

## Features

- **Radial sunburst chart**: your main goal sits in the center, categories form the middle ring, and sub-topics or tasks form the outer rings
- **Click to zoom**: click any slice to make it the new center and focus on its branches
- **Proportional slices**: slice size reflects the weight, priority or time you give it, so you can see at a glance where your effort goes
- **Weak-spot flagging**: mark a slice (for example in red) to highlight topics that need review
- **Private and local**: data is stored in your browser with IndexedDB. Nothing is uploaded anywhere.

## Usage

1. Download `Baotracker.html`, or clone the repo:

```bash
   git clone https://github.com/YonaelT/bao-tracker.git
```

2. Open `Baotracker.html` in any modern browser.

That's all. There is no build step and no dependencies to install.

## Example uses

- Mapping a dense subject (SAT prep, a tech stack) into topics and sub-topics
- Spotting weak areas so you know where to direct your review
- Breaking a large project into milestones, tasks and micro-habits
- Keeping a high-level view of progress across several areas without digging through menus

## How it differs from list-based trackers

| List and table trackers | Baotracker |
|---|---|
| Vertical checklists or daily grids | Nested hierarchy shown as a wheel |
| Tasks shown in isolation | Proportions visible at a glance |
| Sub-topics buried in other pages | Click-to-zoom navigation |
| Often need accounts or internet | One local file that works offline |

## Data and privacy

Your data is stored by your browser, tied to the browser profile and to where the file is opened from. Opening the same file in a different browser, or from a different location, shows a separate (empty) tracker. Clearing your browser's site data erases your tracker.

## License

MIT. See [LICENSE](LICENSE).
