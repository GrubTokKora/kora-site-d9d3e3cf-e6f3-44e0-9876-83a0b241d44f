# Site index · format 2
Structure and the names of what each page offers. Values that change often — prices, hours, phone,
address — and body copy are deliberately not recorded here; read the page itself for those.

## index.html → /
title: 32th Oral Care – Gentle Family Dentistry in Brewster, New York
purpose: Home page for 32th Oral Care, introducing the practice, its dental services, opening hours, and location in Brewster, New York.
sections:
- `#site-header` — site branding, main navigation, and call-to-action: Home, Services, Hours, Visit us
- `#mobile-nav` — mobile navigation drawer: Home, Services, Hours, Visit us
- `#hero` — hero banner with practice introduction: Brewster, New York, Visit us
- `#story` — practice background and about information
- `#offerings` "Our Services" — grid of dental services: General & Preventive, Cosmetic Dentistry, Restorative Dentistry, Dental Implants, Emergency Dentistry, Children & Family, See all services
- `#hours_location` — opening hours and location details: Monday, Tuesday, Wednesday, Thursday, Friday, Brewster, New York, Visit us
also: The business description appears in the site metadata, the Open Graph tags, the FAQ schema, and the LocalBusiness schema.
also: The FAQPage JSON-LD schema contains questions and answers that are not rendered as visible text on the page.

## hours.html → /hours
title: Hours & Location — 32th Oral Care
purpose: Display opening hours, location, and visiting information for 32th Oral Care.
sections:
- "Hours &amp; Location" — page introduction
- "Opening Hours &amp; Find Us" — opening hours and location details: Monday, Tuesday, Wednesday, Thursday, Friday, Brewster, New York, Putnam County
- "Plan Your Visit" — patient visit information cards: Same-Day Emergency Care, Family-Friendly Appointments

## services.html → /services
title: Dental Services — 32th Oral Care
purpose: Display dental services offered by 32th Oral Care.
sections:
- "Our Dental Services" — hero banner: Brewster, New York
- `#offerings-heading` "Our Services" — dental services list: General & Preventive, Cosmetic Dentistry, Restorative Dentistry, Dental Implants, Emergency Dentistry, Children & Family
- `#detail-heading` "What to expect at each visit" — dental service details: General & Preventive, Cosmetic Dentistry, Restorative Dentistry, Dental Implants, Emergency Dentistry, Children & Family
- "Ready to book your visit?" — call to action band
also: The page description in the meta tag is mirrored into the JSON-LD structured-data block.
also: The offerings list of six dental services and their descriptions are repeated verbatim in the JSON-LD structured-data block.

## support files
Files that are not pages. A line marked [content] holds words or data a visitor reads, so a
change to the site's content can land there; the rest only make the site work or look right.
- `llms.txt` — 71 bytes — too small to hold content
- `robots.txt` — 45 bytes — too small to hold content
- `sitemap.xml` — 160 bytes — too small to hold content

## shared (every page)
The header, navigation, mobile menu and footer are propagated from index.html to every other page by
`shell_propagation`. A change to any of them is made on index.html alone and copied automatically.
