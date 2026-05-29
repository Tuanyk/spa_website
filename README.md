# Sweet Beauty Spa — Vietnamese Landing Page

A luxurious, elegant single-page website fully translated to Vietnamese for **Sweet Beauty Spa** (facebook.com/sweetspahn).

**Tagline:** Sweet Beauty Spa – chăm sóc sắc đẹp & thư giãn toàn diện  
**Specialties:** Chuyên da, gội đầu dưỡng sinh, massage body, triệt lông công nghệ cao  
**Location:** Bắc Từ Liêm, Hà Nội

## ✨ What's new (Vietnamese version)
- Complete Vietnamese translation with natural, warm copy
- Updated hero with your exact slogans
- Added prominent **Ưu đãi** (Promotions) section featuring the 3 promotional posters from `temp/`
- Services updated with **Triệt Lông** as a flagship offering + classic spa rituals
- Address changed to Hà Nội (39/41, ngõ 75, Phú Diễn, Bắc Từ Liêm)
- All CTAs and forms fully localized
- Kept the premium elegant design system + lifestyle photos from `assets/`
- Booking modal + lightbox fully translated

## ✨ What was built

- **Fully self-contained** modern landing page (`index.html`)
- Premium feminine-luxury aesthetic with soft blush, cream, rose gold & sage accents
- Custom AI-generated photography (hero, treatments, products, lounge, couples)
- All major conversion sections: Hero, Story, Signature Treatments (6), The Sweet Difference, Gallery, Testimonials, Visit + Contact
- Fully responsive (mobile-first) with beautiful mobile menu
- Booking request modal with elegant form (simulates submission + success state)
- Full-screen image lightbox gallery with keyboard arrows + close
- Smooth scrolling, scroll-aware navbar, subtle hover states
- Direct links to your real Facebook page everywhere that matters

## 🚀 Quick start

1. Open `index.html` directly in any browser (double-click or `open index.html`)
2. Everything works locally with zero setup or build step
3. To deploy: push to GitHub → connect repo to **Cloudflare Pages** (recommended) or Netlify/Vercel

**Note:** The 3 images in `temp/` are used in the new "Ưu đãi" section. Keep them when deploying.

## ✏️ How to customize

### 1. Text & Services
- Open `index.html` and edit directly (everything is in one file)
- Key sections to update: hero slogans, service cards, address, opening hours, testimonials

### 2. Images
- **New brand assets** (in `/temp/`):
  - `logo.png` — Official gold logo with CH crown + butterfly (used in navbar + Visit section)
  - `herobanner.png` — Professional laser treatment hero photo (used as main hero background + gallery)
- Elegant lifestyle photos: `/assets/` (products, couples, massage-hands, lounge)
- Promotional posters: `/temp/1.jpg`, `2.jpg`, `3.jpg` (used in Ưu đãi section)

### 3. Contact & Booking
- All CTAs point to https://www.facebook.com/sweetspahn/ (as requested)
- Booking modal simulates submission (easy to wire to a real form later)

## 📝 CMS Recommendations (for blog posts + easy admin)

Since you plan to deploy to **Cloudflare Pages + GitHub** and want to add blog posts later, here are the **easiest realistic options** (ranked for minimal pain):

### 1. Decap CMS (decapcms.org) — **Recommended starting point (easiest for static + Git)**
- Completely free, open-source, lives inside your repo
- Beautiful admin UI at `yoursite.com/admin`
- Editors write in Markdown → creates real commits on GitHub
- Perfect for a "Posts" collection (blog/journal)
- Works great with Cloudflare Pages (requires one-time GitHub OAuth app setup, ~10 mins)
- No extra hosting or vendor lock-in
- I can set this up for you in ~15 minutes if you want

### 2. Sanity.io — Best editor experience (if you want something more powerful)
- Free plan is very generous
- Gorgeous hosted admin (Studio) with excellent image handling
- Structured content (great for posts with categories, SEO fields, featured images)
- Fetch content via their tiny JS client (works fine on Cloudflare Pages at runtime or build time)
- Very quick to define a "post" schema
- Slightly more moving parts than Decap but fantastic long-term

### 3. Avoid for now
- Payload / Strapi / Directus → require a server (not ideal for pure Cloudflare Pages)
- Ghost → overkill for a simple spa site

**My suggestion:** Let's start with **Decap CMS** (or Sanity if you prefer the nicer UI). Tell me which direction you like and I'll implement the config + a simple blog listing page.

Would you like me to add Decap CMS now?

### 4. Colors & Typography
The design system lives at the top of the `<style>` tag:
```css
--cream: #FDF9F4;
--blush: #F4E6E7;
--rose: #C48A7D;     /* main accent */
--deep: #3F2A2A;     /* rich text */
--sage: #9CA88F;
--gold: #D4B48C;
```

Change these values and the whole site updates instantly.

## 📸 About the photos used

Five high-quality custom images were generated specifically for Sweet Beauty Spa using AI (soft blush & cream luxury spa aesthetic). They are royalty-free for your use.

If you have professional photos from your Facebook page or a photographer, replace them for maximum authenticity and trust.

## 🔗 Important links already in the site

- All "Follow / Message on Facebook" buttons → https://www.facebook.com/sweetspahn/
- Easy to change if you later add Instagram, TikTok, or a booking system

## 🛠 Future ideas (when you're ready)

- Add real booking calendar (Cal.com embed or similar)
- Blog / Journal section (easy with Decap CMS or Sanity)
- Gift card / package sales page
- Before/after gallery (with permission)
- English version toggle (if you ever want bilingual)

## Notes from creation

I attempted to pull detailed information (services, address, phone, about text) directly from your Facebook page. Due to Facebook's heavy JavaScript rendering and anti-scraping protections, only the page name "Sweet Beauty Spa" was reliably retrievable. The site was therefore built with elegant, high-quality placeholder content that matches the premium "Sweet Beauty" positioning you can easily overwrite with your real details.

Everything is intentionally clean and well-commented so you (or a designer/developer) can update it quickly.

---

**Made with care for Sweet Beauty Spa.**  
Open `index.html` and fall in love with your new digital home. 🌸

If you want any changes — different services highlighted, Vietnamese version, new photos, different accent color, booking form connected, etc. — just tell me and I'll update it immediately.
