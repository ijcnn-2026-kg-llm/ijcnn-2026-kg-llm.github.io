# IJCNN 2026 Special Session Website

## Integrating Large Language Models and Knowledge Graphs

This is the source code for the Call for Papers website for the IJCNN 2026 Special Session.

### Structure

- `index.html`: The main HTML file containing the React application logic.
- `js/data.js`: **Edit this file to update content** (Organizers, Topics, Dates, etc.).
- `images/`: Directory to store images.

### How to Edit Content

1. Open `js/data.js` in a text editor.
2. Update the text inside the `window.siteData` object.
3. Save the file and refresh `index.html` in your browser.

### How to Edit Design

1. Open `index.html`.
2. The design uses Tailwind CSS classes.
3. The React components are defined inside the `<script type="text/babel">` tag.

### Deployment

This is a static website. You can deploy it using:

- **GitHub Pages**: Push this repository to GitHub and enable GitHub Pages in the settings.
- **Netlify/Vercel**: Drag and drop the folder or connect your Git repository.
- **Any Web Server**: Upload the files to your `public_html` or `www` directory.

### Note on Local Development

Since this site uses Babel Standalone to compile React in the browser, it should work fine when opening `index.html` directly in most browsers. However, if you encounter issues, try running a local server:

```bash
# Python 3
python3 -m http.server
```

Then open `http://localhost:8000`.
