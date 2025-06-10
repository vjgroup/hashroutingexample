# Hash Routing Demo

This repository contains a minimal static website that demonstrates client-side routing using URL fragments.
It is designed for quick testing of how hash-based routes behave when embedded in other tools, such as
PowerPoint.

## Routes

- `#/` — Home
- `#/about` — About page
- `#/contact` — Contact page

## Usage

Open `index.html` in a browser or host it on any static server. The page listens for changes to
`window.location.hash` and swaps in a bit of placeholder content for each route so you can see the routing in action.

## Deploying to GitHub Pages

1. Push this repository to GitHub.
2. In the repository settings, enable **GitHub Pages** from the `main` branch.
3. After a few minutes your site will be available at:

```
https://<username>.github.io/<repository-name>/
```

You can then test the routes at:

```
https://<username>.github.io/<repository-name>/#/
https://<username>.github.io/<repository-name>/#/about
https://<username>.github.io/<repository-name>/#/contact
```


## Live Demo

A working copy of this site can be viewed at:

```
https://example.github.io/hashroutingexample/
```

The example site uses the same `index.html` found in this repository. Feel free
to replace `example` with your own GitHub user name if you fork the repo.

This simple setup should preserve the fragment portion of the URL when opened from
other applications.

