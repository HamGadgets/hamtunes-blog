HAMTUNES — ADMIN READY

Admin URL after deployment:
https://celadon-lebkuchen-2fbe9e.netlify.app/admin/

This version adds:
- Decap CMS admin
- GitHub-backed article editing
- Draft/published status
- News, Music, Lifestyle, Technology and Business categories
- Cover-image upload
- Markdown article editor
- Public article pages
- WhatsApp contact/share buttons

ONE-TIME SETUP
1. Create a GitHub repository for this project.
2. Upload all files from this package.
3. Open admin/config.yml and replace:
   YOUR_GITHUB_USERNAME/YOUR_GITHUB_REPOSITORY
   with your real repo, e.g. hamza123/hamtunes-blog
4. Connect that GitHub repository to your existing Netlify site.
5. In Netlify, configure GitHub authentication for Decap CMS.
6. Deploy.
7. Open /admin/ and log in.
8. Go to HamTunes Content → Articles → add or edit posts.

IMPORTANT
Do not put passwords, tokens, or private API keys in the site files.

Netlify's Git Gateway is deprecated for NEW configurations, so this build uses the Decap GitHub backend instead. Netlify Identity remains available for authentication, but Git Gateway is no longer the recommended new setup.

WhatsApp:
https://wa.me/256756308591

Social links are still placeholders (#) in index.html and can be replaced with your real profiles.
