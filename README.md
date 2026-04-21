# Bethel A.M.E. Church — Freehold, NJ

One-page editorial site for Bethel AME — The Church on the Hill.
Built by Chevelle · [bychevelle.com](https://bychevelle.com)

---

## Quick overview

- **Stack:** Static HTML/CSS/JS + Decap CMS + Netlify Identity
- **Editable:** Yes — Pastor Sparks or Sister Corliss (or anyone invited) can edit every section from the admin panel
- **Hosting:** Netlify (auto-deploys on every GitHub commit)
- **Cost:** Free tier covers everything

---

## File structure

```
bethel-ame-freehold/
├── index.html          ← the actual site
├── config.json         ← all editable content (edited via admin panel)
├── README.md           ← this file
├── ASSET-GUIDE.md      ← what photos/logo to upload, and their filenames
├── admin/
│   ├── index.html      ← Decap CMS login page
│   └── config.yml      ← defines what's editable in the admin panel
└── assets/
    └── images/         ← all photos and the logo go here
```

---

## How editing works (for Bethel)

1. Go to **`[your-site].netlify.app/admin/`**
2. Log in with your invited email + password
3. Click **"Edit Site Content"**
4. Every section of the site is editable — headlines, paragraphs, pastor bio, leadership, photos, service times, everything
5. Click **Save** → **Publish** → changes go live in ~30 seconds

No code needed. No risk of breaking the site — the editor only changes content, not the design.

---

## Deployment — step by step (for Chevelle)

### 1. GitHub

- Create a new repo: `bethel-ame-freehold` (private or public — both work)
- Upload all six files + the `assets/images/` folder
- **IMPORTANT:** when uploading `admin/config.yml` and `admin/index.html`, type the full path `admin/config.yml` in the filename field so GitHub creates the folder automatically
- Watch out for the nested-folder bug: the repo should have `admin/` at the root, NOT `admin/admin/`

### 2. Netlify deployment

- Go to Netlify → "Add new site" → "Import from Git"
- Choose the `bethel-ame-freehold` repo
- Build command: **(leave blank)** — this is static HTML
- Publish directory: **(leave blank or type `/`)**
- Click Deploy
- Rename the site URL to something like `bethel-ame-freehold.netlify.app`

### 3. Enable Netlify Identity + Git Gateway

- Site settings → **Identity** → Enable Identity
- Set **Registration preferences** → "Invite only"
- Identity → Services → **Git Gateway** → click "Generate access token in GitHub" → authorize
- Identity → Invite users → add Pastor Sparks's email (`bethelfreehold@aol.com`) and your own to test
- The invite sends a link → they click it → set a password → they're in

### 4. Test the admin panel

- Go to `[site-name].netlify.app/admin/` → should see a login page
- Log in with your invited account
- You should see "✦ Edit Site Content" — click in and test editing a headline → Save → Publish
- Confirm the live site updates (~30 seconds)

### 5. Set up Formspree (for the contact + prayer forms)

- Go to [formspree.io](https://formspree.io) → sign up → create 2 forms:
  1. **Bethel — Contact** (goes to bethelfreehold@aol.com)
  2. **Bethel — Prayer Requests** (goes to bethelfreehold@aol.com)
- Copy the two endpoint URLs (e.g. `https://formspree.io/f/xxxxxxx`)
- In the admin panel → **⚙️ Form Provider** section:
  - Change provider from `demo` to `formspree`
  - Paste the contact endpoint into "Contact Form Action URL"
  - Paste the prayer endpoint into "Prayer Form Action URL"
  - Save → Publish
- Done — forms now deliver to Bethel's inbox

---

## Photo uploads

See `ASSET-GUIDE.md` for the exact list of photos Bethel should upload, their recommended dimensions, and filenames.

All photos go into `assets/images/` via the admin panel's image upload fields. Decap CMS handles the upload automatically — no need to use GitHub directly.

---

## Common edits Bethel will make

| What | Where in admin panel |
|---|---|
| Change service times | ⭐ Hero Section → Service Times |
| Update Pastor's Note | ⛪ Pastor Sparks → Pastor's Note |
| Add a new leadership member | 👥 Leadership Team → Leaders → "Add Leader" |
| Change an event/ministry description | 🤝 Ministries |
| Update contact info | 📍 Plan a Visit + 🔻 Footer |
| Swap photos | Any section with an "Image" field |

---

## Logo note

The site currently uses a placeholder SVG logo that echoes Bethel's colors (navy + gold + sky blue). Once the official Bethel logo is finalized (square or circular, ideally SVG or high-res PNG), upload it via:

- Admin panel → **🏷️ Brand & Logo** → **Church Logo** → upload
- File it as `bethel-logo.png` (or `.svg`) in `assets/images/`

---

## Questions?

Reach out to Chevelle at [bychevelle.com](https://bychevelle.com).
