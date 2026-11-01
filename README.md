Node.jsBabar Boutique — concept website
A lightweight, server-rendered, responsive boutique demo. No dependencies or API keys are required.
Run
Install Node.js 18+ and run npm start. The site listens on port 3000 (or PORT), on all interfaces. Open http://localhost:3000.
Editing
data/site.json is the central business, collection and product catalogue. Add a product object for each distinct item; use separate image objects for its views. Empty optional fields are omitted on the product page. Prices must be verified before adding.
public/images/ contains optimized images; IMAGE-INVENTORY.md maps original uploads to derivatives and explains the near-duplicate. No AI images were used.
server.js contains page templates and routes. public/style.css contains tokens and styles, and public/app.js contains interactions.
The name and description of the single look are provisional, because the six supplied photos show the same outfit. The man's suit is not separately represented as boutique inventory.
The contact form opens a prefilled email app and cannot send directly. WhatsApp product links include the current origin. No checkout or false success state is provided.
This is an unapproved demo. Directory-sourced contact details, exact address, image rights, product details, policies and any actual store practices must be confirmed with the owner before launch. Opening hours are intentionally omitted.
SEO: the demo is set to noindex, nofollow and robots.txt disallows crawlers. Canonical URLs and sitemap entries remain empty unless business.productionUrl is set to the owner’s real production URL. On approval, remove noindex in server.js, update robots.txt response, set the production URL and review metadata, social image and structured data. Legal pages are explicitly drafts
