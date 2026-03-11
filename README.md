# hazirbas.com

Personal portfolio website for [Caner Hazirbas](https://hazirbas.com) — Research Scientist at Meta AI working on on-device ML and GenAI.

## Stack

Single `index.html` file. No frameworks, no build step, no dependencies beyond two Google Fonts. Just HTML and CSS.

## Structure

```
.
├── index.html   # Entire site
├── CNAME        # Custom domain (hazirbas.com)
└── README.md
```

## Editing

Open `index.html` in any text editor. Sections are clearly commented:

- `<!-- Header -->` — name, role, bio, social links
- `<!-- Datasets -->` — dataset cards
- `<!-- Publications -->` — paper list
- `<!-- News -->` — news and talks

## Deployment

Hosted on GitHub Pages from the `master` branch. Pushes to `master` deploy automatically within ~1 minute.

```bash
git add index.html
git commit -m "Update portfolio"
git push origin master
```

## Credits

Built with the help of [Claude Sonnet 4.6](https://claude.ai) by Anthropic.

## Custom Domain

Served at [hazirbas.com](https://hazirbas.com) via the `CNAME` file and DNS A records pointing to GitHub Pages IPs:

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```
