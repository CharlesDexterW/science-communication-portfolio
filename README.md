# science-communication-portfolio
This repository contains the source code for the personal science communication portfolio of Benjamin Garcés C., a Biochemistry Engineer and IB Science Teacher. The project serves as a digital gallery for science-related articles, research interests (Genetics, Neuroscience, and Paleontology), and professional services.

## Features
Dynamic Article Loading: Uses asynchronous JavaScript (fetch API) to inject article content dynamically from separate HTML files (article1.html, etc.), making the portfolio easy to update without bloating the main index file.

Responsive Two-Column Layout: A structured design separating professional biography/contact info from the news gallery.

Typography & Design: Integrated Google Fonts (Helvetica Neue and Open Sans) for high readability, essential for scientific communication.

Open Access Licensing: Content is explicitly protected and shared under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license.
## Project Structure
Plaintext.
├── index.html          # Main landing page
├── Style1.css          # Primary styling and layout definitions
├── images/             # Directory for profile pictures and social icons
│   ├── 324a.jpg        # Profile image
│   ├── linkedin.png    # Social media icons
│   └── favicon.ico     # Browser tab icon
├── article1.html       # Portfolio piece 1
├── article2.html       # Portfolio piece 2
└── article4.html       # Portfolio piece 3
### Tech Stack
HTML5 & CSS3: Semantic structure and custom styling.

JavaScript (ES6): For DOM manipulation and fetching external article assets.

Google Fonts API: For professional typography.

### Local Development (Ubuntu 24.04)
To view the site locally, you should use a local server because the fetch API for articles may be blocked by CORS policies if you simply double-click the index.html file.

Open your terminal in the project folder.

Start a simple Python server:

Bash

python3 -m http.server 8000
Open your browser and navigate to http://localhost:8000.

### License
This project is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International. This means you are free to share and adapt the material, provided you give appropriate credit and do not use it for commercial purposes.
