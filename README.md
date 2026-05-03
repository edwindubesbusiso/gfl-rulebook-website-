JW's Golden Football League — Official Rule Book

A clean, fully static multi-page website serving as the official rule book for the **JW's Golden Football League (GFL)**. Built with pure HTML and CSS — no frameworks, no dependencies, no build tools required.

---

---

🚀 Getting Started

No installation or server needed. Just open the project locally:

1. **Clone the repository**
```bash
   git clone https://github.com/edwindubesbusiso/gfl-rulebook.git
```

2. **Open in your browser**
```bash
   cd gfl-rulebook
   open index.html
```
   Or simply double-click `index.html` in your file explorer.

> ✅ Works entirely offline. The only external dependency is Google Fonts — the design degrades gracefully without an internet connection.

---

🛠️ Built With

| Technology | Usage |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Styling, animations, and responsive layout |
| Google Fonts | `Bebas Neue` (display) & `DM Sans` (body) |
| Vanilla JavaScript | Hamburger menu toggle (inline, no libraries) |

---

✨ Features

- **Hamburger navigation** — slides down a full-width dropdown on all pages; morphs into ✕ when open
- **Active page highlighting** — the current section is always highlighted in gold in the menu
- **Fade-in animations** — page headers and content animate in on load
- **Fully responsive** — adapts to mobile, tablet, and desktop viewports
- **No framework dependencies** — zero npm, zero build steps, zero config
- **Self-contained** — all links are relative; the entire site runs from a local folder

---

📋 Rule Book Sections

| # | Page | Description |
|---|---|---|
| 00 | Mission | The league's founding statement and core values |
| 01 | Eligibility | Who can play — affiliation, age, and conduct rules |
| 02 | Points | The 3-point system and all 6 tie-breaker criteria |
| 03 | Cards | Yellow/red card offences, bans, and appeals |
| 04 | Bookings | Venue booking requirements and manager duties |
| 05 | Gameplay | Pre-match reminders, safety, and referee guidelines |
| 06 | Roles | Responsibilities of Managers, Organisers, Support & Disciplinary Teams |
| 07 | Disclaimer | Full liability waiver and participation agreement |

---

🎨 Design Tokens

The colour palette and typography are defined as CSS variables in `styles.css`:

```css
--gold:        #C9A84C   /* Primary accent */
--gold-light:  #E8C96A   /* Gradient highlight */
--gold-dim:    #7a6128   /* Subtle accent / borders */
--dark:        #0e0e0e   /* Page background */
--surface:     #161616   /* Card background */
--surface2:    #1e1e1e   /* Card hover state */
--border:      #2a2a2a   /* Dividers and outlines */
--text:        #e8e2d6   /* Primary text */
--muted:       #888070   /* Secondary / label text */
```

---

🤝 Contributing

This project is maintained for internal league use. If you are a league organizer and need to update the rules:

1. Fork the repository
2. Edit the relevant `.html` file(s)
3. Open a pull request with a brief description of the change

---

📄 License

This project is for internal use by the JW's Golden Football League community. All content and rules are the property of the GFL organizers.

---
<div align="center">
  <strong>GFL</strong> — JW's Golden Football League &nbsp;·&nbsp; Official Rule Book
</div>
