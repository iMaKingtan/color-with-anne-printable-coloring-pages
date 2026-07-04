# Publishing checklist

Use the repository name:

```text
color-with-anne-printable-coloring-pages
```

The expected addresses are:

- Repository: `https://github.com/iMaKingtan/color-with-anne-printable-coloring-pages`
- GitHub Pages: `https://imakingtan.github.io/color-with-anne-printable-coloring-pages/`

## 1. Create the public repository

Create an empty public repository under `iMaKingtan`. Do not add a second
README, license, or `.gitignore` on GitHub because those files already exist
locally.

Suggested repository description:

> Curated previews and metadata for original printable coloring pages by Color with Anne.

Suggested topics:

```text
coloring-pages
printables
kids-activities
teacher-resources
capybara
github-pages
webp
```

Set the repository website field to:

```text
https://colorwithanne.com/
```

## 2. Push the project

After creating the empty repository, connect and push the local project:

```bash
git branch -M main
git remote add origin https://github.com/iMaKingtan/color-with-anne-printable-coloring-pages.git
git push -u origin main
```

Check the staged files before the first commit. There should be no PDF files in
the repository.

## 3. Enable GitHub Pages

In the repository, open **Settings > Pages** and choose:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/docs**

Save and wait for the Pages deployment to finish. Test the home page, all ten
preview images, the print guide, and the links to Color with Anne.

## 4. Complete the repository presentation

- Add `docs/assets/social-preview.webp` as the repository social preview under
  **Settings > General > Social preview**.
- Pin the repository on the `iMaKingtan` profile if it represents ongoing work.
- Add `https://colorwithanne.com/` to the GitHub profile website field.
- Keep the profile and repository descriptions natural; do not repeat keywords.

## 5. Maintain the project

- Add one complete original theme at a time.
- Refresh `New This Week` in both `README.md` and `docs/index.html` only when the
  linked website pages are genuinely new or substantially updated.
- Change the visible weekly date, JSON-LD `dateModified`, and sitemap `lastmod`
  in the same commit.
- Publish branded WebP previews only; keep high-quality PDFs on the official
  Color with Anne topic page.
- Give each scene a specific title, alt text, and catalog record.
- Use a clear commit message such as `Update weekly coloring page links for
  2026-07-11` so the maintenance history remains understandable.
- Check every external link after publishing.

This repository can help people and crawlers understand the Color with Anne
brand and its subject matter, but it should not be treated as a shortcut to
rankings. Its value comes from accurate ownership, useful resources, and
consistent long-term maintenance.
