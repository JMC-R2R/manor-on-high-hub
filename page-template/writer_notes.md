# Manor On High, location page template

**Layout name:** Manor location page (Elementor "suburb wedding venue" layout)
**Source pages (approved, built by our delivery team):**
- https://manoronhigh.com.au/toorak-wedding-venue/
- https://manoronhigh.com.au/brighton-wedding-venue/

Both pages use the identical Elementor build (same element IDs). Only the H1, the two section H2s, the two framed photos, the intro and room paragraphs and the FAQ change from page to page. Everything else is fixed copy, and it is already written into `skeleton.html`.

**Pages to write with this template:** Wedding Venue Broadmeadows, Wedding Venue Preston.

> **Check before writing Preston:** a live page already exists at https://manoronhigh.com.au/preston/ (title "Wedding Venues Near Preston | The Manor on High", H1 "Luxury Wedding Venue in Preston"). Confirm with Jhen whether the new page replaces it or targets a different angle, so the two don't compete in search. No Broadmeadows page was found in the page sitemap on 11/11/2026. The nearest existing pages are /wedding-venue-meadow-heights/, /wedding-venue-glenroy/ and /wedding-venue-coolaroo/.

## How to fill the skeleton

- Replace every `{{...}}` slot. Leave everything else exactly as it is: classes, fixed headings, fixed paragraphs, icons, gallery, reviews and form.
- Use exactly one `<h1>`, in the hero. The hero section keeps `class="pg-hero mh-hero"`.
- Don't add inline `style` attributes, new classes or extra sections.
- Write in Australian English. Don't use em or en dashes (write "80 to 180 guests", not "80–180") or the Oxford comma. Write in the first person plural ("we", "our"), in a warm and assured tone that is premium and inclusive.
- Positioning: Melbourne's elegant alternative to city and winery venues. Don't write to cultural or multicultural weddings. That focus has been dropped, even though the header menu still lists cultural pages.

## Sections in order

| # | Section | Class | Fixed or slot | Guidance |
|---|---|---|---|---|
| 1 | Hero (background video, black gradient, gold Playball H1) | `pg-hero mh-hero` | **Slot: H1** | 8 to 12 words. The live pattern is "An Elegant Wedding Reception Venue for Couples from Toorak" and "An Elegant Melbourne Wedding Venue for Couples from Brighton". Keep "Couples from [Suburb]". The hero has no lead paragraph and no button. |
| 2 | Virtual Tour (Matterport) | `mh-tour` | Fixed | Copy it verbatim. |
| 3a | Intro H2 + framed photo left, copy right, "Download Brochure" button | `mh-intro` | **Slots: H2_INTRO, IMG_1/ALT_1, P_INTRO_1, P_INTRO_2** | H2: 7 to 12 words in Title Case, about the setting or the planning benefit (live: "Bring Your Wedding Plans to Life in Our Melbourne Reception Rooms", "Discover an Elegant Setting for Your Wedding Reception"). P1: 55 to 70 words. Name [Suburb] couples and our Epping estate, then cover matching the guest list to a room and planning the menu, styling and schedule together. Use the phrase "luxury wedding venues in Melbourne" once. P2: 35 to 45 words on what the couple might want on the day, ending with an invitation to a private tour. |
| 3b | Spaces H2 (left aligned) + room list, framed tall photo right, "Reach Out to Us" button | `mh-rooms` | **Slots: H2_SPACES, P_SPACES_LEAD, five room paragraphs, IMG_2/ALT_2** | H2: 7 to 12 words in Title Case, about personalising the celebration. Lead: one sentence of 20 to 30 words. The room labels (Regency Room, Georgian Room, Grand Ballroom, Courtyards, Lounge Spaces) and their links are fixed. Write each room paragraph in 30 to 50 words, using only the facts listed below. Use the phrase "unique wedding venues in Melbourne" once, in the Courtyards paragraph. |
| 4 | "We Will Make Your Dream Day Come True", 5 icon boxes on a floral backdrop | `mh-dream` | Fixed | Copy it verbatim. |
| 5 | "Gallery Event Highlights", 8 Regency Room photos | `mh-gallery` | Fixed | The same 8 photos appear on both live pages. |
| 6 | "Book Today" dark band + button | `mh-book` | Fixed | Copy it verbatim. |
| 7 | "Testimonials / Past Clients" | `mh-reviews` | Fixed | These are 3 Google reviews copied verbatim from the live Trustindex widget. Don't edit them, add to them or invent reviews, and don't add a review count or rating. |
| 8 | "Frequently Asked Questions", numbered gold accordion | `mh-faq` | **Slot: 5 FAQs** (4 to 6 allowed) | Questions run 8 to 16 words and answers 45 to 60 words. The first `<details>` gets `open`. Q1 is always the location question ("Where is Manor on High located for couples searching for a [Suburb] wedding venue?"). Pick the other topics from: choosing a room, all-inclusive packages, personalising the menu and décor, ceremony and reception together, travel and parking from [Suburb]. |
| 9 | "Ready to Begin Your Journey?" + enquiry form | `mh-cta` | Fixed | The form is a static mock of the live GoHighLevel form. |

**Total word range for the writer's own copy:** about 550 to 700 words (H1 and H2s + intro + rooms + FAQ). With the fixed copy, the whole page comes to about 850 to 950 words.

## Fixed copy (already in the skeleton, never rewrite it)

- Section headings: "Virtual Tour", "We Will Make Your Dream Day Come True", "Gallery Event Highlights", "Book Today", "Testimonials / Past Clients", "Frequently Asked Questions", "Ready to Begin Your Journey?"
- Icon boxes: "Fully customisable menus and decor" / "Our dedicated team has over 50 years of collective experience" / "Dreamlike setting in beautiful Epping" / "Premium Lounge Spaces" / "Your own personal wedding coordinator"
- Book Today: "Ready to start your forever at Manor on High? Get in touch with our friendly team today. We can't wait to hear your love story and help you design a day as unique as your love. Manor on High, where your magical outdoor wedding ceremony can come to life."
- CTA: "Let's make your dream day a reality. Book a private tour and experience first hand why Manor on High is one of Melbourne's most sought-after wedding and event venues."
- Buttons: "Download Brochure" (to /download-brochure/), "Reach Out to Us" (to /contact-us/, used twice). The form submit button reads "Submit".

## Facts you may use (verbatim from the client's own site, nothing else)

| Fact | Exact wording on the site | URL |
|---|---|---|
| Address | "519 High St, Epping, VIC 3076" (footer) and "We're at 519 High Street, Epping, in Melbourne's northern suburbs." | footer of every page; FAQ on /toorak-wedding-venue/ |
| Phone | "(03) 9401 3111" | footer (tel:0394013111) |
| Email | "mail@manoronhigh.com.au" | footer |
| Three reception rooms | "we offer three reception rooms with private courtyards and lounges" | /toorak-wedding-venue/ FAQ |
| Regency Room | "We offer our Regency Room for celebrations of 80–180 guests, with a grand piano in the foyer and a dedicated stage and dance floor. Private bridal quarters..." | /toorak-wedding-venue/ |
| Georgian Room | "We accommodate up to 270 banquet guests in our Georgian Room. A dedicated entrance and foyer welcome your guests, while the adjoining courtyard and lounge..." | /toorak-wedding-venue/ |
| Grand Ballroom | "for larger guest lists... Crystal chandeliers frame the sweeping dance floor, while our event manager helps coordinate the reception". Never give a capacity number. | /toorak-wedding-venue/ |
| Courtyards | "We give each reception room its own private courtyard" | /toorak-wedding-venue/ |
| Lounges | "furnished lounges alongside our reception rooms... With bar facilities" | /toorak-wedding-venue/ |
| Parking | "We provide complimentary parking for guests who drive." | /brighton-wedding-venue/ FAQ |
| Packages | "packages covering venue hire, catering, décor, service staff and wedding coordination" | /brighton-wedding-venue/ FAQ |
| Ceremony | "we offer ceremony and reception options at our Epping venue" / "outdoor ceremony options and indoor reception rooms" | both source pages |
| Travel time, Preston | "Our stylish event rooms are just a 20-minute drive north of Preston." | https://manoronhigh.com.au/preston/ |
| Travel time, Broadmeadows | **None stated on the site.** Write "a short drive" or "in Melbourne's northern suburbs" and give no minutes or kilometres. | n/a |
| Team experience | "Our dedicated team has over 50 years of collective experience" (fixed icon box) | both source pages |

Never state a package price, a capacity for the Grand Ballroom, a guest maximum for the venue, a review count or a star rating in your own copy. Don't name staff (reviews mention Mario and Bruno, but the copy never names them).

## Photos (IMG_1, IMG_2)

Use a client photo URL. If the hub has prepared page images under `https://update.readytorank.com.au/manor-on-high-hub/img/pages/<mon>/`, use those. Otherwise pick from these live-site photos, all checked and returning 200 on 11/11/2026. Don't reuse the 8 gallery photos (RegencyRoom_Stills 01, 02, 06, 07, 08, 09, 10 and 14), and don't use the same photo on both location pages.

- https://manoronhigh.com.au/wp-content/uploads/2026/01/ManorOnHigh_GeorgianRoom_Stills-45-1024x683.jpg (Georgian Room foyer staircase)
- https://manoronhigh.com.au/wp-content/uploads/2026/01/ManorOnHigh_GrandBallroom_Stills-26-1024x683.jpg (Grand Ballroom, also the hero poster)
- https://manoronhigh.com.au/wp-content/uploads/2026/10/ManorOnHigh_GeorgianRoom_Stills-06-1024x683.jpg (Toorak page)
- https://manoronhigh.com.au/wp-content/uploads/2026/10/ManorOnHigh_GeorgianRoom_Stills-07-1024x683.jpg
- https://manoronhigh.com.au/wp-content/uploads/2026/10/ManorOnHigh_GrandBallroom_Stills-34-1024x683.jpg (Brighton page)
- https://manoronhigh.com.au/wp-content/uploads/2026/10/ManorOnHigh_GrandBallroom_Stills-45-1024x683.jpg (Brighton page)
- https://manoronhigh.com.au/wp-content/uploads/2026/10/ManorOnHigh_25A_Month01_Stills-08-819x1024.jpg (portrait, Toorak page)
- https://manoronhigh.com.au/wp-content/uploads/2026/01/ManorOnHigh_25A_Month01_Stills-25-819x1024.jpg (portrait)

Alt text describes what the photo shows, in 6 to 12 words, ideally naming the room and "Manor on High".

## Internal links

The fixed links are already in the skeleton: room labels to /regency-room/, /georgian-room/, /grand-ballroom/, /courtyards/ and /premium-lounge-spaces/, plus /download-brochure/ and /contact-us/. You may add at most one more in-text link, to /all-inclusive-wedding-package/ (packages FAQ), /wedding-ceremonies/ or /outdoor-wedding-ceremonies/ (ceremony FAQ). Use absolute https://manoronhigh.com.au/ URLs.

## Avoid

- Cultural or multicultural wedding angles, and any culture or religion by name
- Prices, capacity numbers beyond the two room facts above, review counts and ratings
- Invented travel times, landmarks, transport routes or distances (apart from the Preston line above)
- Claims about the suburb itself that the client's site doesn't make
- "Nestled", "boasts", "unforgettable" chains and other filler. Keep sentences plain and specific.
- Em and en dashes, the Oxford comma and US spelling
