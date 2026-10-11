# Box Hill Movers — Website Handover

This folder contains the static demonstration website. Business and contact details are fictional; photos are Pexels stock illustrations. The enquiry form is not connected. Hosting and form accounts, if configured, should belong to the client.

## 1. What's in the folder
- `index.html` — the whole site, with editable services, prices, contact details and hours
- `style.css` — colours, fonts, spacing and responsive layouts
- `images/` — supplied photos and logo; `SOURCES.md` preserves photo provenance
- This guide

## 2. Put it online
Hosting account and chosen provider: [待客户提供：托管平台及客户自有账户]

**Cloudflare Pages**
1. Sign in to your own account at pages.cloudflare.com.
2. Choose the option to upload a static site's assets and upload the contents of this folder.
3. Record the assigned site address: [待客户提供：部署后的网站地址].

**GitHub Pages**
1. Sign in to your own account at github.com. Repository name: [待客户提供：GitHub 仓库名称].
2. Upload this folder's contents and configure Pages to publish the branch containing `index.html`.
3. Record the published address: [待客户提供：GitHub Pages 网站地址].

Provider screens, eligibility and pricing should be checked when publishing. This delivery has not been deployed.

## 3. Use your own domain
Domain: [待客户提供：自定义域名（如需要）]

Add your domain in the chosen hosting provider's domain settings, then copy the DNS records it supplies into your domain provider's settings. Follow the provider's verification status; no setup price or activation time is assumed here.

## 4. Edit text and images
- Open `index.html` in a text editor. Change the visible text, save, then upload the updated file.
- The three service prices are in `#services`; contact details, service area and daily hours are in `#contact`.
- Phone links must keep digits only, for example `tel:0400000007`. Update both telephone links when changing the number. Email links use `mailto:`.
- Replace photos with files of the same names in `images/`, keeping each at or below 500 KB. Update the matching alt text and captions. The five supplied photos are illustrative stock, not this fictional business's staff or work.
- The supplied logo contains only “Box”; “Hill Movers” is adjacent editable text.
- Google Fonts supplies Space Grotesk and Inter; local fallback fonts are defined in the CSS. The site contains no JavaScript.
- Retain the section anchors and the `search-console` and `form_marker` comments.
- Before real business use, supply verified business/contact details and client photos. The supplied “address” is a service area, not a street address; no shop address has been invented.

## 5. The contact form
Intended recipient in the brief: **hello@boxhillmovers.example** (fictional). Service: **Web3Forms**. The form is currently **inactive** because no access key was supplied, as requested for this demo.

Access key: [待客户提供：Web3Forms access key（示范站暂不配置）]

Live recipient, if converting this demo to a real website: [待客户提供：真实表单收件邮箱]

Form plan / submission allowance: [待客户提供：Web3Forms 套餐及提交额度]

To activate, obtain a Web3Forms key associated with the intended real recipient using the client's account. Open `index.html`, find `<!-- form_marker -->`, and replace the hidden `access_key` input's placeholder value with that key. Changing visible email text alone does not change the form recipient. Update or remove the visible demo form notice and its `aria-describedby` reference when appropriate, then test delivery with the client's permission. Keep the POST action, field names and botcheck input. No form submission or delivery test was performed for this demo.

## 6. Google (optional)
Search Console account/site property: [待客户提供：客户 Search Console 账户及网站地址]

After publishing, add the site at search.google.com/search-console and use the HTML tag verification method. Paste the supplied verification tag into `index.html` at `<!-- search-console -->`.

## 7. Revisions
Revision allowance and agreement: [待客户提供：修改轮次及约定]

Send requested changes as a list within the agreed scope. No revision allowance has been inferred from the generic handover template.
