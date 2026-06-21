# Alliant Games

Source files for the [Alliant Games](https://alliantgames.com) website — our gaming community's marketing site, covering server info, donations, and help resources.

## About

Alliant Games is a Rust server community (with Origins/Rift game modes) run by Dusty Hansen Productions LLC. This site is the public-facing landing page for the community, linking out to Discord, the Perks Shop, the Help Center, and other Alliant.gg services.

## Tech

Static HTML site built with [Mobirise](https://mobirise.com/), using Bootstrap 5. No build step — pages are plain HTML/CSS/JS that can be edited directly or regenerated from the Mobirise project.

## Structure

```
.
├── index.html       # Home
├── about.html        # About Us
├── faq.html           # FAQ
├── donate.html      # Donate / VIP
├── rust.html          # Rust hub (Origins + Rift)
├── origins.html      # Origins server info
├── rift.html            # Rift server info (coming soon)
├── privacy.html      # Privacy Policy
├── tos.html             # Terms of Service
├── sitemap.xml
├── assets/               # Images, fonts, theme CSS/JS, vendor libraries
└── CNAME                # GitHub Pages custom domain config
```

## Hosting

Deployed via GitHub Pages with a custom domain configured through `CNAME` and DNS records on Namecheap.

## Editing

Most edits can be made directly to the HTML files. If using Mobirise to regenerate pages, re-export and diff against the existing files before committing, since the builder rewrites full sections.
