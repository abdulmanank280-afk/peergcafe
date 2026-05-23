PEER G CAFE - Website Source Code Extraction
==============================================
Source URL: https://peergcafe.base44.app/
Extracted: 2026-05-23

FILES LIST:
===========

1. index.html           - Full rendered HTML of the HOME page (includes all DOM elements, inline scripts, styles)
2. menu.html            - Full rendered HTML of the /menu page
3. reservations.html    - Full rendered HTML of the /reservations page
4. index-BXWP_SDz.js   - Main JavaScript application bundle (Vite/React SPA - 639KB)
5. badge.js             - Base44 badge script (231KB)
6. index-BMraYWYB.css   - Main CSS stylesheet (77KB)
7. manifest.json        - PWA manifest file

INLINE SCRIPTS (embedded in HTML):
==================================

1. Page View Tracker (type="module"):
   - Tracks page views via history.pushState, replaceState, and popstate
   - Posts to /api/app-logs/{appId}/log-user-in-app/{pageName}
   - App ID: 6a104c3a0090920bcd369500

2. Schema.org WebSite (type="application/ld+json"):
   - Name: PEER G CAFE
   - URL: https://peergcafe.base44.app

3. Schema.org Organization (type="application/ld+json"):
   - Name: PEER G CAFE
   - Logo: https://media.base44.com/images/public/6a104c3a0090920bcd369500/...
   - URL: https://peergcafe.base44.app

INLINE STYLES (embedded in HTML):
=================================

- Badge spinner animation (@keyframes badge-spin)
- Fade-in animation (@keyframes base44-fade-in)
- Scale-in animation (@keyframes base44-scale-in)

EXTERNAL IMAGE REFERENCES:
===========================

Gallery:
- https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?w=1200&q=80 (hero bg)
- https://images.unsplash.com/photo-1501339847302-ac426a4a7cbb?w=900&q=85 (main room)
- https://images.unsplash.com/photo-1559925393-8be0ec4767c8?w=700&q=80 (the bar)
- https://images.unsplash.com/photo-1554118811-1e0d58224f24?w=700&q=80 (morning ritual)
- https://images.unsplash.com/photo-1445116572660-236099ec97a0?w=700&q=80 (quiet corner)
- https://images.unsplash.com/photo-1600093463592-8e36ae95ef56?w=700&q=80 (baked fresh daily)

Menu Items:
- https://jasminecooking.com/wp-content/uploads/2025/11/kashmiri-pink-chai-pistachio-hero.jpg (Kashmiri Chai)
- https://images.unsplash.com/photo-1553530979-7ee52a2670c4?auto=format&fit=crop&w=600&q=80 (Chiku Smoothie)
- https://images.unsplash.com/photo-1579954115545-a95591f28bfc?auto=format&fit=crop&w=600&q=80 (Banana Smoothie)
- https://images.unsplash.com/photo-1623065422902-30a2d299bbe4?auto=format&fit=crop&w=600&q=80 (Mango Smoothie)
- One base64-encoded image (Regular Tea/Chai)

Favicon:
- https://media.base44.com/images/public/6a104c3a0090920bcd369500/90d563dc1_686497200_122096176143302008_3720842246657470443_n.jpg

TECHNOLOGY STACK:
=================

- React (SPA via Vite bundler)
- Tailwind CSS (utility-first CSS framework)
- Lucide React (SVG icon library)
- Base44 platform (app hosting)
- PWA support (manifest.json, standalone display)
