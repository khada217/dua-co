# Qur'anic Duas

This repository is a small single-page web app that displays a curated list of short Qur'anic duas (supplications). This modernization updates the project to remove jQuery, improve accessibility and search UX, normalize the dua data, and add contributing documentation.

What's changed in the `modernize/remove-jquery-enhance-ui` branch

- Remove jQuery dependency and rewrite UI logic in vanilla JavaScript (accessible, debounced search).
- Improve accessibility: labeled search input, keyboard-friendly components, visible focus outlines, and aria-live result counts.
- Keep Onsen UI CSS for styling but avoid relying on jQuery; Onsen's JS is still included for compatibility.
- Normalize `duas.json`: each entry now has an `id` (slug) and a `source` field (empty by default).
- Add `README.md` and `CONTRIBUTING.md` with instructions for contributors.

Local testing

1. Serve the directory (some browser features require a server):

```bash
# Quick test using Python 3
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

2. Open the app in a modern browser. Use the search box to filter duas. Clear to restore the full list.

Contributing

If you'd like to add or edit duas, see CONTRIBUTING.md for the recommended format.
