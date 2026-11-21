# anarcho-nihilism.github.io

## How to write a new text

1. On github.com open the folder `blog/_posts/`.
2. Click "Add file", then "Create new file".
3. Name the file `YYYY-MM-DD-some-name.md`, for example `2026-11-21-my-text.md`.
   The date sets the order of texts. The name becomes part of the URL.
4. Write the title as the first line: `# My title`. Then write the text.
5. Use the "Preview" tab to check it.
6. Click "Commit changes". The site updates in about a minute.

To edit a text, open its file, click the pencil icon, change it, commit.

## How to write a static page

Static pages (like the manifest) live in the folder `pages/`.

1. On github.com open the folder `pages/`.
2. Click "Add file", then "Create new file".
3. Name the file `some-name.md`. The page will be at `/some-name/`.
   For example, `pages/manifest.md` is at `/manifest/`.
4. Write the title as the first line: `# My title`. Then write the text.
5. Check it in "Preview", then click "Commit changes".

## How to add an image

Images live in the folder `assets/images/`.

1. On github.com open the folder `assets/images/`.
2. Click "Add file", then "Upload files". Choose the image and commit.
3. In your text, write:

   ```markdown
   ![What is in the image](/assets/images/my-image.jpg)
   ```

   The path must start with `/assets/images/`. Then it works both in
   "Preview" and on the site.
4. Check it in "Preview", then commit.

Tips:

- Name files with small Latin letters, digits and `-`. No spaces.
  Good: `2026-11-flag.jpg`. Bad: `My Photo 1.JPG`.
- Do not drag an image into the editor. GitHub then keeps it on its own
  server, not in this repo. Always upload into `assets/images/`.
- Phone photos can hide the place where they were taken (GPS).
  Remove this before upload. A simple way: take a screenshot of the
  photo and upload the screenshot.
- Keep images small: about 1500 px wide and under 500 KB is enough.
- Write a short description inside `[ ]`. It is shown if the image
  does not load, and blind readers hear it.
- Any size is fine on the site. Big images shrink to fit the screen.
  Small images keep their real size.

Markdown files in the root folder are not published if their name
starts with a capital letter (like `README.md`). Put pages in `pages/`.
