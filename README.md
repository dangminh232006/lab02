# Lab 02 — HTML Page with Essential Elements

COS10026 Web Technology Project · Week 02 lab exercise.

The COS10026 unit outline, supplied as plain text, marked up as a web page that
follows the layout of the PDF version of the outline.

## Files

| File | Description |
|------|-------------|
| `outline.html` | The unit outline marked up in HTML |
| `images/swin_logo.png` | Official Swinburne logo (176 x 89 PNG) shown in the page header |
| `README.md` | This document |

## Steps Followed

1. Created this repository and copied the text of the unit outline into `outline.html`.
2. Added the document declaration, the `<html>` root with `<head>` and `<body>`,
   meta tags for charset, description, keywords and author, and a page title.
3. Validated the page, then marked up the content a little at a time,
   validating after each part (one commit per part).

## Elements Used

- **Document structure** — `<!DOCTYPE html>`, `<html lang="en">`, `<head>`, `<body>`
- **Metadata** — `<meta>` for charset, description, keywords and author, and `<title>`
- **Page layout** — `<header>`, `<main>` and `<footer>`
- **Headings** — one `<h1>` for the unit title and an `<h2>` for each section
- **Paragraphs and line breaks** — `<p>`, and `<br>` to keep the three lines of the title
- **Horizontal rules** — `<hr>` to separate the header and the footer from the content
- **Lists** — `<ol>` for the numbered learning outcomes, `<ul>` for the content topics
- **Table** — `<table border="1">` with `<thead>`, `<tbody>`, `<tr>`, `<th>` and `<td>` for the assessments
- **Image** — `<img>` with `alt`, `width` and `height`, linked by a relative path to the `images` folder
- **Anchors** — a link to the Swinburne website and a `mailto:` link to the student email
- **Phrase tag** — `<strong>` for the ULO codes
- **Special characters** — `&copy;` and `&amp;`
- **Comments** — `<!-- ... -->` explaining why each part is marked up the way it is

## Validation

`outline.html` was checked with the
[W3C Markup Validation Service](https://validator.w3.org/#validate_by_input)
after each step: no errors. The only warning is that the table `border` attribute is
obsolete; the Week 2 lecture notes the same and that CSS, taught from Week 4, styles tables better.
It stays so the table columns do not run together.

## How to View

Clone the repository:

```bash
git clone https://github.com/dangminh232006/lab02.git
```

Then open `outline.html` in a web browser, or open the folder in Visual Studio Code
and start **Live Server**.

## Acknowledgements

- Page text: COS10026 Unit Outline, Swinburne University of Technology, supplied with the lab.
- Logo: official Swinburne University of Technology logo,
  https://www.swinburne.edu.au/content/dam/media/brand/logo-long-full.svg
  (accessed 23 Sep 2026), saved as a PNG at its real size of 176 x 89 pixels. It replaces the
  smaller, blurred copy of the logo in the lab files.
- Generative AI: the HTML markup of `outline.html` and this README were generated with
  Claude (Anthropic, Claude Opus 5.5, September 2026), as noted in a comment in `outline.html`.

## Author

Bui Dang Minh — Swinburne University
