# inspector website

Inspector website

## Editing this website

This website is using `mkdocs` as a static website generator

### Installing mkdocs

```
pip install mkdocs
```

### Local server for testing

While editing the content (.md files), you can preview your changes by running the built-in webserver:
```
mkdocs serve
```

Preview your work on http://localhost:8000/

Note: when changing the mkdocs.yml file, you'll need to restart the built in webserver.

### Pushing changes

```
mkdocs gh-deploy
```

This will push a static html version of the website to the `inspector-php/website` repo,
in the special `gh-pages` branch, which github.io uses for displaying your website.

Don't forget to commit your source changes (to .yml and .md files) to the regular `master` branch.

### More info on mkdocs

Please visit [www.mkdocs.org](http://www.mkdocs.org) for more information.
