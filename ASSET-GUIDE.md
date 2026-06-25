# Bethel A.M.E. — Photo & Asset Guide

This guide tells the Bethel team exactly which photos to upload and where. Every photo is uploaded through the **admin panel** — no need to rename perfectly or resize to the exact pixel; these are just recommendations for the cleanest look.

---

## How it works

1. Go to `[your-site].netlify.app/admin/`
2. Log in
3. Each section of the site has an **Image / Photo** field wherever a photo is supported
4. Click the image field → upload → save → publish. Decap CMS handles the rest.

Files land automatically in `assets/images/`. You don't need to touch GitHub.

---

## 🎨 Logo

| What | Suggested filename | Size | Format | Notes |
|---|---|---|---|---|
| Bethel logo (square) | `bethel-logo.png` or `.svg` | 512×512+ | PNG transparent or SVG | Admin → **🏷️ Brand & Logo → Church Logo** |
| Favicon | `favicon.png` | 64×64 | PNG | Optional |

---

## ⭐ Hero section (top of site)

The hero has **two flanking photos** — one on each side of the headline. On mobile, they stack and the headline goes on top. Plus an optional **faded background photo** that sits behind everything.

| Slot | Filename | Size | Aspect | Admin path |
|---|---|---|---|---|
| Left photo | `hero-left.jpg` | 800×1067 | 3:4 portrait | **⭐ Hero → Hero Photo — Left → Photo** |
| Right photo | `hero-right.jpg` | 800×1067 | 3:4 portrait | **⭐ Hero → Hero Photo — Right → Photo** |
| Faded background (optional) | `hero-bg.jpg` | 1800×1200 | Any landscape | **⭐ Hero → Faded Background Photo** |

*Leave the flanking photos blank to see styled gradient placeholders (navy+sky on left, gold on right). The faded background fades to ~10% opacity with a radial mask, so contrast doesn't matter.*

---

## 📖 John 3:16 verse — faded background

Add a photo that fades softly behind the John 3:16 scripture block.

| Slot | Filename | Notes |
|---|---|---|
| Faded background | `john-verse-bg.jpg` | Any landscape photo, will fade to ~12% opacity with radial mask |

*Admin path:* **📖 Faith Verse → Faded Background Photo**

---

## 📜 History timeline

Individual photos can be added to any timeline entry. You don't have to fill every one — just the ones where you have strong images. These three will have the biggest visual impact:

| Timeline entry | Suggested photo | Filename | Aspect |
|---|---|---|---|
| **1787 – The A.M.E. Denomination is Born** | Portrait of Rev. Richard Allen | `timeline-richard-allen.jpg` | 4:3 landscape |
| **1988 – The Church on the Hill** | Bethel exterior on Waterworks Road | `timeline-church-on-hill.jpg` | 4:3 landscape |
| **Today – Beyond the Walls** | Congregation photo | `timeline-today.jpg` | 4:3 landscape |

*Admin path:* **📜 History Timeline → Timeline Entries → [entry] → Photo**

Other timeline items (Squirrel Town 1690s, Bethel Begins 1848, 1867 Incorporated, Peach Orchard Years) can be left photo-free, or add archival/historical images if you have them.

---

## 💬 Buddy Lewis Pull Quote

Add a photo that **fades softly into the cream background** behind the quote — creates a moving watermark effect.

| Slot | Filename | Size | Notes |
|---|---|---|---|
| Faded background | `buddy-lewis-bg.jpg` | 1800×1000 | Any landscape congregation/community photo. Will be heavily faded (12% opacity) so contrast doesn't matter. |

*Admin path:* **💬 Buddy Lewis Pull Quote → Faded Background Photo**

---

## 🎯 Mission & Beliefs

Two cards, each with an optional photo at the top.

| Card | Filename | Aspect | Admin path |
|---|---|---|---|
| Mission card | `mission-photo.jpg` | 16:9 landscape | **🎯 Mission & Beliefs → Mission card photo** |
| Beliefs card | `beliefs-photo.jpg` | 16:9 landscape | **🎯 Mission & Beliefs → Beliefs card photo** |

---

## ⛪ Pastor Sparks — portrait carousel

Upload as many photos of Pastor Sparks as you'd like. They display as a **portrait carousel** — one photo at a time, auto-advancing every 6 seconds, with dots below to jump between them. On phones, swipe left/right.

| Slot | Suggested photo | Filename | Aspect |
|---|---|---|---|
| Slide 1 | Pastor Sparks portrait / headshot | `pastor-1.jpg` | 4:5 portrait |
| Slide 2 | Preaching / in the pulpit | `pastor-2.jpg` | 4:5 portrait |
| Slide 3 | Community / outreach / town hall | `pastor-3.jpg` | 4:5 portrait |
| Slide 4 | With family (Sister Candace + family) | `pastor-4.jpg` | 4:5 portrait |

*Admin path:* **⛪ Pastor Sparks → Pastor Photos → "Add photo"**

💡 **Tip:** If you upload just one photo, the carousel controls hide automatically. If you leave all photos blank, a styled placeholder appears with a **Placeholder Color** dropdown — navy, gold, sky, or green. Good way to build the section while you're still collecting photos.

---

## 👥 Leadership team

Each leader (Rev. Dr. Auguste, Evangelist Acker, Bernadine Wilson-Gibson, Sister Corliss Smith) gets an optional headshot. If no photo is uploaded, the card shows their **initials** in a clean navy-to-sky gradient — still looks great.

| Leader | Filename | Aspect |
|---|---|---|
| Rev. Dr. Cheryl Auguste | `leader-auguste.jpg` | 4:5 portrait |
| Evangelist Gloria Acker | `leader-acker.jpg` | 4:5 portrait |
| Bernadine Wilson-Gibson | `leader-wilson-gibson.jpg` | 4:5 portrait |
| Sister Corliss Smith | `leader-smith.jpg` | 4:5 portrait |

*Admin path:* **👥 Leadership Team → Leaders → [leader] → Photo**

---

## 🤝 Ministries (4 cards)

Four cards — one photo per card at the top of each.

| Ministry | Filename | Aspect |
|---|---|---|
| Lay Organization | `ministry-lay.jpg` | 4:3 landscape |
| Women's Missionary Society | `ministry-wms.jpg` | 4:3 landscape |
| Young People's Division | `ministry-ypd.jpg` | 4:3 landscape |
| Sons of Allen | `ministry-sons.jpg` | 4:3 landscape |

*Admin path:* **🤝 Ministries (4 cards) → Ministry Cards → [card] → Photo**

---

## 📚 Christian Education (Learn. Live. Serve.)

Three class/service cards — one photo each.

| Class | Filename | Aspect |
|---|---|---|
| Youth Church School | `ed-youth.jpg` | 16:10 landscape |
| Adult Church School | `ed-adult.jpg` | 16:10 landscape |
| Morning Worship | `ed-worship.jpg` | 16:10 landscape |

*Admin path:* **📚 Christian Education → Classes / Services → [class] → Photo**

---

## 🏛️ Governance

**No photos or icons** — the 4 board cards display with just text (Small Label, Board Name, Description). Clean and understated.

*Admin path:* **🏛️ Governance → Board Cards → [card]**

---

## 💝 Giving faded background

Three "ways to give" cards (just title + description, no icons). Plus an optional faded background for the whole navy section.

| Slot | Notes |
|---|---|
| Faded background | `giving-bg.jpg` — any landscape photo, will fade to ~8% opacity |

*Admin path:* **💝 Giving → Faded Background Photo**

---

## 📅 Events

### Featured / Upcoming event

One spotlighted event — Pastor Sparks, Sister Corliss, or whoever is admin will update this when a new event is scheduled.

| Slot | Notes |
|---|---|
| Event photo | 4:5 portrait, `event-featured.jpg` |

*Admin path:* **📅 Events → Featured / Upcoming Event → Event Photo**

### Past events

A rolling list — add as many past events as you'd like with photos, date, and description.

| Typical entry | Suggested filename | Aspect |
|---|---|---|
| 2024 Holiday Gala | `past-gala-2024.jpg` | 3:2 landscape |
| 2023 Holiday Gala | `past-gala-2023.jpg` | 3:2 landscape |

*Admin path:* **📅 Events → Past Events → "Add past event"**

---

## 📖 Closing scripture (James 2:17)

Optional faded background photo for the closing verse section.

| Slot | Filename | Notes |
|---|---|---|
| Faded background | `closing-bg.jpg` | Any landscape photo, fades to ~15% opacity with radial mask |

*Admin path:* **📖 Closing Scripture → Faded Background Photo**

---

## 📍 Plan a Visit — faded background

Optional faded background photo for the Plan a Visit section (address, service times, map).

| Slot | Filename | Notes |
|---|---|---|
| Faded background | `plan-visit-bg.jpg` | Any landscape photo, fades to ~10% opacity |

*Admin path:* **📍 Plan a Visit → Faded Background Photo**

---

## Filename rules

- ✅ **Lowercase only** — `pastor-1.jpg`, not `Pastor_1.JPG`
- ✅ **Hyphens for spaces** — `hero-left.jpg`, not `hero left.jpg`
- ✅ **Keep the extension** — `.jpg` for photos, `.png` for graphics with transparency, `.svg` for vector logos
- ❌ **No special characters** — no apostrophes, ampersands, parentheses, emojis, or quotes

---

## Aspect ratios — quick reference

- **1:1** square (Instagram post size) → pastor collage tiles
- **4:5** portrait (Instagram portrait post) → leadership headshots, featured event
- **3:4** portrait → hero flanking photos
- **4:3** landscape → timeline, ministry cards
- **16:10** / **3:2** / **16:9** landscape → education classes, past events, background photos

---

## If you don't have a photo yet

**Leave it blank.** Every section has a **styled placeholder** built in — soft navy, gold, or sky-blue panels with subtle captions. The site looks finished even without a single photo uploaded. You can add photos over time as you collect them.

---

## Questions?

Reach out to Chevelle — or reply to the handoff message with questions.
