# freeCodeCamp News Author Page

🌐 **[Live Page](https://rustom-yadav.github.io/fcc-authors-page-app)** 

📂 **[Repo](https://github.com/Rustom-yadav/fcc-authors-page-app)**

A simple, responsive author directory that fetches and displays freeCodeCamp news authors from their CDN API. Built with vanilla HTML, CSS, and JavaScript.

## Features

- **Author cards** — Name, avatar, short bio, and link to author page
- **Load more** — Shows 8 authors at a time; "Load More Authors" fetches the next 8
- **Error handling** — Shows a message if the API request fails
- **Responsive layout** — Flexbox grid that wraps on smaller screens
- **freeCodeCamp styling** — Dark theme with purple and golden-yellow accents

## How to Run

1. Clone or download this repo.
2. Open `index.html` in a browser, or serve the folder locally (e.g. with Live Server).

No build step or dependencies required.

## Tech Stack

- **HTML5**
- **CSS3** (custom properties, flexbox)
- **Vanilla JavaScript** (Fetch API)

## Project Structure

```
fcc-authors-page-app/
├── index.html      # Main page and layout
├── styles.css      # Layout and theme styles
├── script.js       # Fetch authors, render cards, load-more logic
├── README.md
├── LICENSE
└── .gitignore
```

## Data Source

Author data is loaded from:

`https://cdn.freecodecamp.org/curriculum/news-author-page/authors.json`

## License

MIT — see [LICENSE](LICENSE).
