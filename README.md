# cardamora_cs
Coming Soon static web page for CARDAMORA

## Waitlist form setup (portable)

This project uses a static Formspree integration so it works on Cloudflare Pages and any other static host.

1. Create a form at `https://formspree.io/`.
2. Copy your Formspree form ID (example: `xzzabcde`).
3. In `index.html`, replace `YOUR_FORMSPREE_FORM_ID` in the form action URL.
4. Deploy.

No backend, database, or SMTP setup is required for collecting emails.
