# Zeyna website

A one-page showcase for Zeyna handmade pearl and bead jewelry.

## What's in this folder

- `index.html` is the whole website.
- `images/` holds the jewelry photos, the logo, the browser icon and the picture Facebook shows when someone shares your link.

Keep the two together. The page looks for its photos inside the `images` folder.

## Put it online with GitHub Pages

1. Sign in to GitHub and create a new repository (for example `zeyna`). Make it **Public**.
2. On the repository page, choose **Add file > Upload files**.
3. Drag in `index.html`, `README.md` and the whole `images` folder, then click **Commit changes**.
4. Go to **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, pick the **main** branch and the **/(root)** folder, then **Save**.
5. After a minute or two your site is live at `https://YOUR-USERNAME.github.io/zeyna/`.

## Social links

Every Instagram button and icon opens https://www.instagram.com/zeynaboutique5/

Every Facebook button and icon opens https://www.facebook.com/profile.php?id=61595839025436

To change either one later, open `index.html` on GitHub, click the pencil icon, and use your browser's Find (Ctrl+F or Cmd+F) to locate and replace the old address everywhere it appears.

## Make shared links look good on Facebook

Once the site is live, find `og:image` near the top of `index.html` and change it to the full address:

```html
<meta property="og:image" content="https://YOUR-USERNAME.github.io/zeyna/images/og-image.jpg">
```

Add the website address to the bio on your Instagram and Facebook pages so visitors can find it.

## Add a new piece later

1. Upload the photo into the `images` folder.
2. In `index.html`, find the `Featured pieces` section and copy one `<li class="piece" ...>` block.
3. Change the photo file name, the name in `<h3>`, and the short description.
4. Set `data-cat` to `bracelets`, `necklaces` or `earrings` so the filter buttons know where it belongs.

The Rings card says "Photos coming soon". When you have ring photos, it can become a photo card like the others, with a Rings filter button.
