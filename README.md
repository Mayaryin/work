# work

A repository for hosting PDF files via GitHub Pages.

## Viewing the files

Once GitHub Pages is enabled, the files are accessible at:
`https://mayaryin.github.io/work/`

## How to enable GitHub Pages

1. Go to **Settings** → **Pages** in this repository.
2. Under **Source**, select the branch (e.g. `main`) and folder (`/ (root)`).
3. Click **Save**.

GitHub Pages will then serve this repository at `https://mayaryin.github.io/work/`.

## How to add PDF files

1. Add your `.pdf` files to the root of this repository (or a subfolder).
2. Open `index.html` and add a link for each file inside the `<ul>` list:
   ```html
   <li><a href="your-file.pdf">Your File Title</a></li>
   ```
3. Commit and push. The file will be available at `https://mayaryin.github.io/work/your-file.pdf`.