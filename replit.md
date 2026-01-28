# Glazed & Grounded - Yoga Website

## Overview
A static single-page website for "Glazed & Grounded" yoga classes by Timothy Maguire. The site displays upcoming classes, contact form, waiver links, and social media connections.

## Project Structure
- `index.html` - Main webpage with all content and inline CSS
- `assets/` - Images including RYT200 badge and decorative graphics
- `CNAME` - Custom domain configuration

## Technology
- Pure HTML/CSS static site
- Contact form handled by Formspree (external service)
- Python HTTP server for local development

## Running Locally
The project uses Python's built-in HTTP server on port 5000:
```
python -m http.server 5000 --bind 0.0.0.0
```

## Deployment
Configured as a static site deployment serving files from the root directory.

## External Services
- Formspree for contact form submissions
- Google Forms for waiver signing
