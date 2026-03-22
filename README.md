# Benjamin Garcés · Personal Webpage & Portfolio
 
Personal webpage and science communication portfolio of **Benjamin Garcés Cifuentes** — Biochemistry Engineer, bioinformatician, and science communicator based in Ambato, Ecuador.
 
**Live site:** [charlesdexterw.github.io/BGC](https://charlesdexterw.github.io/BGC/)
 
---
 
## About the site
 
A bilingual (EN/ES) personal portfolio covering three areas:
 
- **Research** — phylogenetics, conservation genomics, molecular docking, and computational biology projects linked directly to their GitHub repositories
- **Science communication** — original articles on microbiology, neuroscience, and public health, written for general audiences
- **Publications** — peer-reviewed Springer chapter (TICEC 2022) and undergraduate thesis
 
The bilingual toggle switches the entire interface between English and Spanish without a page reload, using a lightweight vanilla JS class-swap approach.
 
---
 
## Features
 
- **Bilingual UI (EN/ES)** — full interface and content available in both languages via a single toggle; no frameworks, no reload
- **Dynamic article loading** — sci-comm articles are injected asynchronously via the Fetch API from separate HTML files, keeping `index.html` maintainable
- **Sticky two-column layout** — fixed left sidebar with bio and skills; scrollable right main column with sectioned content
- **Responsive** — collapses to single-column on screens below 860px
- **Open Graph & Twitter card meta tags** — structured link previews for LinkedIn, WhatsApp, and X/Twitter shares
- **CC BY-NC-SA 4.0 licensing** — all science communication content explicitly licensed
 
---
 
## Project structure
 
```
BGC/
├── index.html               # Main landing page — all sections
├── Style1.css               # Layout, typography, component styles
├── _config.yml              # GitHub Pages configuration
├── .gitignore
│
├── article1.html            # Sci-comm: Does cold weather make you sick?
├── article2.html            # Sci-comm: Understanding Alzheimer's
├── article4.html            # Sci-comm: Antibiotic resistance
├── article5.html            # Sci-comm: (supporting file)
├── article5_1.html          # Sci-comm: Phage therapy
├── article_template.html    # Template for new articles
│
├── Analysis.html            # Atelopus sp. cryopreservation analysis
├── genom_seq_analysis_repo.html  # mm9 genomic sequence analysis write-up
├── test.html                # Development scratch file
│
└── images/
    ├── 324a.jpg             # Profile photo
    ├── cell.ico             # Favicon
    ├── linkedin.png         # Social icon
    ├── b-github-30.png      # Social icon
    ├── x.png                # Social icon
    ├── mail.png             # Social icon
    └── thumbnail_webpage.png  # Open Graph preview image
```
 
---
 
## Tech stack
 
- **HTML5** — semantic structure, bilingual `data-lang` attribute pattern
- **CSS3** — custom properties, grid layout, sticky positioning, `@keyframes` animations
- **JavaScript (ES6)** — DOM class toggling for language switch, Fetch API for article injection
- **Google Fonts** — DM Serif Display + DM Sans
- **GitHub Pages** — static hosting, no build step required
 
---
 
## Local development
 
The Fetch API calls for article content are blocked by CORS if you open `index.html` directly from the filesystem. Use a local server instead:
 
```bash
# Python (recommended)
cd BGC/
python3 -m http.server 8000
# Then open: http://localhost:8000
```
 
---
 
## License
 
Science communication content is licensed under  
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](http://creativecommons.org/licenses/by-nc-sa/4.0/).
 
You are free to share and adapt the content provided you give appropriate credit and do not use it for commercial purposes.
 
Source code (HTML/CSS/JS) is available for reference. If you reuse structural patterns, attribution is appreciated.
 
---
 
## Author
 
**Benjamin Garcés Cifuentes**  
Biochemistry Engineer · Bioinformatician · Science Communicator  
Ambato, Ecuador
 
[LinkedIn](https://www.linkedin.com/in/abgc2381) · [GitHub](https://github.com/CharlesDexterW) · [X/Twitter](https://twitter.com/Charles_DexterW) · agarces2381@gmail.com
 

- Bash
- python3 -m http.server 8000
- Open your browser and navigate to http://localhost:8000.

### License
This project is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International. This means you are free to share and adapt the material, provided you give appropriate credit and do not use it for commercial purposes.
