# Project Specification: Oracle Dental Care (Pitch Demo Website)

## 1. Tech Stack & Deployment Target
- **Stack:** Semantic HTML5, Tailwind CSS (via CDN for fast zero-build prototyping, or Vite + Tailwind), Vanilla JavaScript.
- **Hosting Target:** Cloudflare Pages (`oracle-dental-care.pages.dev`).
- **Architecture:** Single-page, high-converting, mobile-first static site. Zero backend database.

## 2. Brand & Visual Identity (Matched to Real Clinic Interior)
- **Primary Background:** Warm Ivory / Stone (`#FAF9F6`) and Clinical White (`#FFFFFF`).
- **Primary Accent / CTA:** Deep Emerald / Forest Green (`#1B4332`) — matches logo leaf motif.
- **Secondary Accent:** Warm Metallic Gold / Bronze (`#C59B27`) and Walnut Wood tones (`#5C4033`) — matches backlit 3D signage and chevron wood slat walls.
- **Operatory Highlight Color:** Subtle Plum / Burgundy (`#581845`) accents.
- **Typography:** Clean geometric sans-serif (e.g., 'Plus Jakarta Sans' or 'Inter') for UI, paired with an elegant serif (e.g., 'Playfair Display') for headings.

## 3. Verified Business Data
- **Clinic Name:** Oracle Dental Care (ओरेकल डेंटल केयर)
- **Co-Located Facility:** Oracle Imaging Diagnostic Centre (Led by Dr. Sagar Shetty - Ultrasonography/Diagnostics)
- **Lead Dental Surgeon:** Dr. Ananya Shetty (Award-winning dental surgeon; conference speaker/award recipient)
- **Specialist Team:** Visiting/In-house Prosthodontist
- **Google Rating:** 4.8 ★ (84+ Verified Google Reviews) | 4.3 ★ on Justdial (113 Ratings)
- **Address:** Bungalow No. 12, Dewan & Shah Housing Enclave, Ambadi Road, Off Vidya Mandir Marg, Near Vasai Virar Municipal Swimming Pool & Yamaha Showroom, Vasai West, Maharashtra 401202
- **Plus Code:** 9RQF+GF Vasai West
- **Primary Phone / WhatsApp:** +91 82650 54624
- **Additional Appointment Numbers:** +91 93592 26569 / +91 81800 38830
- **Email:** oraclehealthcareservices@gmail.com
- **Operating Hours:**
  - Monday to Saturday: 10:00 AM – 2:30 PM & 5:00 PM – 8:00 PM
  - Sunday: Closed
- **Accessibility & Facility Badges:** 100% Wheelchair Accessible (Entrance, Parking, Elevator, Restroom, Seating), Modern Ergonomic Operatory, Strict Sterilization Protocol, LGBTQ+ Friendly.

## 4. Core Services to Feature
1. **Painless Wisdom Tooth Extraction & Oral Surgery** (Signature service with proactive post-op doctor follow-up calls).
2. **Prosthodontics & Dental Implants** (Crowns, bridges, dentures, full-mouth rehabilitation with specialist prosthodontist).
3. **Orthodontics & Dental Braces** (Metal, ceramic, and clear aligner consultations).
4. **Cosmetic Dentistry & Smile Makeovers** (Veneers, teeth whitening, aesthetic bonding).
5. **Root Canal & Preventive Dentistry** (Single-sitting RCT, ultrasonic scaling, routine family checkups).

## 5. Exact Patient Testimonials (Real Google Reviews)
- **Rahul Mulki (5★):** "Highly recommended Dr. Ananya Shetty. I recently underwent a dental procedure here and had a fantastic experience. The doctor was incredibly skilled, explained everything clearly, and ensured I was completely comfortable and pain-free."
- **Vivek Shetty (5★):** "I just had my wisdom tooth pulled at Dr. Ananya’s clinic and I’m so glad I went there. She was very professional and easy to talk to. The best part was the follow-up—the staff and the doctor actually kept in touch to see how I was doing and took the time to answer all my questions without rushing me."
- **Sandeep Rajpurohit (5★):** "Great experience at Oracle Dental Clinic. Everything was explained thoroughly and all my doubts were answered patiently as well. The staff was friendly, the clinic was clean, and the overall experience was very comfortable. Felt satisfied with the consultation and treatment by the dentist and prosthodontist."

## 6. Interactive Functional Requirements
- **WhatsApp Instant Booking Form:** A clean modal or inline booking section with inputs for:
  - Patient Name
  - Phone Number
  - Treatment Needed (Dropdown of the 5 core services + General Consultation)
  - Preferred Slot (Morning: 10:00 AM - 2:30 PM | Evening: 5:00 PM - 8:00 PM)
  - On submit, JavaScript formats the data and opens `https://wa.me/918265054624?text=...` in a new tab.
- **Sticky Mobile Bottom Bar:** For mobile viewports, a sticky bottom bar with two buttons: "Call Clinic" (`tel:+918265054624`) and "Book via WhatsApp".
- **Embedded Google Map:** Responsive iframe pointing to Oracle Dental Care, Ambadi Road, Vasai West.

# Project Specification: Oracle Dental Care (Audited Demo Spec)

## 1. Confirmed Facts (Directly from Google Maps Viewport & Photos)
- **Clinic Name:** Oracle Dental Care (ओरेकल डेंटल केयर)
- **Google Maps Rating:** 4.8 out of 5 (84 reviews at time of capture)
- **Category:** Dental clinic
- **Address:** Bungalow No. 12, Dewan & Shah Housing Enclave, Ambadi Road, Off Vidya Mandir Marg, near Vasai Virar Municipal Swimming Pool, Vasai West, Maharashtra 401202
- **Plus Code:** 9RQF+GF Vasai West
- **Primary Phone (Google Maps):** 082650 54624
- **Additional Appointment Numbers (Visible on clinic's pink appointment card photo):** 93592 26569 / 81800 38830
- **Co-Located Facility (Visible on exterior blue signboard photo):** Oracle Imaging Diagnostic Centre (Ultrasonography) — Dr. Sagar Shetty
- **Operating Hours (Google Maps):**
  - Monday to Saturday: 10:00 AM – 2:30 PM, 5:00 PM – 8:00 PM
  - Sunday: Closed
- **Accessibility & Attributes (Google Maps "About" tab):**
  - Wheelchair-accessible entrance, exit, car park, lift, seating, and toilet
  - Restroom available, LGBTQ+ friendly
  - Appointments recommended
- **Named Personnel (From patient reviews):**
  - Dr. Ananya Shetty
  - A prosthodontist (mentioned in Sandeep Rajpurohit's review; in-house vs. visiting status is UNCONFIRMED)
- **Treatments/Topics Explicitly Mentioned in Reviews & Tags:**
  - Wisdom tooth extraction (`wisdom tooth`, Vivek Shetty review)
  - Dental braces (`dental braces` review tag)
  - Smile makeovers (`smile makeover` review tag)
  - Prosthodontic consultation & treatment (Sandeep Rajpurohit review)

## 2. Exact Verbatim Patient Reviews (Do Not Alter Inside Quotes)
- **Rahul Mulki:** "Highly recommended Dr. Ananya Shetty. I recently underwent a dental procedure here and had a fantastic experience. The doctor was incredibly skilled, explained everything clearly, and ensured I was completely comfortable and pain-free."
- **Vivek Shetty:** "I just had my wisdom tooth pulled at Dr. Ananya’s clinic and I’m so glad I went there. She was very professional and easy to talk to. The best part was the follow-up—the staff and the doctor actually kept in touch to see how I was doing and took the time to answer all my questions without rushing me."
- **Sandeep Rajpurohit:** "Great experience at Oracle Dental Clinic. Everything was explained thoroughly and all my doubts were answered patiently as well. The staff was friendly, the clinic was clean, and the overall experience was very comfortable. Felt satisfied with the consultation and treatment by the dentist and prosthodontist."

## 3. Unverified / Pending Client Confirmation (Do NOT state as fact)
- **Dr. Ananya Shetty's exact qualification acronym (BDS / MDS):** Unconfirmed.
- **Specific sub-procedures (Implants, Single-Sitting RCT, Aligners, Veneers):** Unconfirmed. Keep service descriptions general or mark as `[Sample Service Text — Customizable]`.
- **WhatsApp active number:** Must manually verify which of the three numbers (`82650 54624`, `93592 26569`, `81800 38830`) is active on WhatsApp.
- **Email (`oraclehealthcareservices@gmail.com`):** Sourced from third-party directory; omit from public UI until confirmed by clinic.

## 4. Technical & Compliance Rules
1. **DCI Ethics Compliance:** No superiority claims ("Best", "Award-winning", "Guaranteed Painless"). Use factual, dignified medical tone.
2. **Honest Imagery:** Any stock image must clearly state `[Representative Placeholder Photo]` and must NOT have clinic address captions overlaid on it.
3. **Zero Runtime Bloat:** No Tailwind Play CDN or unpinned Unpkg scripts in production. Use compiled CSS or clean native CSS + inline SVGs.
4. **Layout & SEO:** Include `Dentist` JSON-LD schema, `scroll-mt-24` on all anchor targets, accessible `aria-label` attributes on ratings, and no clipped negative-margin cards.