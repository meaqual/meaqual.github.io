# Yuheng Huang — academic homepage

The site is static HTML and CSS. To preview, run `python3 -m http.server 8000` from this directory and visit `http://localhost:8000`.

## Publish on GitHub Pages

1. Create the public repository `meaqual/meaqual.github.io`.
2. Commit and push the contents of this directory, including `.nojekyll` and the `papers/` folder, to the repository root on `main`.
3. In the repository, go to **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, select **main** and **/(root)**, then save.
4. Check the deployment under **Actions**, then open https://meaqual.github.io/.

Edit `index.html` to update biography, education, and publications. Keep PDFs in `papers/` and use relative URLs. The portrait uses the public GitHub avatar.

## Set a homepage-only portrait

Upload a square image such as `images/avatar.jpg` to this repository. In `style.css`, change `--portrait-image` to `url('images/avatar.jpg')` and commit to `main`. This changes only the portrait on the homepage.
