# MaRQuEs Lab website

This repository contains the source for the MaRQuEs Lab website: [josepmarques.github.io/MarquesLab](https://josepmarques.github.io/MarquesLab/). The site is published with GitHub Pages from the `main` branch.

## Updating the website

1. Open the file you want to change in the repository. Edit `index.html` for the homepage, or `group-history.html` for the group-history page.
2. Select **Edit** (the pencil icon) to make changes. For images or other files, choose **Add file → Upload files** and upload the file to the repository.
3. Preview the changes when possible, then select **Commit changes**. Commit directly to `main` to publish, or create a pull request and merge it into `main` after review.
4. GitHub Pages automatically builds and deploys changes from `main`. To check progress, open the repository’s **Actions** tab and look for the **pages build and deployment** workflow. Wait until it completes successfully.
5. Visit [the live website](https://josepmarques.github.io/MarquesLab/) and refresh the page. Deployment usually takes a few minutes.

## Editing images

Image filenames and paths in the HTML must match the uploaded files exactly, including capitalization and spaces. The homepage MRI animation uses the three `Pasted Image` PNG files referenced in `index.html`. The `group-history.html` page contains the group photo gallery.

## If an update does not appear

- Confirm the change was committed to `main` (or that its pull request was merged).
- Check **Actions** for a failed or still-running Pages deployment.
- Wait a few minutes, then refresh the page or try a private/incognito window to bypass cached content.
