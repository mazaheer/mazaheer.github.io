# Academic website

A traditional, minimal, multi-page HTML/CSS academic site for GitHub Pages.

## Publish
1. Open your repository `mazaheer.github.io` on GitHub.
2. Upload the HTML files and `style.css` into the **root** of the repository (not inside a subfolder). Do not upload just the ZIP file.
3. Under **Settings → Pages**, use **Deploy from a branch**, branch `main`, folder `/(root)`.
4. Visit `https://mazaheer.github.io` after deployment completes.

## Personalize
- Update the email address, profile picture and CV link in `index.html`.
- Replace provisional research and notes text with your final details.
- Put PDFs in a `files/` folder; then link to them using relative links like `files/cv.pdf`.
- To add a portrait image, put `profile.jpg` under `images/`, then replace the `<div class="portrait">...</div>` placeholder with `<img class="portrait" src="images/profile.jpg" alt="Portrait of Muhammad Atif Zaheer">`.
- Change the font in the `body { font-family: ... }` rule in `style.css`.

No Jekyll, JavaScript, or external dependencies are required.
