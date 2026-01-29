# Resume

My resume in [JSON Resume](https://jsonresume.org) format — an open-source standard for resumes.

## Usage

### Install the CLI

```bash
npm install -g resume-cli
```

### Validate

```bash
resume validate resume.json
```

### Preview locally

```bash
resume serve --theme elegant
```

This starts a local server where you can preview your resume in the browser.

### Export to PDF or HTML

```bash
resume export resume.pdf --theme elegant
resume export resume.html --theme elegant
```

## Themes

JSON Resume supports [50+ community themes](https://jsonresume.org/themes/). Some popular options:

- `elegant` - Clean and professional
- `even` - Modern and minimal
- `stackoverflow` - Developer-focused
- `kendall` - Simple and readable

Install a theme:

```bash
npm install -g jsonresume-theme-elegant
```

Then use it with `--theme elegant`.

## Publishing

You can publish your resume to the JSON Resume registry:

```bash
resume publish
```

This hosts it at `https://registry.jsonresume.org/[username]`.

Alternatively, host `resume.json` in a GitHub Gist and access it via:
`https://registry.jsonresume.org/[github-username]`

## Resources

- [JSON Resume Schema](https://jsonresume.org/schema/)
- [Getting Started Guide](https://docs.jsonresume.org/getting-started)
- [Theme Gallery](https://jsonresume.org/themes/)
