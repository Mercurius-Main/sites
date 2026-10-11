# Doncaster Road Cleaning Co. — Website Handover

The site files are yours to edit and host. Photographs are supplied Pexels stock illustrations, subject to their original licence; see `images/SOURCES.md`. This is a fictional demonstration business. No form-service account or working delivery key is included.

## 1. What's in the folder
- `index.html` — the whole site, including editable services, prices, hours and contact details
- `style.css` — colours, fonts, spacing and responsive layouts
- `images/` — supplied photographs, logo and source record
- This guide

## 2. Put it online
Two hosting routes from the supplied handover template are below. Account interfaces and plan allowances have not been verified in this offline build.

**Cloudflare Pages**
1. Use your own account at pages.cloudflare.com.
2. Create a Pages project using direct upload, then upload the contents of this folder.
3. Open the assigned site address and check the images, links and mobile layout.

**GitHub Pages**
1. Use your own account at github.com and create a repository named `doncaster-road-cleaning-demo` (suggested name).
2. Upload this folder's contents, then configure Settings → Pages to publish the main branch's root.
3. Open the address shown by GitHub Pages and check the site.

Hosting account and final published URL: [待客户提供：托管账号及最终网站地址].

## 3. Use your own domain
Domain: [待客户提供：自定义域名，如需使用]. Add your domain in the chosen host's custom-domain settings and copy the DNS records it supplies into your domain provider. Follow that provider's current instructions and verify HTTPS once DNS has updated. Domain prices and activation times are not promised here.

## 4. Edit text and images
- Open `index.html` in a text editor, change its plain text, save and re-upload.
- Keep `#services`, `#about`, `#gallery`, `#contact`, the form fields and both integration comments intact.
- Replace a photo with a file of the same name in `images/`; keep each file at or below 500 KB and update its alt text and source record.
- Sora headings and Inter body text load from Google Fonts. Their local fallback stacks are in `style.css`; the page remains usable if Google Fonts is unavailable.
- All five photographs are illustrative Pexels images. They do not show this business's staff, premises or work. The source record is copied unchanged from the supplied assets.
- Before a real launch: [待客户提供：真实商家确认的联系方式、文案及自有照片]. The supplied “Four years later” about text is preserved; ask the client to confirm its currency rather than silently changing the business history.

## 5. The contact form
The intended recipient in the brief is **hello@doncasterroadcleaning.example**, a fictional demo address. The form uses **Web3Forms**. It is **not configured to deliver enquiries**. The brief supplies no access key; the binding contract requires retaining the `{{FORM_ACCESS_KEY}}` placeholder. A matching visible missing-content note appears above the fields.

Free-plan allowance: [待客户提供：Web3Forms 所选方案及当前提交额度]. Working recipient and access key: [待客户提供：真实收件邮箱及其 Web3Forms access key].

To activate delivery, obtain a Web3Forms key for your real recipient, open `index.html`, find `<!-- form_marker -->`, and replace the value of the hidden `access_key` input. Changing the visible email address alone does **not** change the form recipient. Update the visible email and `mailto:` link separately; remove the demo form notice only after a successful authorised test submission. Preserve the POST action, hidden subject, botcheck and required fields. No form was submitted during this build.

## 6. Google (optional)
Use your own account at search.google.com/search-console. Add the final address and use the verification method provided there. For HTML-tag verification, insert your supplied tag at `<!-- search-console -->` in `index.html`.

Verification tag: [待客户提供：Search Console 验证标签，如需启用].

## 7. Revisions
The supplied handover template includes two rounds of revisions within the agreed scope. Send changes as a list. The current scope is one static page in this order: Hero, Services, About, Gallery, Contact.
