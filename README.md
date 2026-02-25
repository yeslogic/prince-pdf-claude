# Prince PDF - Claude Code Plugin

Convert Markdown and HTML documents to high-quality PDF using the [Prince](https://www.princexml.com) formatting engine.

## Installation

Install from the Claude Code plugin directory:

```
/plugin > Discover > prince-pdf
```

## Usage

Once installed, three tools are available:

> Convert https://example.com to PDF

> Make a PDF from this HTML: `<h1>Hello World</h1><p>This is a test.</p>`

> Write a one-page resume and convert it to PDF

## Tools

| Tool | Input | Description |
|------|-------|-------------|
| `markdown_to_pdf` | `content` | Convert Markdown content to PDF |
| `html_to_pdf` | `content` | Convert HTML content to PDF |
| `url_to_pdf` | `url` | Fetch a URL and convert it to PDF |

**Common optional parameters:** `style`, `page_size`, `page_margin`, `javascript`, `pdf_profile`, `output_filename`

## Links

- [Prince Cloud](https://prince.cloud) - hosted MCP server
- [Prince documentation](https://www.princexml.com/doc/) - full Prince documentation
- [Privacy policy](https://prince.cloud/privacy/)
