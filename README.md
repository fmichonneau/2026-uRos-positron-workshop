# 2026-uRos-positron-workshop

Slides for three workshops taught at uRos 2026:

1. Getting Started with Positron (`01-positron-getting-started.qmd`)
2. Getting Started with Posit Assistant (`02-positron-assistant.qmd`)
3. Developing chat-based data applications you can trust (`03-developing-chat-apps.qmd`)

The rendered slides are published with GitHub Pages at
<https://fmichonneau.github.io/2026-uRos-positron-workshop/>.
Exercise files are in
[2026-uRos-materials](https://github.com/fmichonneau/2026-uRos-materials).

## Building

Render the landing page and all three decks into `_site/`:

```bash
quarto render
```

Every push to `main` renders the site and deploys it through the workflow in
`.github/workflows/publish.yml`. In the repository settings, under
**Pages > Build and deployment > Source**, select **GitHub Actions**.
