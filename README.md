[README (5).md](https://github.com/user-attachments/files/31623143/README.5.md)

# Emmanuel Adenuga — AI Automation Business Analyst Portfolio

A single-page portfolio built on the [Massively](https://html5up.net/massively) template by HTML5 UP, showcasing AI automation, business analysis and data analysis project work across healthcare, finance, retail, aviation and enterprise sectors.

**🔗 Live site:** [eoaadenuga.github.io](https://eoaadenuga.github.io) <!-- update if your Pages URL differs -->

---

## About

This portfolio highlights 10+ years of experience delivering digital transformation, AI workflow automation (n8n, AI agents) and data analysis projects. It includes:

- A featured case study on an AI-powered data analyst agent (n8n, conversational memory, Google Sheets, Gmail integration)
- Six additional project case studies spanning FMCG, healthcare, aviation, retail and process mapping
- A skills & certifications overview across AI automation, business analysis, data analysis, QA testing and Agile delivery

## Tech Stack

- HTML5 / CSS3 (based on the Massively template by [HTML5 UP](https://html5up.net))
- Vanilla JavaScript (jQuery-based scroll and breakpoint utilities from the original template)
- No build step required — static site, deployable anywhere

## Project Structure

```
.
├── index.html              # Main portfolio page
├── assets/
│   ├── css/
│   │   ├── main.css         # Base Massively theme styles
│   │   └── fontawesome-all.min.css
│   ├── js/
│   │   ├── main.js
│   │   ├── util.js
│   │   ├── breakpoints.min.js
│   │   ├── browser.min.js
│   │   ├── jquery.min.js
│   │   ├── jquery.scrollex.min.js
│   │   └── jquery.scrolly.min.js
│   └── sass/                # Source SCSS (optional, if customising the theme)
├── images/                  # Project screenshots and diagrams
└── README.md
```

## Running Locally

No build tools or dependencies are required.

```bash
git clone https://github.com/eoaadenuga/<repo-name>.git
cd <repo-name>
```

Then simply open `index.html` in a browser, or serve it locally:

```bash
# Python
python3 -m http.server 8000

# Node
npx serve .
```

Visit `http://localhost:8000` (or the port shown).

## Deploying to GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Save — your site will be live at `https://<username>.github.io/<repo-name>/`.

## Customising

- **Content:** edit the project cards, bio, achievements and skills sections directly in `index.html`.
- **Styling:** custom section styles (badges, panels, skill cards, etc.) are scoped under the `ea-` class prefix inside the `<style>` block in `index.html`, kept separate from the base Massively theme in `assets/css/main.css` to avoid conflicts.
- **Images:** replace files in `/images` — keep filenames free of spaces (use hyphens) for reliable hosting on GitHub Pages and other static hosts.

## Credits

- Template: [Massively](https://html5up.net/massively) by [HTML5 UP](https://html5up.net) ([CCA 3.0 license](https://html5up.net/license))
- Icons: [Font Awesome](https://fontawesome.com)

## Contact

**Emmanuel Adenuga**
📍 Darlington, UK — open to remote & hybrid roles nationwide
📧 [eoaadenuga@gmail.com](mailto:eoaadenuga@gmail.com)
💼 [LinkedIn](https://www.linkedin.com/in/emmanuel-adenuga/)
🐙 [GitHub](https://github.com/eoaadenuga)
