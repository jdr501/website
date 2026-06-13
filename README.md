# Academic Website Sections

This repository contains standalone static pages for Danusha Rajapaksa's academic website sections.

## Pages

- `/research/` — publications, working papers, and work in progress
- `/projects/` — thematic research projects and teaching tools
- `/teaching/` — teaching profile, courses, pedagogy, and FinTech/blockchain teaching lab

## Recommended workflow

1. Create a public GitHub repository.
2. Copy these files into the repository.
3. Push from VS Code.
4. In GitHub, go to **Settings → Pages**.
5. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. After GitHub Pages is live, embed the URLs in Google Sites.

Example URLs after publishing:

```text
https://YOUR-USERNAME.github.io/YOUR-REPO/research/
https://YOUR-USERNAME.github.io/YOUR-REPO/projects/
https://YOUR-USERNAME.github.io/YOUR-REPO/teaching/
```

## Editing

- Edit page content inside each `index.html` file.
- Edit shared styling in `assets/style.css`.
- Replace placeholder `href="#"` links with real PDF, demo, GitHub, or teaching-note links.

## Notes for Google Sites

In Google Sites, use:

**Insert → Embed → By URL**

Then paste the relevant GitHub Pages URL. Resize the embed box height after insertion.
