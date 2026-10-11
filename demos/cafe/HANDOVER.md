# Greythorn Corner Cafe — Website Handover

This folder contains the complete static demonstration site. No developer account is connected. Google Fonts supplies the typefaces, with local fallback fonts. The enquiry form needs a client-owned Web3Forms key before it can deliver messages.

## 1. What's in the folder
- `index.html` — the whole site, including editable prices, hours and contact details
- `style.css` — colours, fonts, spacing and responsive layouts
- `images/` — supplied logo and five Pexels illustration photographs
- `SOURCES.md` — the supplied image source and licence notes
- This guide

This is a fictional business. The photos do not depict Greythorn Corner Cafe, its staff or its work. All contact details are demonstration placeholders.

## 2. Put it online
Choose a host using your own account. Hosting availability, plans and current instructions have not been checked because this task permits no network access except Google Fonts.

**Cloudflare Pages**
1. Open pages.cloudflare.com and create or sign in to your account.
2. Choose the direct asset upload option and upload this folder's contents.
3. Use the address assigned by the host. [待客户提供：部署后的站点网址]

**GitHub Pages**
1. Open github.com and create a repository. [待客户提供：GitHub 仓库名称]
2. Upload the contents so `index.html` is at the published root. Enable Pages in repository settings and select the publishing branch and folder.
3. Record the address supplied by GitHub. [待客户提供：GitHub Pages 网址]

## 3. Use your own domain
[待客户提供：自有域名；若不需要可使用托管平台网址]

Add the domain in the host's custom domain settings, then copy the exact DNS records it supplies to your domain provider. Prices and activation times depend on the provider; check them before purchasing. No domain or deployment has been configured as part of this delivery.

## 4. Edit text and images
- Open `index.html` in a text editor, edit the visible text, save, and upload again. Prices and opening hours are ordinary HTML text.
- Keep section IDs `services`, `about`, `gallery`, `contact` so navigation continues to work.
- Replace photos in `images/` using the existing filenames, keeping each under 500 KB. Update descriptive alt text, captions and source notes when changing photos.
- Fonts: Cormorant Garamond for headings; Inter for body text. Both have fallbacks in `style.css`.
- Check 375 px mobile and 1280 px desktop after edits. Keep the call button visible without scrolling at 375×812.
- Preserve the exact demonstration footer while this remains a demo. For a real business, obtain verified contact details and genuine photographs before changing the disclosures.

## 5. The contact form
The intended recipient in the brief is **hello@greythorncorner.example**, a fictional address. **No enquiries are currently delivered.** The form uses **Web3Forms**; [待客户提供：当前表单套餐及提交限额]. No service quota has been assumed or verified.

[待客户提供：Web3Forms access key；正式上线时提供真实收件邮箱]

To connect a real inbox, obtain an access key using the recipient's own Web3Forms account. In `index.html`, find `<!-- form_marker -->` and replace the placeholder value of the hidden `access_key` input with that key. Changing visible email text or the `mailto:` link does not change the form recipient. To change recipients later, obtain the corresponding key from the service and update the hidden input.

Keep the POST action `https://api.web3forms.com/submit`, the hidden subject, botcheck field, required name/contact/message fields, and both form marker comments. Web3Forms requires no JavaScript here. After configuration, remove the visible unconnected-form note and its `aria-describedby` reference, then perform a controlled submission and confirm receipt. No test submission was made during this build.

## 6. Google (optional)
Use your own account at search.google.com/search-console. Add your published URL and follow the current HTML-tag verification instructions, placing the tag at `<!-- search-console -->` in `index.html`.

## 7. Revisions
Two rounds of revisions within the agreed scope are included by the supplied handover template. Send changes as a list for an updated set of files. This build contains exactly Hero, Services, About, Gallery and Contact, in that order.

