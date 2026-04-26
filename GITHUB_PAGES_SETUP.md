# Deploy to GitHub Pages (5 Minutes)

## Step-by-Step: Make Your Tool Live on the Web

### **Step 1: Create a GitHub Account (if you don't have one)**

1. Go to [github.com](https://github.com)
2. Click **Sign up**
3. Enter email, create password, username
4. Verify email
5. Choose free plan

---

### **Step 2: Create a New Repository**

1. On GitHub homepage, click **+ New** (top-left corner)
2. Fill in:
   - **Repository name:** `SyllabusAutonomyAssistant`
   - **Description:** "Free OER tool for syllabus revision and BOS compliance"
   - **Visibility:** **PUBLIC** (required for GitHub Pages)
   - **Add README:** ✓ (we'll replace it)
3. Click **Create repository**

---

### **Step 3: Upload Files (Easiest Method)**

**Option A: Upload via GitHub Website (Recommended for Beginners)**

1. In your new repo, click **Add file** → **Upload files**
2. Drag and drop:
   - `SyllabusAutonomyAssistant.html` → Rename to `index.html` (important!)
   - `README.md`
3. Click **Commit changes**

**Option B: Use Git Command Line (For Experienced Users)**

```bash
# On your computer
git clone https://github.com/YOUR-USERNAME/SyllabusAutonomyAssistant.git
cd SyllabusAutonomyAssistant

# Copy your HTML file and rename it
cp SyllabusAutonomyAssistant.html index.html
cp README.md README.md

# Push to GitHub
git add .
git commit -m "Initial release: Free Version 1.0"
git push origin main
```

---

### **Step 4: Enable GitHub Pages**

1. In your repo, go to **Settings** (top-right)
2. Scroll to **Pages** (left sidebar)
3. Under "Build and deployment":
   - **Source:** Select **Deploy from a branch**
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Click **Save**

You'll see: *"Your site is live at: https://YOUR-USERNAME.github.io/SyllabusAutonomyAssistant/"*

---

### **Step 5: Test Your Live Tool**

1. Wait 30 seconds for deployment to complete
2. Click the link provided, or visit:
   ```
   https://YOUR-USERNAME.github.io/SyllabusAutonomyAssistant/
   ```
3. Your tool should load instantly!

---

## ✅ You're Done!

Your tool is now **live on the internet** and **free to share** with:
- Your college website
- Email to faculty
- WhatsApp, social media
- EngageCSEdu submission
- SIGCSE conference

---

## 📝 Copy the Link to Share

```
https://YOUR-USERNAME.github.io/SyllabusAutonomyAssistant/
```

Replace `YOUR-USERNAME` with your GitHub username.

**Example:**
```
https://krishnaveni-drcv.github.io/SyllabusAutonomyAssistant/
```

---

## 🔄 Update Your Tool Later

To add new features or fix bugs:

**Option A: Via GitHub Website**
1. Click the file you want to edit (e.g., `index.html`)
2. Click the **✏️ Edit** button
3. Make changes
4. Click **Commit changes**
5. Wait 30 seconds → Your live site updates automatically!

**Option B: Via Git**
```bash
# Edit files locally
git add .
git commit -m "Update: description of changes"
git push origin main
# Wait 30 seconds for deployment
```

---

## 🔒 Data Privacy

Your GitHub repo is public (people can see the code), but:
- ✅ The tool runs **entirely in users' browsers**
- ✅ **No data** is sent to any server
- ✅ **No tracking** or analytics
- ✅ Completely **private** for users

---

## 📞 Troubleshooting

### **Site not live after 5 minutes?**

1. Check **Settings** → **Pages** → Is it enabled?
2. Confirm branch is `main` and folder is `/ (root)`
3. Hard refresh your browser: `Ctrl+Shift+R` (Windows) or `Cmd+Shift+R` (Mac)

### **Links or images broken?**

Make sure all files are in the repo root (same folder as `index.html`).

### **Want a custom domain?**

GitHub Pages supports custom domains—see [GitHub Docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

---

## 🎉 Share Your Success!

Once live, you can:

1. **Email faculty:**
   ```
   Dear Colleagues,
   
   The Syllabus Autonomy Assistant for PRE-BOS is now available:
   https://YOUR-USERNAME.github.io/SyllabusAutonomyAssistant/
   
   Use it to streamline your syllabus revisions for BOS approval.
   
   Best,
   Dr. [Your Name]
   ```

2. **Add to your college website**
3. **Submit to EngageCSEdu** (link in README)
4. **Share on social media**

---

## 🚀 Next: Alternative Hosting (Optional)

If you want to explore other options:

- **Netlify:** Free, easy (see README.md for steps)
- **Vercel:** Free, fast (see README.md for steps)
- **Your college server:** If IT can host static HTML

---

**That's it! Your tool is live. Congratulations! 🎊**

© Dr. C. V. Krishnaveni | CC BY 4.0 | OER
