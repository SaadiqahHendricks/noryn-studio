# NORYN STUDIO website starter

A responsive multi-page HTML/CSS/JavaScript starter for NORYN STUDIO.

## Files
- `index.html` — homepage
- `about.html` — studio story and approach
- `services.html` — service descriptions
- `work.html` — portfolio / concept projects
- `contact.html` — Netlify enquiry form
- `success.html` — form success page
- `assets/css/style.css` — styling
- `assets/js/main.js` — mobile navigation and reveal effects

## Preview locally
Open `index.html` in a browser. For a better local development experience, use VS Code with the Live Server extension.

## Before launch
1. Replace `YOUR_EMAIL_HERE` in the footer with the email address you want visitors to use.
2. Replace the Instagram `#` links with the correct profile URL.
3. Review all copy, photos and service descriptions.
4. The photos are remotely loaded from Unsplash and require an internet connection.
5. The logo is currently a text wordmark placeholder; replace it with the final NORYN logo when ready.

## Netlify enquiry form
The contact form is marked up for Netlify Forms (`data-netlify="true"`). To activate it:
1. Deploy the folder to Netlify.
2. In Netlify, open the site dashboard and confirm form detection under Forms.
3. Submit a test enquiry through the live site.
4. Configure form submission email notifications in Netlify to send to both founders' email addresses.
5. The form currently redirects to `success.html` after a successful submission.

Important: the static local preview will not submit enquiries. Netlify Forms only processes submissions after deployment to Netlify. Notification emails must be configured in the Netlify dashboard.

## Notes
- No database or build tools are required.
- Google Fonts and Unsplash photos are external resources.
- This is a starter build, not a final production launch. Check links, content, mobile layout, form notifications and domain settings before publishing.
