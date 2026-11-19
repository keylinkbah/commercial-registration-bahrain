# Commercial Registration in Bahrain — Keylink

## Deploy on GitHub Pages
1. Create a GitHub repository and upload these files at its root, including `.nojekyll` and `assets`.
2. Open Settings → Pages → Deploy from a branch → main → / (root) → Save.
3. GitHub shows the public website address when deployment finishes.
4. If using your own domain, add it under Pages → Custom domain and configure its DNS as GitHub instructs. Enable HTTPS.

No installation or build is needed. `index.html` contains the complete design, images, fonts, CSS, JavaScript and JSON-LD. It also opens directly on your computer. The separate hero copy supports a crawlable structured-data image.

## Website address and SEO
This export is ready for any GitHub Pages address. Because your exact address is not yet known, it intentionally omits an absolute canonical, og:url, social preview image URL and sitemap rather than point Google at your WordPress site. Its schema uses page-relative entity IDs. Your page remains crawlable and indexable without these optional tags.

Once GitHub gives you the final public address, add a canonical link in the HTML head (`<link rel="canonical" href="YOUR_FINAL_HTTPS_ADDRESS">`) and an og:url meta tag for that same address. For social previews, add og:image and twitter:image pointing to your public assets/hero-registration.jpg URL. Create a sitemap.xml containing the final page URL and add its address to robots.txt. Replace YOUR_FINAL_HTTPS_ADDRESS with the real address; do not publish a placeholder. These final address settings can be completed after deployment.

Only one version should be indexed: avoid keeping WordPress and GitHub copies live at competing addresses without an appropriate canonical or redirect. After deployment, verify the domain in Google Search Console and submit sitemap.xml once created. Validate the live URL in Google's Rich Results Test and Schema.org Validator. Technical SEO and schema do not guarantee indexing, rich results or a first-place ranking. FAQ rich results are generally limited to qualifying government and health sites. Reviews and rating claims have not been invented.

## WhatsApp form
The form opens https://wa.me/97332392277 with the visitor's name, nationality, CR type and business activity prefilled. The visitor must tap Send in WhatsApp. The HTML does not send automatically, email enquiries or store submissions. WhatsApp must be available on the device or via WhatsApp Web. Never enter sensitive passport or payment details in the enquiry fields.

## Included structured information
One graph contains seven relevant types across six entities: Organization / ProfessionalService (one business), WebSite, WebPage, ImageObject, Service and FAQPage. The three offers use minimum USD 3,500 prices, not exact fixed prices. FAQ answers match the page. No extra schema plugin is needed on GitHub Pages.

## Credits
Images and logo: existing Keylink page assets. Fonts: Manrope and Sora, distributed under the SIL Open Font License. Smooth scrolling: Lenis (MIT). All media and fonts are embedded in the HTML, with no runtime CDN requirement.
