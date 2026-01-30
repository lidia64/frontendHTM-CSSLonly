# RP Tumba Tech Club — Static Website by Lidia Uwineza

This repository contains a small, static multi-page website for the RP Tumba Tech Club. The site is built using plain HTML and a single external CSS file — no JavaScript or build tools are required.

## What’s included

- `index.html` — Home page
- `about.html` — About the club
- `services.html` — Activities / Services
- `contact.html` — Contact page (includes a contact form and map placeholder)
- `form.html` — Membership registration form
- `media.html` — Media gallery (images, audio, video, PDF)
- `styles.css` — Central stylesheet for the whole site
- `img/` — Media assets used by the site (photos, audio, video, PDFs, etc.)

## Quick preview

1. Open the project folder in your file explorer: `d:\25rp00738\front end\website\`
2. Double-click `index.html` to open it in your default browser.

Or from PowerShell in the folder:

    start index.html

(That will open the page in your default browser.)

## Notes about the contact form

- The membership form in `form.html` uses a simple `POST` action to `submit.html`. There is no server-side processing included with this static site — submitting the form will attempt to load the target page instead of sending an email.
- If you want real form handling without building a backend, consider a form service (Formspree, GetForm, Netlify Forms) or replace the form action with a `mailto:` link for simple email-based submissions.

## Styling

- All visual styling is in `styles.css`. The file contains beginner-friendly, easy-to-read rules for headers, navigation, the hero sections, media gallery, forms, and footer.
- If you edit `styles.css`, refresh your browser to see the changes.

## How to edit

- Use any text editor (VS Code recommended) to edit the HTML and CSS files.
- Keep file paths relative (e.g., `img/student.jpg`, `styles.css`) so pages remain portable.

## Contributing / Next steps

- Add a `submit.html` or a simple confirmation page if you want the form to show a friendly message after submit.
- Improve accessibility by adding `aria-` attributes and ensuring images have descriptive `alt` text.
- If you want responsive behavior reintroduced or additional layout changes, edit `styles.css` and test on different screen sizes.

## License

This project is provided as-is for learning and demonstration purposes. Feel free to reuse and adapt the files for your own club or project.

---

If you want, I can:
- Create a simple `submit.html` confirmation page now.
- Replace the form action with a third-party form service example.
- Clean up inline attributes in `media.html` (recommended) — tell me which option you prefer.
