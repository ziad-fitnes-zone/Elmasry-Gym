# Elmasr'y Gym — Website

A fully rebranded gym website (black & gold theme) built on a responsive Bootstrap 5 template, ready to publish on **GitHub Pages**.

## What's in this project

- `index.html` — Home page (hero, about, classes, trainers, testimonials)
- `about.html` — About / mission, vision & goals
- `course.html` — Membership & classes
- `team.html` — Trainers
- `testimonial.html` — Testimonials
- `contact.html` — Contact form + map
- `404.html` — Custom 404 page
- `css/`, `js/`, `lib/`, `img/` — Styles, scripts, third-party libraries, and images

All paths are relative, so the site works whether it's hosted at the root of a domain (`username.github.io`) or in a subpath (`username.github.io/repo-name`).

## Deploying to GitHub Pages

1. Create a new GitHub repository (public, unless you have GitHub Pro/Team for a private Pages site).
2. Push the contents of this folder to the repository's default branch (e.g. `main`):
   ```bash
   git init
   git add .
   git commit -m "Elmasr'y Gym website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Set **Branch** to `main` and folder to `/ (root)`, then **Save**.
6. Wait a minute or two — GitHub will publish the site at:
   `https://<your-username>.github.io/<your-repo>/`

The `.nojekyll` file in this project tells GitHub Pages to skip Jekyll processing, so folders like `css/`, `js/`, and `lib/` (which start with lowercase letters, not underscores) will be served as-is without any build step.

## Notes

- Contact form on `contact.html` is front-end only (no backend). To make it functional, connect it to a form service (e.g. Formspree, EmailJS) or your own backend.
- The Google Map embed on the contact page points to Maadi, Cairo — update the `src` in the `<iframe>` if your gym is in a different location.
- Update the phone (`+20 100 123 4567`), email (`info@elmasrygym.com`), and address throughout the site once real contact details are available.
- This template's license requires the "Designed By HTML Codex" credit link in the footer to remain unless the Pro version is purchased (see `LICENSE.txt`).
