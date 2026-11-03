# SCULPT ($SCULPT)

Every masterpiece starts as a block. · https://x.com/UseSculpt

Landing page for SCULPT, the AI-powered marble sculpting and token creation launchpad on Solana. One static page: no build step, no dependencies.

## Files

- `index.html` – the whole site (HTML, CSS and JS in one file)
- `logo.png` – favicon and social preview image
- `vercel.json` – Vercel settings

## Deploy on Vercel

1. Push these files to the root of a GitHub repo.
2. In Vercel, click **Add New → Project** and import the repo.
3. Framework preset: **Other**. Leave the build command and output directory empty.
4. Deploy.

## At launch

Edit the `CONFIG` block at the top of the script in `index.html`:

```js
const CONFIG = {
  xUrl: "https://x.com/UseSculpt",
  buyUrl: "",     // DEX link
  chartUrl: "",   // chart link
  contract: ""    // $SCULPT contract address
};
```
