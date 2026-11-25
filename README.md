# What Is Counselling — James Pearson (Integrative Counsellor)

A polished, fast, accessible, zero-dependency static website redesign for **What Is Counselling**, the private counselling practice of **James Pearson**.

* **Live Practice:** [whatiscounselling.com](https://whatiscounselling.com/)
* **Practitioner:** James Pearson (Postgraduate Distinction, Lancaster University)
* **Accreditations:** BACP Registered Member · NCPS Accredited Member
* **Locations:** Foster Park View, Denholme, Bradford, West Yorkshire (BD13 4BQ) & Online across the UK

---

## ✨ Design & Architectural Highlights

* **Authentic Brand Identity:** Harmonized around the authentic circular red brand mark (`#c92a2a`, `#1a201d`, `#faf8f5`).
* **Clean Editorial Layout:** Controlled typography with responsive CSS `clamp()` scales, elegant Playfair Display serif headings, DM Sans body text, and restrained 4px button border radii.
* **Professional Trust Bar:** Official member badges for **BACP Registered Member**, **NCPS Accredited Member**, **Lancaster University**, and **Psychology Today Verified**.
* **Practice Studio Location Card:** Dedicated in-person counselling studio card with full address, off-street parking confirmation, and 1-click Google Maps navigation.
* **3-Step Journey Roadmap:** Transparent, pressure-free breakdown of the counselling process:
  1. Free 15-Minute Introductory Call (Phone or Video)
  2. Initial 60-Minute Clinical Session (£35)
  3. Ongoing Counselling (£60 / 60 min, flexible cancellation up to 2h ahead)
* **100% Internal Journal System:** 10 authentic articles migrated from the live website into dedicated internal HTML pages with left-aligned brand badge overlays on original photography.
* **Mobile Thumb-Friendly Quick-Action Bar:** Sticky frosted-glass bottom bar on mobile screens offering 1-tap call/text and online scheduling.
* **Zero Dependencies:** Pure vanilla HTML5, CSS3, and modern JavaScript without bloated frameworks, libraries, or external runtimes.

---

## 📁 Project Structure

```text
what-is-counselling-redesign/
├── index.html                                 # Homepage
├── about.html                                 # Meet James Pearson
├── practical-details.html                     # Fees, session structure & location
├── online-counselling.html                    # Remote therapy across the UK
├── in-person-counselling.html                 # Practice room in Denholme, West Yorkshire
├── will-counselling-help-me.html              # Guidance for new clients
├── contact.html                               # Contact form & direct practice details
├── journal.html                               # Journal index & article catalog
├── privacy-policy.html                        # UK GDPR & data protection notice
├── relationship-counselling.html              # Service: Relationship counselling
├── anger-counselling.html                     # Service: Anger management
├── anxiety-counselling.html                   # Service: Anxiety counselling
├── depression-counselling.html                # Service: Depression counselling
├── grief-counselling.html                     # Service: Grief & loss counselling
├── journal-*.html                             # 10 dedicated internal journal article pages
├── journal_data.json                          # Full structured catalog of all articles
├── assets/
│   ├── css/
│   │   └── style.css                          # Master stylesheet & responsive design system
│   ├── js/
│   │   └── script.js                          # Client-side router, templates, and UI interactions
│   └── images/
│       ├── what-is-counselling-logo.png       # Official circular logo
│       ├── james-pearson-signature-logo.png   # Authentic signature mark
│       ├── james-pearson-portrait-1.jpg       # Authentic portrait
│       ├── james-pearson-portrait-2.jpg       # Authentic secondary portrait
│       ├── credentials/                       # Official BACP, NCPS, Lancaster, Psychology Today logos
│       ├── journal/                           # 10 original featured article photographs
│       ├── favicon.png                        # Generated 32x32 brand favicon
│       └── favicon.svg                        # Vector brand favicon
└── README.md
```

---

## 🚀 Local Preview

Because this is a zero-dependency static site, you can preview it immediately using any local web server:

```bash
# Using Python 3:
python -m http.server 8000

# Using Node.js (npx):
npx serve .

# Or simply open index.html directly in any web browser.
```

---

## 🌐 Deploying to GitHub Pages

1. In your GitHub repository, navigate to **Settings** > **Pages**.
2. Under **Build and deployment** > **Source**, select **Deploy from a branch**.
3. Choose branch **`main`** and folder **`/ (root)`**.
4. Click **Save**. Within 1–2 minutes, your website will be live at `https://<username>.github.io/<repository-name>/`.
