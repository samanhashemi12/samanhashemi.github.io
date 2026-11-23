# Saman Hashemi — Engineering Portfolio

A static, five-tab engineering portfolio designed for GitHub Pages. It uses only HTML, CSS, JavaScript, and locally stored images/videos.

## Website

- Open `index.html` in a browser to preview the website locally.
- Projects include real CAD images, a photo/video gallery, project notes, and selected SolidWorks downloads.
- The design includes Home, Projects, Experience, About, and Contact.
- All assets are referenced by relative paths, so the site works at `username.github.io` or `username.github.io/repo-name`.

## Publishing with GitHub Pages

1. Sign into GitHub (https://github.com).
2. Create a **public** repository named `YOUR_USERNAME.github.io`, replacing `YOUR_USERNAME` with the exact GitHub username.
3. Place **all files in this folder directly in the repository root** — do not upload the whole ZIP and do not nest the files under another folder. `index.html` must be at the top level.
4. Open repository **Settings > Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, then select branch `main` and folder `/(root)`, then **Save**.
6. Open `https://YOUR_USERNAME.github.io` once the site deploys. Check the Projects, Resume, and Contact links.

The `.nojekyll` file in this folder keeps the published site as ordinary static HTML/CSS/JS with no Jekyll processing.

## Updating later

Update/replace the changed files in the same repository on branch `main`. GitHub Pages automatically redeploys.

## Privacy and accuracy

The public website includes your supplied resume, email address, phone number, and LinkedIn profile. Project sheets and graphics labeled illustrative are for presentation, not verified mechanical drawings or evidence of fabrication/flight testing. Some SolidWorks assemblies may depend on additional external reference parts.

## Browser upload edition — RC car assembly note

The full SolidWorks RC-car assembly (`car.SLDASM`, about 27 MB) has been omitted from this edition so every file is under GitHub's **25 MiB browser-upload limit**. The website still contains the **RC car custom SolidWorks component parts** as a smaller ZIP, and all web pages, photographs, project sheets, resume, and other CAD downloads are intact.

To publish the original whole assembly as a direct site download, use the separate **full-with-assembly** package and GitHub Desktop instead of browser upload. The complete file is preserved there.
