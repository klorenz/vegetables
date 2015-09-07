# Vegetables changelog

## Vegetables 1.0.8

- handlebars replace the mustache render engine
- partial files handled, thanks to handlebars, with `partial-*.html` files in the template directory

## Vegetables 1.0.7

- configuration file: it is now possible to use wildcards in pageOptions documents name
- message added when the website is successfully deployed

## Vegetables 1.0.6

- layout support, e.g. layout-homepage.html, read from file tags or page options
- template - slideshow: transitions between slides enhanced
- assets files were not updated while serving

## Vegetables 1.0.5

- generation asynchronous process enhanced (and optimized) to be able to start the browser and live reload at the right moment

## Vegetables 1.0.4

- new options: scripts before and after to execute commands before and/or after generation
- serve mode: the Web site is automatically opened in browser
- live reload in preview mode, can be disabled in the configuration file

## Vegetables 1.0.3

- configuration: pageOptions available, i.e. customized tags par page
- template - slideshow: one-line code enhanced and transitions between slides
- frontmatter notation is supported, as yaml or json
- new CLI parameters: template, globaltitle, host and port
- configuration file supports YAML, with this priority: the file provided in CLI parameters < vegetables.yaml < vegetables.json

## Vegetables 1.0.2

- Non elegant logs removed
- Access address enhanced

## Vegetables 1.0.1

- svg format added to the media files
- default template enhancement: page title not displayed on small screens
- baseUri is now calculated as relative path

## Vegetables 1.0.0

First version, with:

- multiple formats template
- generate and serve features
- deploy on GitHub pages feature
- ...