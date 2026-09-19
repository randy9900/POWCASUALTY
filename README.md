# Hellship Casualty Roster — GitHub Pages package

This folder contains everything needed to host the roster on GitHub Pages.

## Setup (one-time, ~5 minutes)

1. **Create a GitHub account** if you don't have one: https://github.com/join

2. **Create a new repository**
   - Click the "+" in the top right → "New repository"
   - Name it anything, e.g. `hellship-roster`
   - Set it to **Public** (required for free GitHub Pages)
   - Click "Create repository"

3. **Upload the file**
   - On the new repo's page, click "uploading an existing file"
   - Drag in `index.html` from this folder
   - Click "Commit changes"

4. **Turn on GitHub Pages**
   - Go to the repo's **Settings** tab → **Pages** (left sidebar)
   - Under "Branch," select `main` and folder `/ (root)`, then **Save**
   - Wait 1–2 minutes; GitHub will show your live URL, something like:
     `https://yourusername.github.io/hellship-roster/`

5. **Use that URL**
   - Visit it to confirm the roster loads and search/filter work
   - Use it as the link in your Squarespace button, or as the `src` in an iframe if you want it embedded inline on a Squarespace page:
     ```html
     <iframe src="https://yourusername.github.io/hellship-roster/" style="width:100%;height:900px;border:none;"></iframe>
     ```

## Updating the roster later

If you ever get corrected or additional records, just repeat step 3 (upload a new `index.html` to the same repo, commit) — the live URL stays the same.

## Notes

- The file is fully self-contained (~4 MB) — no other files or setup needed.
- GitHub Pages hosting is free and has no visitor limits for a site this size.
- This is a **public** repository, so the file itself is visible to anyone who looks at the repo — same visibility as the live page itself.
