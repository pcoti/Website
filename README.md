# Peter Coti - Personal Website

A distinctive, professional digital resume website designed for MBA admissions committees and professional networking.

**Live site**: [pcoti.net](https://pcoti.net)

## Features

- **Dark/Light Theme**: Defaults to dark mode with smooth toggle animation
- **Responsive Design**: Mobile-first, works on all devices
- **Performance Optimized**: Single HTML file, minimal dependencies
- **Accessible**: WCAG 2.1 AA compliant, reduced motion support
- **Interactive**: Scroll progress, reveal animations, hover effects

## Design Philosophy

"Strategic Clarity" - A refined, editorial aesthetic that communicates analytical thinking and executive presence. Typography-forward design with generous whitespace and restrained color usage.

## Tech Stack

- Pure HTML5, CSS3, vanilla JavaScript
- No frameworks or build tools required
- Google Fonts (Fraunces + Outfit)
- Inline SVG icons

## Performance

- Target: Under 40KB HTML (excluding fonts)
- Lighthouse Performance: 95+
- First Contentful Paint: Under 1.5s

## Local Development

```bash
# Simply open index.html in a browser, or use a local server:
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Deployment

Hosted on GitHub Pages with custom domain (pcoti.net).

```bash
# Push changes to deploy
git add -A
git commit -m "Update site"
git push
```

## License

MIT License - See [LICENSE](LICENSE) for details.
