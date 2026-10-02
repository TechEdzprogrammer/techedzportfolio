# Tech Edz portfolio website

A static HTML and CSS portfolio with responsive project previews. No dependencies or build step are required.

## Before publishing

1. Review the wording for each project and add measurable results or client testimonials only when you have permission.
2. The contact buttons use the Tech Edz Facebook Page. You can later replace them with a direct Messenger link, business email, or booking link.
3. Confirm that all five project links open as expected. The two client systems may require sign-in, and the Facebook posts may require a Facebook account.
4. Keep the `assets` folder beside `index.html` and `styles.css` when uploading or deploying the website.

## Preview locally

Open `index.html` in a browser, or run `python3 -m http.server 8000` inside this folder and open `http://localhost:8000`.

## Netlify

Drag this folder or the ZIP file into [Netlify Drop](https://app.netlify.com/drop). For a Git deployment, set the publish directory to `.` and leave the build command blank.

## Vercel

Drag the folder or ZIP file into [Vercel Drop](https://vercel.com/drop). It can deploy static files as-is without a build step. For a Git deployment, import the repository using the **Other** framework preset and check that `index.html` is in the served output directory.

No server processing is present. If you later want a contact form, connect it to a form provider or host-supported function before publishing the form; a plain static form cannot send inquiries by itself.
