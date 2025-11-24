# The Seed — Website Migration & Integrations Proposal



## 1. Pricing Summary

### One-time

| Item                                  | Price (USD) | Notes                                  |
| ------------------------------------- | ----------- | -------------------------------------- |
| **Website migration (Squarespace → WordPress)** | **$400**     | Matches Guatemalan agency “Option 1”   |
| **Additional feature build (AI, CRM, etc.)**    | —           | Estimated **60–80 hours** of extra work; see breakdown below |


### Monthly (recurring)

| Item                          | Price (USD)            | Notes |
| ----------------------------- | ---------------------- | ----- |
| **SEO + SEM management**     | **$250 / month**       | Matches their package conceptually at a slightly lower monthly fee; same idea: manage Google Ads + basic SEO. |
| **Google Ads budget (media)**| **$300+ / month**      | Paid directly to Google, as with the Guatemalan proposal. |
| **Hosting + SSL**            | **$200 / year** | Same as what the Guatemalan agency |

---

## 2. What’s in the Migration Package (Matched to Guatemala)

This section shows the **work bundled into the $391** “Squarespace → WordPress” migration, mirroring what the Guatemalan agency offered as their **Option 1**.

### Scope: Website Migration & Hosting Setup

**Included:**

- WordPress installation on a managed server (≈2GB storage).
- Migration of current Squarespace design/structure into WordPress.
- Bilingual site (Spanish / English), mirroring existing content.
- Responsive layout (desktop / tablet / mobile).
- Basic on-page SEO:
  - Page titles, meta descriptions, clean URLs/slugs.
  - XML sitemap and basic robots.txt.
- Image optimization (resizing/compression during migration).
- One or more contact forms (e.g. general inquiry form), with email notifications.
- Hosting-related setup:
  - Domain + DNS pointing to the new server.
  - SSL certificate installation.
  - Database + PHPMyAdmin.
  - Basic email accounts (IMAP/POP3/SMTP), if required.
  - Server-level security: antivirus and scheduled backups.

### Estimated Effort: Migration Package

| Area                                    | Tasks                                                                 | Est. Hours |
| --------------------------------------- | --------------------------------------------------------------------- | ---------- |
| **Discovery & content inventory**       | Review current Squarespace site, list pages, blog, menus, forms.     | 2–4        |
| **WP setup & theme/page builder**       | Install WordPress, choose/configure theme or page builder.           | 2–4        |
| **Page layouts & content migration**    | Recreate existing pages with similar design/structure.               | 8–14       |
| **Blog migration**                      | Export/import posts, categories/tags cleanup, basic formatting.      | 2–5        |
| **Menus, header, footer, forms**        | Navigation, header/footer layout, contact form(s).                    | 3–6        |
| **SEO & URL structure**                 | Titles/meta, slugs, basic redirects where needed.                    | 4–6        |
| **Hosting, SSL, launch**                | Provision hosting, DNS, SSL, go-live checks.                         | 2.5–5      |
| **QA & responsive testing**             | Cross-device checks, fixing layout glitches, link tests.             | 4–6        |

**Total (migration only):**  
**≈ 25–30 hours** of work bundled into the **$391** migration package.

> In other words, I’m treating the **basic migration** as a flat, discounted project that exactly matches what the Guatemalan agency proposed.

---

## 3. Additional Features You Requested (Beyond the Guatemala Scope)

Here’s where the large gap is.

Everything below is **work the Guatemalan quote does *not* cover**, but that you’ve asked for:

- AI chatbot connected to WhatsApp and the CRM.
- Stripe or other online payments on the site.
- Booking engine integration (Hospitable / WeTravel).
- Proper CRM setup and email automations.
- A dedicated landing page + funnel.
- Deeper analytics and KPI tracking.
- Google Business / Maps presence optimization.
- LinkedIn advisory / optimization.

### 3.1 High-Level Comparison

| Scope                              | Included in Guatemalan quote? | Included in $391 migration? | Est. Additional Hours (beyond migration) |
| ---------------------------------- | ----------------------------- | --------------------------- | ---------------------------------------- |
| Basic Squarespace → WP migration   | ✅ Yes (Option 1)              | ✅ Yes                       | — (already counted)                      |
| AI chatbot + WhatsApp integration  | ❌ No                         | ❌ No                       | 14–20                                    |
| Booking engine integration         | ❌ No                         | ❌ No                       | 6–10                                     |
| Online payments (Stripe, etc.)     | ❌ No                         | ❌ No                       | 6–10                                     |
| CRM setup + email automations      | ❌ No (only a note about Mailchimp migration) | ❌ No | 13–20                                    |
| Landing page + funnel              | ❌ No (landing pages specifically excluded in their SEM scope) | ❌ No | 14–20                                    |
| Advanced analytics & KPI tracking  | 🔸 Only basic GA/GTM for ads  | 🔸 Basic only              | 10–15 (for funnel & CRM events, dashboards) |
| Google Maps / Google Business      | ❌ No                         | ❌ No                       | 4–7                                      |
| LinkedIn optimization              | ❌ No                         | ❌ No                       | 3–5                                      |

**Extra work for your wishlist:**  
Roughly **60–80 hours** of additional implementation on top of the 25–30 hours for the basic migration.

So in total:

- **Migration only:** ≈ 25–30 hours → **$391** (matched to Guatemala).
- **Extras you’re asking for:** ≈ 60–80 hours → **2–3× more work** than the migration itself.

---

## 4. Detailed Extra Features & Effort

### 4.1 AI Chatbot + WhatsApp + CRM Feed

**What you asked for**

> “Creación de un AI Chat bot básico unido al Whatsapp en el que nosotros podemos incorporar información de nuestros retiros para responder preguntás estándar básicas y alimentar a su vez el CRM.”

**What’s involved**

- Selecting an AI/chatbot platform that supports WhatsApp and CRM integration.
- Structuring FAQs: retreat info, dates, prices, logistics, travel questions.
- Building flows/intents for common questions.
- Connecting to WhatsApp Business.
- Connecting to CRM (send new leads with tags/segments).
- Testing in both languages (EN/ES).

**Estimated effort:** **≈ 14–20 hours**

---

### 4.2 Booking Engine Integration (Hospitable / WeTravel)

**What you asked for**

> “Integración con booking engine -hospitable o wetravel-”

**What’s involved**

- Reviewing which booking engine is the source of truth (Hospitable or WeTravel) and how it should appear on the site.
- Embedding booking widgets or iframes in relevant pages (e.g. retreats, accommodation).
- Styling to match the site aesthetic.
- Testing booking flow end-to-end (desktop/mobile).
- Making sure GA/GTM can track “started booking” and “booking completed” events if possible.

**Estimated effort:** **≈ 6–10 hours**

---

### 4.3 Online Payments (Stripe or Similar)

**What you asked for**

> “Integración de Stripe u otro Online Payment system”

**What’s involved**

- Setting up Stripe (or other gateway) products/checkout for retreats (e.g. deposits, balances, full payment).
- Embedding checkout flow into the WordPress site.
- Confirming handling of currencies, taxes, and fees as needed.
- Confirmation pages & emails wired into CRM where possible.
- Testing multiple payment scenarios.

**Estimated effort:** **≈ 6–10 hours**

---

### 4.4 CRM Setup & Automations (Mailchimp / Other)

**What you asked for**

> “CRM, automatización de emails, base de datos de clientes -Mailchimp, CRM; Zapier-”

**What’s involved**

- Setting up a CRM / ESP account (Mailchimp or similar).
- Defining lists/audiences and segments (leads vs guests; retreats; interests).
- Creating custom fields (e.g. retreat type, dates, source, language).
- Wiring up forms (site, landing pages, chatbot, and possibly booking engine) to feed the CRM.
- Building core email automations:
  - Welcome series.
  - Pre-retreat info.
  - Post-retreat follow-up.
- Setting up Zapier (or similar) for any non-native integrations.

**Estimated effort:** **≈ 13–20 hours**

---

### 4.5 Landing Page + Funnel

**What you asked for**

> “Creación de un Landing page y Funnel a nuestra página -como hemos hablado en la reunión-”

**What’s involved**

- Designing and building an opt-in landing page (similar spirit to the Guatemala Retreats example).
- Thank-you page and possibly a follow-up “info” page (e.g. retreat details, case studies, FAQs).
- Opt-in forms linked to CRM with the correct tags/segments.
- 1–3 email nurture sequence aligned with the retreat offer.
- Wiring events into GA4/GTM (landing views, opt-ins, key clicks).

**Estimated effort:** **≈ 14–20 hours**

---

### 4.6 Analytics & KPI Tracking

**What you asked for**

> “GA + Tag Manager (for SEM only)” and “Análisis KPI mensual.”

**What’s involved (beyond basic SEM tracking)**

- GA4 property & GTM container organized for long-term use.
- Events for:
  - Landing page opt-ins.
  - Retreat inquiry form submissions.
  - Booking engine starts/finishes (where technically feasible).
  - WhatsApp clicks.
- Linking GA4 with Google Ads and funnel pages.
- Creating a simple dashboard or report view focusing on:
  - Leads per channel (organic, ads, referrals).
  - Cost per lead and cost per booking (from ads).
  - Funnel drop-off points.

**Estimated effort:** **≈ 10–15 hours**

*(Some baseline GA/GTM work is part of the SEM package; the extra hours here are for funnel + CRM + multi-step KPI tracking.)*

---

### 4.7 Google Maps / Business Profile & LinkedIn

**What you asked for**

> “Optimización de nuestra presencia en plataformas google maps, google business, etc”  
> “Asesoría optimización Linked’in”

**What’s involved**

- **Google Business / Maps**
  - Audit of existing profile(s).
  - Fixing categories, descriptions, services, URLs with tracking.
  - Uploading key photos.
  - Q&A seeding and basic review strategy.

- **LinkedIn**
  - Review of profile and company page.
  - Suggestions for positioning, headline, About section.
  - Content themes and call-to-actions aligned with retreats.

**Estimated effort:** **≈ 7–12 hours**  
(≈ 4–7 for Google Business, 3–5 for LinkedIn).

---

## 5. Summary: Why the Extras Are “A Lot More”

Putting it all together:

| Block                                      | Est. Hours |
| ------------------------------------------ | ---------- |
| **Basic migration (Squarespace → WP)**     | **≈ 25–30** |
| **All additional requested features**      | **≈ 60–80** |
| **Total with everything implemented**      | **≈ 85–110** |

The **Guatemalan quote** (Option 1) at **$391** only covers the **25–30 hours** of basic migration work.

Your wishlist adds **roughly 60–80 hours** of new work on top — about **2–3× more** than the original website migration.

---

## 6. How We Can Structure This

- I’ll **match the Guatemalan migration price**:  
  - **$391** one-time for the Squarespace → WordPress migration as described above.
- I’ll **match the intent of their monthly SEM/SEO package**, simplified as:  
  - **$250 / month** for SEO + SEM management (plus your ad budget, e.g. $300/month paid directly to Google).
- For the **additional 60–80 hours of feature work** (AI, CRM, funnels, automations, bookings, etc.):
  - We can either:
    - Fund part of it upfront, **or**
    - Cover some/all of it via **commission on bookings**, since these extra systems are what will drive more direct bookings and retreat sales.

This way:

- You’re getting the **same baseline** the Guatemalan agency offered, at the **same price**.
- You also see clearly that your expanded wishlist is **substantially more work**, which justifies treating it as a separate block of value (whether paid upfront, via commissions, or a mix of both).

