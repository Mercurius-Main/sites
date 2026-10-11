# Eastside Electrical Services — Website Handover

You control the delivered site files. No developer-owned account is involved. This is a fictional demonstration site; the supplied stock photos remain subject to their source licence.

## 1. What's in the folder
- `index.html` — the whole site, including all editable services, prices and contact details
- `style.css` — colours, fonts, spacing and responsive layouts
- `images/` — five supplied illustrative Pexels photographs, the supplied logo and `SOURCES.md` provenance
- This guide

## 2. Put it online
The following hosting options are carried over from the handover template. Their current interfaces and plan terms have not been verified for this offline build.

**Cloudflare Pages**
1. Create your own account at pages.cloudflare.com.
2. Choose a Pages project with direct asset upload, then upload the contents of this `site` folder.
3. Use the project address shown in your account. Live site URL: [待客户提供：发布后的网站地址].

**GitHub Pages**
1. Create your own account and a repository named [待客户提供：GitHub 仓库名称].
2. Upload this folder's contents at the repository root; configure Pages to publish from the appropriate branch in repository settings.
3. Use the URL shown by Pages. Repository name / URL: [待客户提供：GitHub 仓库名称和地址].

## 3. Use your own domain
Domain: [待客户提供：自有域名（如需）]. Add your domain in the chosen hosting account and follow its displayed DNS instructions at your domain registrar. Domain charges and DNS timing depend on the provider; they were not verified for this build.

## 4. Edit text and images
- Open `index.html` in a text editor. Change the visible text, save and upload the updated files.
- Services and prices are the three list rows in `#services`. Hours and service area are in `#contact`. There is no invented street address or weekend timetable.
- Update every `tel:0400000004` and visible phone number together. Telephone links use digits only. Update the `mailto:` link and its visible email together.
- Replace photos in `images/` using the same filenames and keep each below 500 KB. Review the image dimensions, alt text, captions and both mobile and desktop crops after replacing them.
- The supplied photos are stock illustrations, not Eastside's premises, employees or projects. Preserve the provenance in `images/SOURCES.md`; replace with client photos before adapting this demonstration into a real business site.
- Space Grotesk and Inter load from Google Fonts with local fallback stacks. There are no scripts or build tools in the delivered site.

## 5. The contact form
Intended recipient: **hello@eastsideelectrical.example** (fictional demo address). The template uses **Web3Forms**. The form is **not configured and delivery has not been tested**. Service quota: [待客户提供：Web3Forms 账户当前套餐额度].

The brief supplies no access key. The hidden `access_key` retains the literal `{{FORM_ACCESS_KEY}}` required by the delivery contract; the page also displays `[待客户提供：Web3Forms access key]`. This intentionally fails the strict production-readiness checks.

To configure a real site, use a real recipient account to obtain the corresponding Web3Forms access key. In `index.html`, find `<!-- form_marker -->` and replace only the hidden `access_key` value. Replacing the visible email address alone does not change where the form sends enquiries. Retain the POST action, field names and spam-check field. After configuration, send a client-authorized test enquiry, confirm receipt, and remove the demo form notice. No enquiry was submitted during this build.

## 6. Google (optional)
Use your own Search Console account. Add the deployed property and, if using HTML-tag verification, insert the provided tag at `<!-- search-console -->` in `<head>`. Verification tag: [待客户提供：Search Console 验证标签（如需）]. No verification or indexing has been performed.

## 7. Revisions
The brief does not specify a revision allowance: [待客户提供：约定的修改轮次]. Send requested changes as a list within the five-section scope. A future “客户反馈” section in `BRIEF.md` defines the revision work.
