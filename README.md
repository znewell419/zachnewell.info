Personal portfolio website for Zachary Newell.

🌐 Live Site: https://zachnewell.info

## Overview

This repository contains the source code for my personal website. The site is now trucking-first: I am earning my Class A CDL at Suburban Truck Driver Training School in Romulus, MI, and the site follows that training.

My dad was a truck driver. The trucking page tells that story and tracks my progress through CDL school, from classroom and yard work to road training and the state test.

My IT and homelab work is still on the site, now as a hobby section. I am not actively looking for an IT job. The resume page is past work history.

Current status, as of November 14, 2026: CDL-A candidate in training, not licensed yet. Pre-trip instructor retest passed November 9, 2026, 90/98. Road training started the week of November 9, 2026. State test date is not set yet.

The website is built as a lightweight static site and is self-hosted on my own Linux server.

## Features

- Trucking page with training timeline and From the Yard photos
- About page
- Homelab page, formerly Projects
- Resume page and resume download
- Contact page
- Search engine optimization files (`robots.txt` and `sitemap.xml`)
- Responsive personal website
- Self-hosted deployment

## Technologies Used

- HTML5
- CSS3
- Git
- GitHub
- Caddy Web Server
- Arch Linux
- Cloudflare DNS

## Repository Structure

```text
.
├── assets/
│   ├── css/
│   │   └── style.css
│   └── images/
│       ├── behind-the-wheel.jpg
│       ├── yard-1.jpg
│       ├── yard-2.jpg
│       └── zachary-newell.jpeg
├── downloads/
│   └── Zachary-Newell-Resume-2026-2-pages.pdf
├── about.html
├── contact.html
├── favicon.svg
├── index.html
├── projects.html
├── resume.html
├── robots.txt
├── sitemap.xml
└── trucking.html
```

## Deployment

The website is hosted on a self-managed Arch Linux server. Live files are served from `/srv/web/portfolio/`.

Deployment workflow:

1. Website changes are committed to GitHub
2. Changes are pulled onto the server
3. Caddy serves the static website files

## Future Improvements

- Keep the trucking timeline current through the state test
- Update the resume once licensed
- Add additional homelab projects
- Improve animations and styling
- Add blog functionality
- Add analytics
- Continue improving accessibility
- Expand project documentation

## Related Projects

- [Linux Server Infrastructure](https://github.com/znewell419/linux-server-infrastructure) — documentation for the self-hosted Linux server, Docker services, monitoring stack, security configuration, and system administration work supporting this website.

## Author

Zachary Newell
