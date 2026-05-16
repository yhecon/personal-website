# Personal Website

Academic personal website for Yuhang He.

## Local Preview

Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy With Netlify

1. Push this repository to GitHub.
2. In Netlify, choose **Add new site** -> **Import an existing project**.
3. Select this GitHub repository.
4. Use these settings:
   - Build command: leave blank
   - Publish directory: `.`
5. Add your custom domain in Netlify after the first deploy succeeds.

## Next Edits

- Replace placeholder bio, affiliation, and email.
- Add `assets/cv.pdf`.
- Add a profile photo.
- Replace placeholder research entries with real papers.
