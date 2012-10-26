# HTML-DOC

Generate HTML documentation from embedded Markdown comments

## Usage

```
npm install html-doc -g
```

```
Usage: html-doc [options]

Options:

  -h, --help           output usage information
  -V, --version        output the version number
  -h, --header <path>  Override the default header in which to wrap output html
  -f, --footer <path>  Override the default footer in which to wrap output html

  Use over stdio:

    $ html-doc < source.html > output.html
```

### Custom header/footer

```
html-doc -h path/to/header.html -f /path/to/footer.html < source.html > output/html