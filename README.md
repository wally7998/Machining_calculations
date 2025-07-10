# Milling Cutting Parameters Calculator

A simple web-based calculator for milling cutting parameters (RPM and Feedrate) from SFM, IPT, Diameter, and Number of Teeth.

## Usage

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Enter values and click "Calculate" to see results.

## Embedding

You can host this on [GitHub Pages](https://pages.github.com/) and embed the calculator in SharePoint with an `<iframe>`:

```html
<iframe width="420" height="370" src="https://YOUR_GITHUB_USERNAME.github.io/milling-calculator/" frameborder="0"></iframe>
```

## Formulas

- **RPM:** (3.82 × SFM) / Diameter
- **Feedrate (IPM):** RPM × Number of Teeth × IPT
