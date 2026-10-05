# Aseem Baji academic website

This repository contains the source for Aseem Baji's academic website at `https://aseemwr10.github.io`.

## Publish with GitHub Pages (browser only)

1. Sign in at [github.com](https://github.com).
2. Select the **+** menu in the upper-right corner, then **New repository**.
3. Set the repository owner to `aseemwr10` and the repository name to exactly `aseemwr10.github.io`.
4. Set visibility to **Public**. Do not add a README, `.gitignore`, or license during creation because this package already includes a README.
5. Select **Create repository**.
6. On the empty repository page, select **uploading an existing file**.
7. Unzip this package on your computer. Open the resulting `aseemwr10.github.io` folder and drag everything inside it into the GitHub upload area. Upload the contents, not the enclosing folder. `index.html`, `research.html`, and the other files should appear at the repository root.
8. Enter a commit message such as `Launch academic website`, then select **Commit changes**.
9. Open **Settings** in the repository navigation, select **Pages** in the left sidebar, and find **Build and deployment**.
10. For **Source**, select **Deploy from a branch**. Choose the `main` branch and `/ (root)`, then select **Save**.
11. After GitHub completes the deployment, visit [https://aseemwr10.github.io](https://aseemwr10.github.io). Initial publication or later updates can take several minutes.

The site uses plain HTML and CSS and does not require a build step or paid hosting.

### If the site shows a 404

- Confirm that the repository is public and named exactly `aseemwr10.github.io`.
- Confirm that `index.html` is visible at the top level of the repository rather than inside another folder.
- Recheck **Settings → Pages** and verify that the source is `main` and `/ (root)`.
- Open the repository's **Actions** tab to see whether the Pages deployment is still running or failed.

## Updating content

- **Headshot:** Open `assets/aseem-baji-headshot.jpg` on GitHub, select the delete icon, commit the deletion, and upload the replacement with the exact same filename and location.
- **Job market paper:** Upload the finalized PDF under `files/`, then edit `index.html` and `research.html` to add the download link.
- **CV:** Replace `files/Aseem_Baji_CV.pdf` whenever the CV changes, preserving the filename so that the existing link continues to work.
- **Text:** Open an HTML file in GitHub, select the pencil icon, make the edit, and commit it. GitHub Pages republishes the site automatically.
