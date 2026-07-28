# Quarto Website

This repository contains the source files for a website created with [Quarto](https://quarto.org/).

## Project structure

* `_quarto.yml` — configuration file
* `index.qmd` — site home page
* `$pages.qmd` — various site pages
* `styles.css` — custom styles
* `_site/` — generated output; not tracked

## Requirements

To build the website locally, install:

* Quarto
* Visual Studio Code
* the Quarto extension for Visual Studio Code

Verify that Quarto is installed:

```bash
quarto --version
```

## Preview the website

From the project directory, run:

```bash
quarto preview
```

Quarto will render the website, open it in a browser, and update the preview when source files change.

Press `Control + C` in the terminal to stop the preview server.

## Render the website

To generate the complete website:

```bash
quarto render
```

By default, the rendered site is written to the `_site` directory.

## Publishing

The website can be published using GitHub Pages by pushing the contents of 

## License

Add the project’s license information here.
