# NCAIEE'2024: Conference Website

![NCAIEE'2024](images/logo.png)

Official website of the **National Conference on Artificial Intelligence in Electrical Engineering (NCAIEE'2024)**, held on **13 November 2024** at **Ouzera Campus, Medea (Algeria)**.





## About

NCAIEE'2024 brought together PhD students and researchers to exchange ideas and explore applications of AI in Electrical Engineering. The conference featured keynotes, oral sessions, poster sessions and online sessions.

This repository contains the conference website, kept as an archive of the event.

## Pages

| Page | Description |
| --- | --- |
| `index.html` | Home: overview, topics of interest, important dates |
| `call-for-papers.html` | Call for papers and downloadable PDF |
| `organization.html` | Organizing committee, track chairs, logistics team |
| `scientific-committee.html` | Scientific committee |
| `speakers.html` | Plenary speakers and biographies |
| `submission.html` | Author information, paper template, CMT submission link |
| `registration.html` | Registration (coming soon) |
| `presentation.html` | Poster, oral and online presentation guidelines |

## Built with

- HTML5
- CSS3 (responsive layout, no framework)
- Vanilla JavaScript (mobile menu and back-to-top button)

No build step and no dependencies. Fonts are loaded from Google Fonts.

## Project structure

```
.
├── index.html
├── call-for-papers.html
├── organization.html
├── scientific-committee.html
├── speakers.html
├── submission.html
├── registration.html
├── presentation.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
│   └── speakers/
└── downloads/
    ├── Call_For_Papers.pdf
    ├── NCAIEE-Word-template.docx
    └── Template_Poster_NCAIEE2024.pptx
```

## Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/ncaiee-2024.git
   cd ncaiee-2024
   ```
2. Open `index.html` in your browser, or start a local server:
   ```bash
   python3 -m http.server 8000
   ```
   Then visit http://localhost:8000.

## Deploy with GitHub Pages

1. Go to **Settings → Pages** in your repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and the `/ (root)` folder, then save.
4. After a minute or two, the site is live at `https://YOUR-USERNAME.github.io/ncaiee-2024/`.

## Contact

- Email: ncaiee.2024@univ-medea.dz
- Facebook: [@ncaiee_2024](https://www.facebook.com/profile.php?id=61564356677411)

## Credits

Organized by the Faculty of Technology, Yahia Farès University of Medea.
