# Kew Strength Studio — Website Handover

This folder contains the static website and its assets. No agency account is involved. This is a fictional demonstration: contact details and photographs are placeholders, and form delivery is not configured. Photo licensing information is preserved in `IMAGE-SOURCES.md`.

## 1. What's in the folder
- `index.html` — the whole site, including services, prices, hours and contact details
- `style.css` — colours, Google Fonts (Sora and Inter), spacing and responsive layouts
- `images/` — resized copies of the five supplied stock photographs and supplied logo; each under 500 KB
- `IMAGE-SOURCES.md` — original Pexels sources and usage notes
- This guide

## 2. Put it online
Choose a host and confirm its current plan and publishing instructions before deployment. Hosting account: [待客户提供：网站托管账号]. Repository name: [待客户提供：GitHub 仓库名称].

**Cloudflare Pages**
1. Create or sign into your own account at pages.cloudflare.com.
2. Choose the direct asset upload option and upload this folder's contents.
3. Record the assigned site address: [待客户提供：已部署网站网址].

**GitHub Pages**
1. Create a repository in your own GitHub account using your chosen repository name.
2. Upload the folder contents, then configure Pages in the repository settings for the publishing branch and folder.
3. Record the published address shown by GitHub.

These are handover instructions, not evidence of deployment. No hosting account or live site was created during this build.

## 3. Use your own domain
Domain: [待客户提供：自定义域名]. Add your chosen domain in the host's settings and follow its DNS instructions at your domain provider. Hosting, domain costs and DNS timing have not been verified; no cost or activation-time promise is made.

## 4. Edit text and images
- Open `index.html` in a text editor. Change the visible text, save and upload again. Services and prices are the three `price-row` entries. Contact information and hours are in `#contact`.
- Sunday hours were not supplied: replace the visible `[待客户提供：周日营业时间]` once confirmed. Do not assume Sunday is closed.
- To swap a photo, put the replacement in `images/` under the same filename, update its alt text and check the crop on phone and desktop. Keep each image under 500 KB.
- All current images are Pexels illustrations, not the business's premises, employees or clients. Replace them with authorised client photos for a real launch and update the stock disclosures only after replacement.
- Test at 375 px and 1280 px after edits. The mobile phone button should remain fully visible in the first 375×812 screen.

## 5. The contact form
Intended recipient in the brief: **hello@kewstrength.example** (fictional). The form uses **Web3Forms**. Plan allowance: [待客户提供：所选 Web3Forms 方案及提交额度].

Delivery is not configured. The brief deliberately supplies no key; the hidden `access_key` therefore retains the contract-required placeholder. Required before live use: [待客户提供：真实收件邮箱及对应 Web3Forms access key].

Open `index.html`, find `<!-- form_marker -->`, then replace the `value` of the following hidden `access_key` input with the key issued for the confirmed recipient. Changing the visible email link alone does not change the recipient. Keep the POST action, required field names and botcheck field intact. Remove the visible unconfigured-form notice only after a real delivery test succeeds. No submission or email delivery was tested during this build.

## 6. Google (optional)
Use your own Search Console account at search.google.com/search-console. Add the published site and, if using HTML-tag verification, paste its supplied tag at `<!-- search-console -->` in the head of `index.html`. Verification tag: [待客户提供：Search Console 验证标签，如需].

## 7. Revisions
Revision entitlement was not specified in the brief: [待客户提供：约定修改轮次及范围]. Send requested changes as a list and confirm the agreed scope. This build includes only Hero, Services, About, Gallery and Contact, in that order.
