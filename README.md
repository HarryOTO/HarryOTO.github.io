# Harrison Prochnow | Portfolio

A static portfolio site. It uses plain HTML and CSS, so there is no build step.

## Publish on GitHub Pages

1. Create a new GitHub repository. Naming it `<your-username>.github.io` gives you the address `https://<your-username>.github.io`. Any other name works too and is served at `https://<your-username>.github.io/<repo-name>/`.
2. Upload everything in this folder to the repository root (`index.html` must be at the top level).
3. In the repository, open **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. Wait a minute or two. GitHub shows the live address at the top of the Pages settings.

## Edit content

- Text lives in `index.html`. Each project is one `<section class="block">`; copy an existing one to add another, and add a row to the project index near the top.
- Colors and type live at the top of `styles.css` (the `:root` block).
- Photos are in `assets/img/`. Keep the `width` and `height` attributes in `index.html` matched to the image so the page doesn't jump while loading.
