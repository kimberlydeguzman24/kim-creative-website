# Kim Creative — website source

This is your complete, ready-to-deploy website: one `index.html` file plus an `assets` folder of images. No build step, no framework, no npm install — it's plain HTML/CSS/JS, so it deploys to Vercel as-is.

## What's included

- `index.html` — the entire site: home page (hero, about, services, work, offer ladder, contact), plus the Reels showcase, Platform Playbook (8 platforms), and Sample Data pages, all as sections in one file that show/hide based on the URL.
- `assets/` — your 12 real portfolio images (portrait, case studies, product concepts), already compressed for the web.

Everything from your Lovable build plan is already in here: the 4-tier offer ladder (ticket-stub styled, price-free), the persuasion pass (hero trust line, case-study "what this means for you" bridges, contact response time, footer line), and the 8-platform Playbook with click-to-expand strategy modals.

## Deploy to Vercel (no GitHub required, fastest way)

1. Go to [vercel.com](https://vercel.com) and sign in (or create a free account).
2. Go to **vercel.com/new**.
3. Look for **"Deploy without Git"** or drag-and-drop — Vercel calls this **Vercel Drop**. Drag this whole folder (or a zip of it) onto the page.
4. Vercel deploys it instantly and gives you a live URL like `kim-creative.vercel.app`.

## Deploy to Vercel via GitHub (recommended if you'll keep editing)

This path means every future update is one `git push` away from going live automatically.

1. Create a free [GitHub](https://github.com) account if you don't have one.
2. Create a new repository (e.g. `kim-creative-website`) and upload this folder's contents to it (GitHub's website lets you drag-and-drop files in — you don't need command-line Git for this).
3. Go to **vercel.com/new**, click **Import Git Repository**, and pick that repo.
4. Leave the build settings as default (Vercel will detect it's a static site) and click **Deploy**.
5. From then on, any time you edit `index.html` in GitHub and commit the change, Vercel redeploys automatically.

## Adding a custom domain

Once deployed, go to your project in Vercel → **Settings → Domains** → add the domain you own (e.g. `kimcreative.com`) and follow the DNS instructions Vercel gives you.

## What still needs your input before this is fully "real"

- **Reels page**: 4 phone mockups are placeholders. Replace the placeholder `<div class="reel-slot">` content with a real `<video>` or `<img>` tag per slot when you have footage — I can do this edit for you the moment you send the files.
- **Platform Playbook**: 8 cards use colored placeholder boxes (labeled "Your [Platform] visual here"). Same as above — send the images and I'll wire them in.
- **Contact button**: "Message me directly" currently just shows a preview-mode message. Tell me your real email, booking link, or form endpoint and I'll connect it.
- **Sample Data page**: intentionally fictional, already labeled "Illustrative data · Not client results" — leave as-is unless you want it swapped for a real reporting example.

## Editing this yourself later

Since it's plain HTML/CSS/JS in one file, you (or anyone) can open `index.html` in any text editor, search for the text you want to change, and edit it directly — no build tools needed. Save, re-upload (or `git push` if you used the GitHub path), and Vercel redeploys.
