# 🚀 Complete Deployment Guide: 3 Ways to Launch Your Tool

Choose the option that best fits your needs.

---

## 📊 Quick Comparison

| Option | Setup Time | Cost | Best For | Skill Level |
|--------|-----------|------|----------|-------------|
| **GitHub Pages** | 5 min | FREE | Faculty, small orgs | Beginner |
| **Netlify** | 10 min | FREE | Teams, custom domains | Beginner |
| **Local Browser** | 1 min | FREE | Testing, offline use | Beginner |

---

## ✅ Option 1: GitHub Pages (RECOMMENDED FOR YOU)

**Best for:** Academic institutions, OER distribution, EngageCSEdu submission

### Why Choose This?

- ✅ **Completely free** forever
- ✅ **Version control** (track changes)
- ✅ **Perfect for ACM/OER** communities
- ✅ **No server** required
- ✅ **Automatic SSL** (HTTPS)
- ✅ **Shows technical credibility**

### Setup (5 minutes)

```bash
# 1. Create GitHub account at github.com (free)

# 2. Create new repository:
#    - Name: SyllabusAutonomyAssistant
#    - Visibility: PUBLIC
#    - Add README: YES

# 3. Upload files via GitHub website:
#    - Click "Add file" → "Upload files"
#    - Drag/drop index.html, README.md, LICENSE
#    - Commit changes

# 4. Enable Pages:
#    - Settings → Pages
#    - Source: main branch / root folder
#    - Save

# 5. Your site is live!
#    https://YOUR-USERNAME.github.io/SyllabusAutonomyAssistant/
```

### After Launch

```bash
# Update the tool anytime:
git clone https://github.com/YOUR-USERNAME/SyllabusAutonomyAssistant.git
cd SyllabusAutonomyAssistant

# Edit index.html in your editor

# Push updates:
git add index.html
git commit -m "Update: [description]"
git push origin main

# Site updates in 30 seconds automatically!
```

### URL Format

```
https://YOUR-USERNAME.github.io/SyllabusAutonomyAssistant/
```

**Example:**
```
https://krishnaveni-cv.github.io/SyllabusAutonomyAssistant/
```

---

## ✅ Option 2: Netlify (EASIEST FOR BEGINNERS)

**Best for:** Non-technical users, custom domains, zero configuration

### Why Choose This?

- ✅ **Drag-and-drop** deploy
- ✅ **No Git required**
- ✅ **Free custom domain** available
- ✅ **Better UI** than GitHub
- ✅ **Automatic SSL**

### Setup (10 minutes)

```bash
# 1. Go to netlify.com

# 2. Sign up (free) with GitHub account

# 3. Click "Add new site" → "Deploy manually"

# 4. Drag & drop your files:
#    - index.html
#    - README.md (optional)
#    - LICENSE (optional)

# 5. Netlify generates your URL
#    https://YOUR-SITE-NAME.netlify.app
```

### Update the Tool

```bash
# 1. Edit index.html on your computer

# 2. Go to Netlify dashboard

# 3. Drag & drop updated files

# Site updates instantly!
```

### Custom Domain (Optional)

```
netlify.com dashboard → Domain settings → Add custom domain
```

---

## ✅ Option 3: Local Browser (FOR TESTING)

**Best for:** Offline use, personal testing, no internet required

### Setup (1 minute)

**Windows:**
1. Find `SyllabusAutonomyAssistant.html` file
2. Right-click → Open with → Chrome/Firefox
3. Done! Tool loads instantly

**Mac:**
1. Find `SyllabusAutonomyAssistant.html` file
2. Double-click
3. Opens in default browser
4. Done!

**Linux:**
```bash
# Terminal
firefox SyllabusAutonomyAssistant.html
# or
google-chrome SyllabusAutonomyAssistant.html
```

### No Internet Needed

Once loaded, the tool works **completely offline**. Share the HTML file via:
- Email
- USB drive
- WhatsApp
- Shared folder

---

## 🎓 RECOMMENDED WORKFLOW FOR YOU

### Phase 1: This Week

```
1. Upload to GitHub Pages (5 minutes)
   → Test the link works
   → Share with your college

2. OR Deploy to Netlify (10 minutes)
   → Both work—choose one or both

3. Test on multiple browsers:
   - Chrome ✅
   - Firefox ✅
   - Safari (on Mac) ✅
```

### Phase 2: After Testing (Week 2)

```
1. Use the live link in emails to faculty
2. Collect feedback from users
3. Document usage (for EngageCSEdu submission)
4. Make improvements as needed
```

### Phase 3: EngageCSEdu Submission (June)

```
1. Include live link in your submission
2. Mention "Classroom-tested at Madhu Academy"
3. Highlight "Freely accessible via GitHub Pages"
```

---

## 🔗 Share Your Live Tool

Once deployed, you can share:

**Email to faculty:**
```
Subject: Free Syllabus Tool for BOS Revision

Dear Colleagues,

The Syllabus Autonomy Assistant is now available:
[Your Live URL]

Features:
- Upload APSCHE syllabus
- Auto-generate additions & deletions
- CO–PO mapping
- Export to Excel (coming soon)

Completely free and open-source.

Best regards,
Dr. [Your Name]
```

**WhatsApp/Social Media:**
```
🎓 New! Syllabus Autonomy Assistant
Free tool for autonomous college syllabi
Upload → Select subject → Generate additions
[Your Live URL]
#OER #HigherEd #SyllabusDesign
```

**College Website:**
```
Link in your dept page:
"Resources" → "Syllabus Tool"
[Your Live URL]
```

---

## ✅ Platform Comparison Details

### GitHub Pages

**Pros:**
- Free, permanent hosting
- Version control built-in
- Perfect for academic use
- Shows on your GitHub profile
- Supports custom domains
- Great for portfolio

**Cons:**
- Requires GitHub account
- Slight learning curve with Git
- URL includes GitHub username

**Best for:**
- Faculty (academic credibility)
- OER communities
- ACM submissions

### Netlify

**Pros:**
- Easiest setup (drag & drop)
- Beautiful dashboard
- Free custom domain setup
- Better SEO tools
- Supports forms (for future versions)

**Cons:**
- Requires Netlify account
- Less transparent version control
- Free tier has limits (but sufficient)

**Best for:**
- Non-technical users
- Wanting professional URL
- Teams/organizations

### Local Browser

**Pros:**
- Zero setup
- No internet required
- Total privacy
- Works offline
- Can share via email/USB

**Cons:**
- Not accessible from web
- Hard to update for all users
- No version control

**Best for:**
- Personal use
- Testing before deployment
- Offline workshops

---

## 🐛 Troubleshooting

### GitHub Pages Site Not Live?

```bash
# Check these in order:

# 1. Is repo PUBLIC?
#    Settings → Check visibility = Public

# 2. Is Pages enabled?
#    Settings → Pages → Source = main branch

# 3. Wait 1 minute and refresh
#    Ctrl+Shift+R (hard refresh)

# 4. Check Actions tab for errors
#    GitHub Actions → Latest run → Check logs
```

### Netlify Not Showing Latest Version?

```bash
# Hard refresh in browser
# Ctrl+Shift+R (Windows)
# Cmd+Shift+R (Mac)

# Or clear cache:
# 1. Go to Netlify dashboard
# 2. Click "Clear cache & redeploy"
```

### File Not Loading Correctly?

**Check HTML file path:**
```html
<!-- ✅ CORRECT (in same folder)-->
<img src="image.png">

<!-- ❌ WRONG (won't work) -->
<img src="/Users/yourname/Desktop/image.png">
```

---

## 🔐 Security & Privacy

**Your tool is completely safe:**

- ✅ **No files uploaded** to servers
- ✅ **No cookies or tracking**
- ✅ **No external API calls** (currently)
- ✅ **No data collection**
- ✅ **100% local processing** in browser
- ✅ **Runs on HTTPS** (encrypted)

Users' uploaded syllabi:
- ⚠️ **Not** sent anywhere (Phase 1 will add processing)
- ⚠️ **Stay local** on their device
- ⚠️ **Can clear** browser cache anytime

---

## 📈 Monitor Your Tool's Usage

### GitHub Pages

```bash
# Check repo traffic:
1. GitHub.com → Your repo
2. Insights → Traffic
3. See visitors, referrers, clones
```

### Netlify

```bash
# Check analytics:
1. Netlify.com → Dashboard
2. Analytics tab
3. See page views, bandwidth
```

---

## 🚀 Going Further (Optional)

### Add Analytics (Non-Intrusive)

If you want to track usage *without collecting personal data*:

**Option A: GitHub Insights** (built-in)
- Automatic, no code needed
- Shows page views & referrers

**Option B: Plausible Analytics** (privacy-first)
```html
<script defer data-domain="yoursite.netlify.app" 
        src="https://plausible.io/js/script.js"></script>
```
- Free tier: 10k visitors/month
- GDPR compliant
- No cookies

---

## 📝 Deployment Checklist

Before announcing your tool:

- [ ] Test on GitHub Pages / Netlify / Local
- [ ] Verify all tabs work (Free Tool, Features, About)
- [ ] Test on 3+ browsers (Chrome, Firefox, Safari)
- [ ] Check on mobile (phone/tablet)
- [ ] Verify links work (creator bio, links in About)
- [ ] Update college name & principal name
- [ ] Share link with colleagues
- [ ] Document who's using it
- [ ] Prepare for EngageCSEdu submission

---

## 🎉 You're Ready!

Pick **GitHub Pages** (recommended) and you'll be live in **5 minutes**.

**Next Step:** Go to [GITHUB_PAGES_SETUP.md](GITHUB_PAGES_SETUP.md) for detailed walkthrough.

---

**Questions?** See README.md for more info.

© Dr. C. V. Krishnaveni | CC BY 4.0 | OER
