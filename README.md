# Securing Routes with Redux, React Router, and Higher Order Components

## Writing the Slides

This slide deck uses [reveal-ck](http://github.com/jedcn/reveal-ck)

After installing `reveal-ck`, run `reveal-ck generate` to create the slides folder

Serve the index.html your favorite way, for example: `open slides/index.html`

To edit the slides, run `reveal-ck server` and edit `slides.slim` and it will auto-reload!

## Deploying to Github Pages

```
git checkout gh-pages
git merge master
reveal-ck generate
git commit -m "Updating Github Pages"
git subtree push --prefix slides origin gh-pages
```
