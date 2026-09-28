# Chenab Navalkha — personal website

A plain HTML website. No build step, no dependencies. GitHub Pages serves the
files exactly as they are, so editing is as simple as changing text in a file.

## Files

- `index.html` — the About / homepage
- `research.html` — Research overview
- `projects.html` — Project cards
- `publications.html` — Publication list
- `style.css` — all the styling (you rarely need to touch this)
- `prof_pic.jpeg` — your profile photo (add this file yourself)

## Putting it online (one-time setup)

1. Create (or reuse) a repository named `chenabnavalkha.github.io`.
2. Upload all of these files to the top level of that repo
   (drag-and-drop works at github.com → "Add file" → "Upload files").
3. Add your photo as `prof_pic.jpeg` (or change the filename in `index.html`).
4. In the repo: **Settings → Pages → Source → Deploy from a branch → main / root.**
5. Wait a minute, then visit `https://chenabnavalkha.github.io/`.

## Editing day-to-day (all in the browser)

1. Go to the file you want to change on github.com, e.g. `research.html`.
2. Click the pencil icon (✏️) at the top right.
3. Edit the text between the `<p> ... </p>` tags. Everything you'd want to
   change is plain English between those tags.
4. Scroll down, write a short note, click **Commit changes**.
5. Your live site updates in about a minute.

### The few HTML things you'll use

- A paragraph:        `<p>Your text here.</p>`
- Italic (titles):    `<em>Grounding Financialization</em>`
- Bold:               `<strong>your name</strong>`
- A link:             `<a href="https://example.com">link text</a>`
- A section heading:  `<h2>Heading</h2>`
- An em dash:         `&mdash;`   (—)
- Curly quotes:       `&ldquo;` and `&rdquo;`  (" ")

### Adding a new publication

Copy one existing `<p class="pub">...</p>` line, paste it where you want it,
and edit the text. Keep the `<span class="year">2026</span>` part for the year.

### Adding a new project card

Copy a whole `<div class="card"> ... </div>` block in `projects.html`,
paste it, and edit.

### Changing the accent color

Open `style.css`, find the line `--accent: #7a2e2e;` near the top, and replace
the color code. That single change recolors links and headings site-wide.

## Note

The navigation menu appears at the top of each `.html` file. If you add or
rename a page, update the `<nav>` block in each file so the menu stays in sync.
