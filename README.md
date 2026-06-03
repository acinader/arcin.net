# arcin.net

Personal site for Arthur Cinader Jr.

The site is plain HTML published with GitHub Pages from the
`docs/` directory to [arcin.net](https://arcin.net/).

This project is AI assisted.

## Structure

- `docs/index.html` - the public page
- `docs/CNAME` - the custom domain configuration
- `docs/.nojekyll` - disables Jekyll processing for GitHub Pages

## Development

There is no build step.

Validate the HTML:

```sh
/opt/homebrew/bin/tidy -quiet -errors docs/index.html
```

Preview locally:

```sh
python3 -m http.server 8765 --directory docs
```

Then open `http://127.0.0.1:8765/`.
