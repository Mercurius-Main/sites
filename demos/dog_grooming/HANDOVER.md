# Belmore Road Dog Grooming — Website Handover

The HTML and CSS are editable files with no build step or account of ours involved. This is a fictional demonstration business. The supplied photos are Pexels stock illustrations, not the business's staff, premises or work; their sources are retained in `images/SOURCES.md`.

## 1. What's in the folder
- `index.html` — the whole site, including editable services, prices and contact details
- `style.css` — colours, fonts, spacing and responsive layouts
- `images/` — five supplied photos, the supplied logo and source notes
- This guide

## 2. Put it online
Hosting account and public URL: [待客户提供：托管账户及网站公开地址]. Suggested GitHub repository name: [待客户提供：GitHub 仓库名].

**Cloudflare Pages**
1. Sign in to your own Cloudflare Pages account.
2. Use its asset upload workflow and upload the contents of this folder.
3. Check the assigned site address on a phone and desktop.

**GitHub Pages**
1. Sign in to your own GitHub account and create the chosen repository.
2. Upload this folder's contents and configure Pages to publish the branch containing `index.html`.
3. Use the published URL shown in repository settings.

Hosting interfaces and plan terms have not been verified online. No deployment has been performed.

## 3. Use your own domain
Domain: [待客户提供：自定义域名（可选）]. Add the domain in your chosen host's settings, then enter the DNS records it provides at your domain provider. Use the provider's current instructions and pricing.

## 4. Edit text and images
- Open `index.html` in a text editor, change the visible text, save and re-upload. Services and prices are in `#services`; address, phone, email and hours are in `#contact`.
- Phone appears twice; update both visible numbers and both digits-only `tel:` destinations together.
- Replace images with files of the same names, keeping each below 500 KB. Update alt text and captions to match the actual image. The five current photos are stock placeholders and the gallery includes a large dog; it does not represent the small/medium-dog service portfolio.
- A real business launch requires verified business details and client-owned photos. Keep the demonstration disclosure until those replacements are complete.
- Colours and font stacks are in `:root` in `style.css`. Cormorant Garamond and Manrope load from Google Fonts; local fallback fonts work without that connection.
- The footer contains the exact disclosure required by the brief. It is one sentence and wraps on narrow screens for readability.

## 5. The contact form
Intended recipient: **hello@belmoredoggrooming.example** (a fictional address). Service: **Web3Forms**. Plan allowance: [待客户提供：Web3Forms 套餐及提交额度].

The form is **not configured to deliver enquiries**. The demo brief supplies no access key. Following the delivery contract, the hidden `access_key` retains the template token and a visible `[待客户提供：Web3Forms access key]` notice appears beside the form. Do not treat this demo as a working inbox.

To configure a real site, obtain a Web3Forms key for the intended real recipient, find `<!-- form_marker -->` in `index.html`, and replace the hidden `access_key` input's value with that key. Changing visible email text alone does not change the destination. After configuration, remove the demo form notice and its `aria-describedby` reference, then test delivery with the owner's permission. The form keeps the original POST endpoint, subject field, honeypot and required name/contact/message fields. No form submission was made during this build.

## 6. Google (optional)
Search Console verification tag: [待客户提供：Google Search Console 验证标签（可选）]. Add the published address to your own Search Console account and paste its verification tag at `<!-- search-console -->` in the document head. No verification or indexing claim is made for this demo.

## 7. Revisions
Revision allowance and agreement: [待客户提供：修订轮次及约定]. Send changes as a list against the agreed scope. This brief contained no 客户反馈 section, so this delivery is the initial build.
