# Attendance Notifier

A free, open-source, mobile-friendly web app for teachers. Mark a student
absent, then send the parent a WhatsApp message or SMS in one tap.

- No server, no sign-up, no SMS gateway fees
- Works in any phone or computer browser (nothing to install)
- Student data is stored only in the user's own browser (localStorage)
- Messages open in the teacher's own WhatsApp / SMS app (`wa.me` and `sms:` links); the teacher presses Send
- Editable message templates with placeholders: `{parent} {student} {class} {date} {school} {teacher}`
- Backup / restore via copy-paste (`name,parent,phone` per line)
- Monthly attendance report (present, absent and percentage per student)
- Holiday, festival and meeting messages for all parents

## Use it

Open `index.html` in a browser, or deploy the folder as a static site.

## Deploy free on GitHub Pages

1. Create a GitHub repository and upload these files.
2. Go to **Settings > Pages**, choose the `main` branch and root folder, and save.
3. Your app will be live at `https://<your-username>.github.io/<repo-name>/`.

Cloudflare Pages and Netlify also work: just point them at this folder (no build step).

## Privacy

Never commit real student names or phone numbers to this repository. Each
teacher's data lives only on their own device. If you add a shared backend
later, keep each school's data separate and follow India's DPDP Act.

## Ideas for contributions

- Multiple classes
- Telugu / Hindi message templates
- Optional sync (PocketBase or Supabase)
- Monthly attendance report

## Licence

MIT. See `LICENSE`.
