# Jiaqi Tong Personal Website

This folder contains a static personal academic website customized from Jiaqi Tong's Yale profile, Google Scholar link, ORCID, publication list, and local headshot.

The design keeps a similar academic profile layout to the reference site, while using a distinct Yale-blue research identity, profile fact rail, research snapshot, and timeline-style publication section.

## Edit Content

Most visible content is in `index.html`.

- Name/title/profile block: near the top of the `<aside class="profile-panel">`.
- Bio: inside the `<section id="bio">` block.
- Training cards: inside `<section id="education">`.
- Research areas: the section with `<h2>Research Areas</h2>`.
- Publications: inside `<section id="publications">`.
- Email and profile links: inside `<section id="contact">`.

## Photo

The current photo is:

`assets/jiaqi-tong-headshot.jpg`

To replace it, put a new image in `assets/` and update the `src` on the profile image in `index.html`.

## CV

The current CV file is:

`assets/jiaqi-tong-cv.pdf`

The main `Download CV` button in `index.html` links to that file.

## Preview

Open `index.html` directly in a browser and refresh after each edit. No build step is required.

## Publish

Simple publishing options:

- GitHub Pages: upload this folder to a repository and enable Pages.
- Netlify: drag this folder into the Netlify dashboard.
- Vercel: import a Git repository containing this folder.
