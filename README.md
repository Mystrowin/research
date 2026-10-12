# Mystrowin Research

Static research landing page for the planned `research.mystrowin.com` subdomain. Built with plain HTML and CSS; no build step or runtime dependencies.

## Preview

Open `index.html` directly in a browser, or serve this folder with any static file server.

## GitHub Pages and custom domain

1. Create a GitHub repository named `research` under the Mystrowin account and push this folder's contents to its root.
2. In repository Settings → Pages, publish from the `main` branch and `/ (root)`.
3. Add `research.mystrowin.com` as the custom domain in Pages. The included `CNAME` file carries the same hostname.
4. At the DNS provider for `mystrowin.com`, add a CNAME record: host `research`, target `mystrowin.github.io`.
5. After DNS resolves, enable HTTPS in Pages settings.

The site links to the two source records on Zenodo and the existing reproducibility repository. Both papers are identified as preprints; the first paper's measured results are bounded to its stated benchmark and configuration, and the second is described as a proposal without reported implementation or experimental results.
