# thequantdefense.com

Coming-soon page for **[TheQuantDefense](https://thequantdefense.com)** — Quantum solutions for defense & aerospace.

## 🛡️ Live Site

**[https://thequantdefense.com](https://thequantdefense.com)**

## About

This repository contains the source code for TheQuantDefense's coming-soon page with a waitlist signup. TheQuantDefense is [TheQuantAI](https://thequantai.in)'s defense & aerospace vertical, focused on:

- **Quantum-Safe Cryptography** — Post-quantum encryption for secure communications
- **Quantum Optimization** — Mission planning, logistics, and resource allocation
- **Quantum Sensing** — Enhanced detection and positioning capabilities

## Tech Stack

| Layer | Technology |
|-------|-----------|
| **Markup** | HTML5 |
| **Styling** | CSS3 (custom properties, responsive grid) |
| **Scripting** | Vanilla JavaScript |
| **Waitlist** | Formspree |
| **Analytics** | Plausible Analytics |
| **Hosting** | GitHub Pages |
| **CI/CD** | GitHub Actions (`deploy.yml`) |
| **DNS** | GoDaddy (A + CNAME records) |

## Development

```bash
# Clone
git clone https://github.com/TheQuantAI/thequantdefense.com.git
cd thequantdefense.com

# Serve locally
python -m http.server 8000
# Open http://localhost:8000
```

## Deployment

Pushes to `main` automatically deploy via GitHub Actions to GitHub Pages with the custom domain `thequantdefense.com`.

## Related Repos

| Repository | Description |
|------------|-------------|
| [quantsdk](https://github.com/TheQuantAI/quantsdk) | Core quantum computing SDK |
| [thequantai.in](https://github.com/TheQuantAI/thequantai.in) | TheQuantAI corporate website |
| [thequantcloud.com](https://github.com/TheQuantAI/thequantcloud.com) | TheQuantCloud product website |

## License

All rights reserved. © 2025 TheQuantAI.
