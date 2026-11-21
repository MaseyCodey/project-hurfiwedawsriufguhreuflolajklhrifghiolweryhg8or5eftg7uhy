# Lola’s Butterfly Effect Foundation — Coming Soon

A complete, ready-to-upload website featuring the foundation’s supplied logo and its yellow and orange colors. It adapts to phones, tablets, and desktop screens.

## Open it on your computer

1. Extract the ZIP first.
2. Open `index.html` in your browser.

Everything needed to display the page is included. There is no installation, build command, external font, or JavaScript dependency.

## Upload to GitHub Pages

1. Create or open the GitHub repository you want to use for this website.
2. Extract this ZIP on your computer.
3. On the repository’s **Code** tab, choose **Add file → Upload files**. A new empty repository may show an **uploading an existing file** link instead.
4. Upload the extracted `index.html`, `styles.css`, `assets` folder, `.nojekyll`, and `README.md` to the repository’s top level. Keep the images inside the `assets` folder. Commit the upload to your chosen branch, usually `main`.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Choose the branch containing the website, usually **main**, and the **/(root)** folder, then click **Save**.
8. Wait for GitHub to finish publishing. The **Pages** screen will show your website address.

**Important:** Upload the extracted files, not the ZIP file. `index.html` must be directly in the publishing folder, not inside an extra enclosing folder. If Windows hides `.nojekyll`, the page can still publish; include the file when available.

GitHub’s official publishing instructions:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Page content and search/social metadata |
| `styles.css` | Layout, brand colors, and responsive styling |
| `assets/logo.webp` | Optimized original foundation logo |
| `assets/logo.png` | Original logo fallback |
| `assets/favicon.png` | Browser tab icon |
| `assets/apple-touch-icon.png` | Mobile home-screen icon |
| `.nojekyll` | Indicates the files are ready to serve directly |

## Edit the page later

- **Wording:** edit `index.html`.
- **Colors:** edit the custom properties at the top of `styles.css`.
- **Logo:** replace the files in `assets`, keeping their names, or update the image paths in `index.html`.

Brand colors sampled from the original logo:

| Color | Hex |
| --- | --- |
| Yellow | `#FAE03A` |
| Orange | `#F35A29` |
| Pale yellow | `#FDF8AB` |

The supplied logo artwork is preserved. Decorative butterflies are separate SVG elements. The page has a brief entrance animation that respects the visitor’s reduced-motion preference; nothing requires interaction to view the content. There is no email collection, donation form, analytics, or invented launch date.
