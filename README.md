# Prince PDF - Claude Code Plugin

Convert HTML, Markdown, and XML documents to high-quality PDF using the [Prince](https://www.princexml.com) formatting engine.

## Installation

Install from the Claude Code plugin directory:

```
/plugin > Discover > prince-pdf
```

## Usage

Once installed, the `prince_convert` tool is available. For example:

> Convert https://example.com to PDF

> Make a PDF from this HTML: `<h1>Hello World</h1><p>This is a test.</p>`

> Convert this markdown to an A4 PDF with 20mm margins

## Parameters

| Parameter | Type | Description |
|-----------|------|-------------|
| `url` | string | URL of a document to fetch and convert |
| `content` | string | Inline HTML/Markdown/XML content to convert |
| `input_format` | string | `html`, `markdown`, `xml`, or `auto` (default: `auto`) |
| `style` | string | Additional CSS to apply |
| `page_size` | string | Page size, e.g. `A4`, `letter` |
| `page_margin` | string | Page margins, e.g. `20mm` |
| `javascript` | boolean | Enable JavaScript execution (default: false) |
| `pdf_profile` | string | PDF profile, e.g. `PDF/A-3b`, `PDF/UA-1` |
| `output_filename` | string | Output filename (default: `output.pdf`) |

Provide exactly one of `url` or `content`.

## Links

- [Prince Cloud](https://prince.cloud) - hosted MCP server
- [Prince documentation](https://www.princexml.com/doc/) - full Prince documentation
- [Privacy policy](https://prince.cloud/privacy/)
