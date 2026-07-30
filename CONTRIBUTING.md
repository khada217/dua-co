# Contributing

Thank you for considering contributing dua entries or improvements.

Adding or editing duas.json

- File: `duas.json` contains an array of dua objects.
- Each dua should be an object with these fields:
  - `id` (string): unique slug identifier, e.g. `dua-seeking-good-this-world-hereafter`
  - `title` (string): short English title
  - `arabic` (string): Arabic text
  - `transliteration` (string): Latin-script transliteration
  - `translation` (string): English translation
  - `source` (string): optional reference (Qur'an or hadith), leave empty if unknown

Please keep formatting consistent and avoid trailing commas. After editing, run a quick local test by serving the repo and opening the app in a browser.

Pull requests

- Create a branch off `main` or the default branch.
- Name your branch descriptively, e.g. `feat/add-dua-xyz`.
- Include a short description in the PR explaining the change and any sources for the dua.

Code style

- The app targets modern evergreen browsers and uses vanilla JavaScript. Keep changes simple and accessible.
