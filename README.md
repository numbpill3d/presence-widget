# presence

A tiny, monochrome presence widget for personal websites.

The landing page is a static demo. The interactive terminal is intentionally local; wire the same UI to your presence API when the service is running.

## GitHub Pages

This folder is ready to publish as a static site. Create a repository, push the folder contents, then enable Pages from the repository's **Settings → Pages** using the default branch and `/ (root)`.

## Widget contract

The intended embed is:

```html
<script src="https://your-domain.example/presence.js" data-user="your-handle"></script>
```

The script should render a readable fallback such as `your-handle is soldering something questionable` and update it from the presence endpoint.
