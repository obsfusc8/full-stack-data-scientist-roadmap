# Full-Stack Data Scientist Roadmap

An open-access, practical curriculum for becoming a full-stack data scientist and AI systems architect.

The roadmap connects mathematical foundations to software engineering, data systems, machine learning, deep learning, LLMs, production MLOps, AI safety, and two optional specialization tracks: quantitative finance and genomic AI.

## Roadmap at a glance

1. **Foundations** : linear algebra, calculus, probability, statistics, and optimization
2. **Systems & software engineering** : algorithms, software construction, databases, and distributed systems
3. **Modeling & AI** : classical machine learning, deep learning, NLP, vision, and language modeling
4. **Production** : MLOps, efficient inference, systems design, governance, and safety
5. **Frontiers** : quantitative finance and AI for science / genomics

## Features

- 45 curated courses and learning resources
- MIT OpenCourseWare and Stanford course material
- Searchable curriculum with school and topic filters
- Local progress tracking with browser storage
- Light and dark themes
- Responsive block-diagram roadmap
- No build step or framework required

## Use the roadmap

Open [`index.html`](./index.html) in a browser, or visit the hosted GitHub Pages site:

**https://obsfusc8.github.io/full-stack-data-scientist-roadmap/**

Progress is saved locally in your browser. External resources link directly to the original MIT, Stanford, and research portals.

## Run locally

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Hosting

The site is a static GitHub Pages deployment. The repository root contains `index.html`, so no build pipeline is required.

## Security notes

- External course links use HTTPS where available.
- New-tab links use `rel="noopener noreferrer"` where applicable.
- The page does not collect data or call a backend.
- Progress is limited to course completion state in `localStorage`.

## License

The roadmap page and accompanying documentation are provided for educational use. Course names, links, and materials remain the property of their respective institutions and authors.
