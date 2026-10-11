# Greythorn Lane Barbers — Website Handover

You own everything in this folder. No account of ours is involved; nothing stops working if we disappear.

## 1. What's in the folder
- `index.html` — the whole site
- `style.css` — colours, fonts, spacing
- `images/` — your photos and logo
- This guide

## 2. Put it online for free (about 15 minutes)
Pick one. Both are free for a site like this.

**Cloudflare Pages**
1. Create a free account at pages.cloudflare.com.
2. "Create a project" → "Upload assets" → drag this whole folder in.
3. You get an address like `yourname.pages.dev`. The site is live.

**GitHub Pages**
1. Create a free account at github.com, create a repository named `greythorn-lane-barbers`.
2. Upload the folder contents. Settings → Pages → Source: main branch.
3. Address: `yourname.github.io/greythorn-lane-barbers`.

## 3. Use your own domain
1. Buy a domain (e.g. from VentraIP or Namecheap, about A$15–30 a year).
2. In Cloudflare Pages or GitHub Pages, open "Custom domains" and add it.
3. They show you one or two DNS records to add at your domain seller. Add them; it works within an hour.

## 4. Edit text and images
- Open `index.html` in any text editor (Notepad works). The text you see on the site is the text in the file. Change it, save, re-upload.
- To swap a photo: put the new file in `images/` with the same name as the old one.
- Keep images under 500 KB each so the page stays fast.

## 5. The contact form
Enquiries go to **[待客户提供：表单收件邮箱]**. The form uses Web3Forms; the free plan allows [待客户提供：以 web3forms.com 当前免费额度为准]. To change the email, open `index.html`, find `<!-- form_marker -->` and replace the address. (The access key in the line below it is currently the placeholder `{{FORM_ACCESS_KEY}}`; get a key at web3forms.com using the recipient email and paste it there. Until then the form does not deliver.)

## 6. Google (optional)
To appear in Google search results: search.google.com/search-console → add your address → verify with the HTML tag method (paste the tag into `index.html` where marked `<!-- search-console -->`). This is your account; we don't need access.

## 7. Revisions
Two rounds of revisions within the agreed scope are included. Send the changes as a list; you'll get the updated files back.
