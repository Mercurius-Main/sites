# Greythorn Lawn & Garden — Website Handover

The HTML, CSS and supplied demonstration assets are in this folder. No developer account is required. Photos retain the Pexels provenance and licence notes in `images/SOURCES.md`; they are stock placeholders, not this fictional business’s staff or work.

## 1. What's in the folder
- `index.html` — the whole site, with five sections and editable business text
- `style.css` — colours, fonts, spacing and responsive layouts
- `images/` — five resized stock photos, supplied logo and source notes
- This guide

## 2. Put it online
Hosting account and repository name: [待客户提供：托管账户和仓库名称].

**Cloudflare Pages:** use the account’s static asset upload workflow and upload this folder’s contents. The entry point is `index.html`.

**GitHub Pages:** create a repository named [待客户提供：仓库名称], upload the folder contents, then configure Pages to publish the branch and directory containing `index.html`.

No hosting has been configured or deployed. Confirm the provider’s current terms and dashboard instructions when publishing. Keep the demonstration disclosure while using fictional contact details and stock photos.

## 3. Use your own domain
Domain: [待客户提供：域名]. Add the chosen domain in the hosting account, then use the exact DNS records supplied by that host. Domain purchase and DNS setup are not included in this delivery; no activation time is promised.

## 4. Edit text and images
- Open `index.html` in a text editor. Services and starting prices are under `id="services"`; contact details and hours are under `id="contact"`.
- Sunday hours were not provided: replace `[待客户提供：周日营业时间]` only after confirmation. The business is mobile; the service area is shown instead of an invented street address.
- To swap a photo, replace the matching file in `images/`. Keep every image under 500 KB and update its width/height attributes, alt text and caption to match the actual picture.
- Stock photos are labelled throughout. Replace them with client-authorised photos before describing them as actual staff or completed work. The provided gallery-3 photo shows a person with a mower, not lawn stripes; its alt text describes the image accurately.
- Colour and typography tokens are at the top of `style.css`. Fraunces and Manrope load from Google Fonts, with local fallback stacks.

## 5. The contact form
Intended recipient: **hello@greythornlawn.example** (fictional demonstration address).

The form uses **Web3Forms**. It is **not connected** and no delivery test has been made. Access key: [待客户提供：Web3Forms access key，示范站暂不启用]. Form allowance: [待客户提供：Web3Forms 账户套餐及提交额度]. Do not promise receipt of demonstration submissions.

For a real launch, the client must supply a real recipient address and an access key associated with that address. In `index.html`, find `<!-- form_marker -->` and set the hidden `access_key` input to the provided key. Changing the visible email address alone does not change the recipient. Remove the visible “not connected” notice only after the client has tested delivery. Preserve the form action, POST method, field names and botcheck input.

## 6. Google (optional)
After publishing, add the actual site URL to the client’s own Google Search Console account. For HTML-tag verification, paste the supplied verification tag into the head at `<!-- search-console -->`. No verification or indexing has been performed.

## 7. Revisions
Revision allowance and delivery terms: [待客户提供：确认的修改轮数及交付约定]. Send requested changes as a list within the confirmed five-section scope; scope changes require a brief update.
