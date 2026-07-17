# To-Do List

A simple, dependency-free to-do list web app built with vanilla HTML, CSS, and JavaScript. Your tasks are saved in the browser so they persist across page reloads.

## Features

- ✅ Add tasks (type and press **Enter** or click **Add**)
- ☑️ Mark tasks complete with a checkbox (adds a strikethrough)
- 🗑️ Delete individual tasks
- 🧹 Clear all completed tasks at once
- 🔢 Live counter of remaining tasks
- 💾 Persistence via `localStorage` — tasks survive a refresh
- 📱 Responsive, single-file, no build step or dependencies

## Usage

Just open `index.html` in any modern browser — that's it.

Or serve it over a local HTTP server:

```bash
# Python 3
python -m http.server 4126
```

Then visit **http://localhost:4126/**.

## Project structure

```
.
├── index.html   # The entire app — markup, styles, and logic
└── README.md
```

## Tech

- HTML5
- CSS3 (no framework)
- Vanilla JavaScript (no dependencies)

## License

MIT
