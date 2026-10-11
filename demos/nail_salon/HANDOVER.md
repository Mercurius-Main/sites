# Whitehorse Road Nails — Website Handover

You control the site files in this folder. No developer account is required. The supplied stock photographs remain subject to their Pexels licence; see `IMAGE-SOURCES.md`.

## 1. What's in the folder
- `index.html` — the whole site, with Hero, Services, About, Gallery and Contact
- `style.css` — colours, fonts, spacing and responsive layouts
- `images/` — five supplied stock photos and the supplied logo, each below 500 KB
- `IMAGE-SOURCES.md` — the client's source and licence notes
- This guide

This is a fictional demonstration business. The phone, address and email are placeholders. The form is not configured to deliver messages.

## 2. Put it online
Choose a hosting provider and verify its current plan and upload instructions in your own account. No deployment has been performed.

**Cloudflare Pages**
1. Open pages.cloudflare.com and create or use your own account.
2. Create a Pages project with direct asset upload.
3. Upload the contents of this `site` folder, with `index.html` at the root.
4. Review the assigned preview address before sharing it.

**GitHub Pages**
1. Create a repository named **[待客户提供：GitHub 仓库名称]** in your own GitHub account.
2. Upload this folder's contents to the repository root.
3. In Settings → Pages, select the publishing branch and root folder.
4. Use the published address shown by GitHub. Your account name and repository name determine that address.

## 3. Use your own domain
Domain: **[待客户提供：域名，如需使用自有域名]**.
Add your chosen domain in the hosting provider's custom-domain settings, then follow its DNS instructions at your domain provider. Pricing and activation time depend on those providers; they have not been verified for this delivery.

## 4. Edit text and images
- Open `index.html` in a text editor. Prices, services, address and hours are plain text. Save and re-upload after editing.
- Phone links currently use `tel:0400000005`. Update both the visible number and every `tel:` value together, using digits only in the link.
- Email links currently use `mailto:hello@whitehorseroadnails.example`.
- To replace an image, put its replacement in `images/` under the same filename. Update its `alt` text, width and height if the subject or dimensions change.
- Keep every image below 500 KB. Review the hero and about crop positions in `style.css` after replacing them.
- The current photos are Pexels stock, not this business's premises, staff or work. Preserve the demonstration disclosures while those photos remain. Real client photos are **[待客户提供：真实商家照片，仅在转为真实客户站时需要]**.
- Colours and font stacks are at the top of `style.css`. Fraunces and Manrope load from Google Fonts; local serif and sans-serif fallbacks are provided.
- Check the page at 375px and 1280px after edits. The primary phone button should remain fully visible in a 375×812 first screen.

## 5. The contact form
Intended recipient supplied in the brief: **hello@whitehorseroadnails.example**. This is a fictional address; **messages are not currently delivered**.

The form uses **Web3Forms**. Plan/submission allowance: **[待客户提供：Web3Forms 所选套餐及当前提交限额]**. Activation key: **[待客户提供：Web3Forms access_key]**.

For a real deployment, obtain an access key linked to a client-controlled, deliverable inbox. In `index.html`, find `<!-- form_marker -->` and replace the placeholder value of the hidden `access_key` input with that key. Changing the visible email address does not configure the form's recipient. Keep the form action, POST method and field names intact.

After configuring the key, test delivery with the client's permission and verify receipt in the intended inbox. Remove the visible demo-form notice only after successful validation. No form submission or delivery test has been performed for this demo. The missing key is intentional under the delivery contract.

## 6. Google (optional)
Use your own account at search.google.com/search-console to add the final site address. If you choose HTML-tag verification, paste the supplied verification tag at `<!-- search-console -->` in the document head. Google verification is not configured and no indexing claim is made.

## 7. Revisions
Send requested changes as a list within the agreed scope. Revision allowance: **[待客户提供：确认约定的修改轮次；交接模板默认两轮]**. The current brief contains no 客户反馈 section, so this delivery is the initial build.
