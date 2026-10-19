# Master Prompt: Mother’s Comfy — International Confinement Care Website

Copy and paste the prompt below into any AI web builder or coding assistant (such as Gemini Canvas, v0, Bolt, Lovable, Cursor, or Claude) alongside your logo and hero photo to generate or extend the complete **Mother’s Comfy** website.

## 1. Full Website Generation Prompt

Build a complete, responsive, single-file interactive website (`index.html` using Tailwind CSS via CDN, Google Fonts `Cormorant Garamond` + `Inter`, and vanilla JavaScript) for **Mother’s Comfy — Confinement Care**, an international live-in postpartum confinement nanny agency serving families worldwide.

### Visual Identity & Colour Direction

Use the following exact brand palette and typography across all sections:

| Design Token | Hex / Value | Usage |
| :--- | :--- | :--- |
| Ivory Background | `#FAF5EF` (`#FDFBF8` surface, `#F3EAE0` alt section) | Main page background, soft section containers, and navigation glass backdrop |
| Sage Green Primary | `#71856A` (hover `#586A52`, light badge `#E6ECE4`) | Primary CTA buttons (`Enquire via WhatsApp`, `Check Availability for Your Due Date`), active pills, and checkmarks |
| Deep Forest Sage | `#2B372B` | All serif headings, primary body text, and top preview bar |
| Warm Beige Accent | `#EFD8B6` (light fill `#F5E9D6`, border `#E8D9C5`) | Highlighted 56-Day Elite package card, timeline milestones, and callout banners |
| Heading Font | `Cormorant Garamond` (600/700 weight) | Editorial headlines, section titles, package names, and step numbers |
| Body & UI Font | `Inter` (400/500/600 weight) | Body copy, comparison table cells, form inputs, badges, and buttons |

### Layout & Interactive Requirements

1. **Top Preview Bar & Sticky Header**:
   - Include a top utility bar with a view-mode toggle allowing visitors to switch between **Full Scroll Site** (all 4 pages stacked smoothly) and **Page-by-Page Tab View** (switching active sections like a multi-page site), plus a button to open a **Design Guide** modal showing the colour swatches and UX principles.
   - Build a sticky translucent header (`backdrop-filter: blur(12px)`) featuring the **Mother’s Comfy** botanical mother-and-baby emblem, the brand title **Mother’s Comfy** with subtitle `CONFINEMENT CARE`, navigation links (`Page 1: Home`, `Page 2: Care Packages`, `Page 3: How It Works`, `Page 4: Contact & Booking`), a mobile hamburger drawer, and a primary **Enquire via WhatsApp** button.

2. **Page 1: Home — Hero & International Empathy Strip**:
   - **Eyebrow Badge**: `🌍 International Live-In Postpartum Nanny Specialists`
   - **Main Headline**: `Care. Recover. Thrive.`
   - **Subheadline**: `Thoughtful postnatal care for mothers and their little ones, in the comfort of home. We match expecting families worldwide with medically screened, experienced confinement nannies who bring warmth, nourishing traditional meals, and 24-hour newborn support directly to your door.`
   - **Dual CTAs**: Primary sage button `Enquire via WhatsApp` (with WhatsApp icon) and secondary warm ivory button `Explore 28 & 56-Day Packages`.
   - **Supporting Tagline**: `Personalised care • Comfort • Recovery`
   - **Hero Visual**: Framed mother-and-baby photograph in soft natural window light with a floating badge reading `24-Hour Live-In Support • Worldwide Travel Ready`.
   - **3-Column Empathy & Trust Strip** below the hero:
     - `01 — Far From Family? We Are Your Village`: Designed for overseas families in the UK, Europe, Australia, USA, Middle East & Asia without local grandparents nearby (inspired by [Suraya Mothercare](https://www.google.com/search?q=https%3A%2F%2Fsurayamothercare.com%2Fmy%2Flaman-utama%2F) and [Asian Confinement UK](https://www.google.com/search?q=https%3A%2F%2Fwww.asianconfinement.co.uk%2F)).
     - `02 — Medically Screened & Travel-Ready`: Every nanny completes a pre-departure health check and required vaccinations before boarding her flight to your home.
     - `03 — Language & Cultural Alignment`: Curated matchmaking for English, Mandarin, or Cantonese-speaking households with personalized herbal & dietary care.

3. **Page 2: Care Packages (28-Day vs. 56-Day Comparison)**:
   - **Interactive Scenario Filter**: Add a `"Help Me Choose"` bar with three interactive filter buttons: `Compare Both`, `Standard Vaginal Recovery (28 Days)`, and `C-Section / Twins / Deep Rest (56 Days)` that dynamically highlight the recommended package card.
   - **Side-by-Side Package Cards + Full Comparison Table**: Render both responsive summary cards (each with a button that pre-selects the package and scrolls to the booking form) and a complete side-by-side comparison table using this exact content:

| Feature | 🌟 Premium Care Package (28 Days) | 👑 Elite Extended Package (56 Days) |
| :--- | :--- | :--- |
| Best For | Standard traditional recovery window. | Extended support for C-sections or twins. |
| Newborn Support | 24-hour professional baby care & log keeping. | 24-hour professional baby care & routine setting. |
| Maternal Care | Herbal baths, lactation support, binding assistance. | Extended lactation guidance & core recovery support. |
| Confinement Meals | 3 daily traditional meals + nourishing tonics/soups. | 3 daily traditional meals + nourishing tonics/soups. |
| Household Support | Light grocery prep & laundry for mother and baby. | Light grocery prep & laundry for mother and baby. |
| Flights & Travel Costs | Arranged and paid for by the customer. | Arranged and paid for by the customer. |
| Medical Screening | Pre-departure health check & vaccinations included. | Pre-departure health check & vaccinations included. |

   - **Primary Call to Action Banner**: Include a warm beige footer banner inside the table card featuring the button: `Check Availability for Your Due Date`.

4. **Page 3: How It Works (The International Process)**:
   - **Section Headline**: `Your Journey to a Supported Postpartum Period`
   - **Intro Copy**: `We make the matchmaking and preparation process straightforward and secure through four simple steps:`
   - **4-Step Process Cards**:
     - **Step 1: The Virtual Discovery Call** — *We meet via a secure video call to map out your due date, location, household language preferences, and cultural dietary needs.* (`4–6 Months Pre-EDD`)
     - **Step 2: Elite Nanny Matchmaking** — *We present profiles of curated nannies who match your specific needs and are fully ready for international travel.* (`Curated Shortlist`)
     - **Step 3: Travel & Timeline Coordination** — *Once you select your nanny, we coordinate the exact arrival timeline and schedule the return airline tickets to align seamlessly with your expected due date window.* (`Flight Alignment`)
     - **Step 4: Seamless Home Integration** — *Your nanny steps into your home to seamlessly take over meal preparation, infant care, and night shifts, giving you an immediate village of support.* (`Day 1 Home Arrival`)
   - **Interactive Due Date & Booking Timeline Calculator**: Include a date picker where expecting parents enter their Estimated Due Date (EDD) and automatically see their calculated **Step 1–2 Matchmaking Window** (4–6 months before EDD), **Step 3 Flight & Medical Check Milestone** (~6 weeks before EDD), and **Step 4 Care Completion Window** (+28 days / +56 days). Sync this date picker automatically with the Page 4 booking form EDD field.
   - **International FAQ Cards**: Include two practical FAQ cards addressing early/late delivery flight flexibility and how overseas confinement groceries and herbs are sourced (inspired by [Lavender Confinement Care](https://www.google.com/search?q=https%3A%2F%2Flavenderconfinementcare.com%2Fservices%2F)).

5. **Page 4: Contact & Booking**:
   - **Headline**: `Secure Your Postpartum Village Today`
   - **Intro Copy**:
     `To ensure proper scheduling and flight alignment, we highly recommend matching with your nanny at least 4 to 6 months before your estimated due date.`
     `Please fill out your details below for a prompt response from Mother’s Comfy within 24 hours:`
   - **Interactive Form Fields**:
     - `First & Last Name`: Required text input
     - `Email Address`: Required email input
     - `Phone Number (with Country Code)`: Required tel input (e.g., `+44 7700 900077`)
     - `Current International Location (City, Country)`: Required text input (e.g., `London, United Kingdom`)
     - `Estimated Due Date (EDD)`: Required date picker
     - `Preferred Language for Nanny`: Dropdown with `English`, `Mandarin`, `Cantonese`, and `Other` (selecting `Other` reveals a text field to specify dialect/language)
     - `Interested Package`: Dropdown pre-filled when the user clicks a package button on Page 2 (`Help Me Decide (28 vs. 56 Days)`, `🌟 Premium Care Package (28 Days)`, `👑 Elite Extended Package (56 Days)`)
     - **Submit Button**: `Request Free Consultation Call`
   - **In-Page Submission Confirmation**: Validate required fields with an in-page message box (never use `alert()`). On valid submit, display a personalized confirmation card summarizing the client's name, city/country, EDD, language, and package, with an `Edit details` link and a `Send Summary via WhatsApp Now` button.

## 2. Companion Image Generation Prompts (Optional Visual Assets)

If you want to generate additional photography for gallery cards or meal sections that match your hero image, use these prompts in an image generator:

* **Hero / Maternal Care Photo (`16:9` or `4:3`)**:
  `Asian mother in soft warm cream linen loungewear sitting peacefully on an ivory bed holding her newborn baby against her chest, bathed in soft morning daylight through sheer white curtains, serene minimalist bedroom, warm beige and sage colour palette, editorial lifestyle photography, clean composition, text-free, no watermarks.`
* **Traditional Confinement Meal & Herbal Tonic Photo (`4:3`)**:
  `Overhead editorial food photography of a nourishing traditional Asian postpartum confinement meal served on a warm wooden tray with ceramic bowls of herbal chicken soup with red dates and goji berries, ginger rice, and warm red date tea, soft natural window light, ivory linen napkin, sage leaf garnish, clean composition, text-free, no watermarks.`
