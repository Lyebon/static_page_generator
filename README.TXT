# Static Site Generator

A custom static site generator built in Python.

The generator takes Markdown files as input, converts their content into HTML, and combines it with a reusable HTML template to produce a static website.

## Features

* Convert Markdown content into HTML
* Generate pages recursively from a content directory
* Reuse a customizable HTML template
* Support headings, paragraphs, lists, quotes, and code blocks
* Copy static assets such as CSS and images
* Generate a deployable static site
* Includes unit tests for the core functionality

## How it works

The generator follows a simple pipeline:

```text
Markdown content
       ↓
Markdown parsing
       ↓
HTML node generation
       ↓
HTML template
       ↓
Static website
```

The generated pages are written to the `docs/` directory, making the output suitable for static hosting.

This project was built as an exercise in understanding how static site generators work internally, including Markdown parsing, HTML generation, templates, file handling, and recursive directory processing.
