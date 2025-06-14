# Google Search "Clone"

This is a basic frontend "clone" of the Google Search interface, built as part of the CS50 Web Programming with Python and JavaScript course. It replicates the core layout and behavior of:

- 🔎 Standard Google Search
- 🖼️ Google Image Search
- ⚙️ Advanced Search

## Features

- 🎯 Replicates the look and feel of Google’s homepage
- 🔍 Functional search bar redirecting to real Google results
- 🖼️ Working image search page
- ⚙️ Advanced search form with multiple input fields
- 🎨 Clean, responsive design using HTML and CSS

## How It Works

1. The **main search page (`index.html`)** contains a form that submits a query directly to Google using the `q` parameter.
2. The **Images page (`images.html`)** also submits queries to Google Images with the same method.
3. The **Advanced Search page (`advanced.html`)** uses multiple input fields to generate a refined Google search URL using specific query parameters.
4. CSS is used to match Google's visual style, including centered layout and button styling.

## Setup

No installation is needed.

1. Clone or download the repository.
2. Open any of the HTML files in a browser:
   - `index.html`
   - `images.html`
   - `advanced.html`

All functionality works offline — search redirects will open real Google pages.

## Code Overview

Key files:

- `index.html` – Main search form (replicates google.com)
- `images.html` – Image search input (replicates google.com/imghp)
- `advanced.html` – Advanced search form
- `styles.css` – Styling for layout, form elements, and buttons
