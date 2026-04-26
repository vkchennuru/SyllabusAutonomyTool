# Syllabus Autonomy Assistant for PRE-BOS

![Version](https://img.shields.io/badge/version-1.0_FREE-blue) ![License](https://img.shields.io/badge/license-CC%20BY%204.0-green) ![OER](https://img.shields.io/badge/OER-Open%20Educational%20Resource-brightgreen)

## 📖 Overview

**Syllabus Autonomy Assistant for PRE-BOS** is a free, open-source tool designed for faculty at autonomous colleges to streamline syllabus revision, compliance checking, and learning outcome mapping for Board of Studies (BOS) approval processes.

Built as an **Open Educational Resource (OER)** under **CC BY 4.0**, this tool is free to use, modify, and distribute.

### 🎯 Key Features (Free Version 1.0)

- ✅ Upload APSCHE-approved syllabus (PDF)
- ✅ Select subject type: CS / Science / Commerce / Arts
- ✅ Choose revision intensity: 5%, 10%, 15%, 20%
- ✅ Auto-generate additions & deletions with justifications
- ✅ Generate CO–PO (Course Outcome–Program Outcome) mapping
- ✅ Export to Excel (Phase 2)
- ✅ Bright, accessible UI (large fonts, high contrast)

### 🚀 Development Roadmap

| Phase | Timeline | Features |
|-------|----------|----------|
| **1** | Q2 2026 | Python/Streamlit app, Gemini API integration, PDF parsing |
| **2** | Q2–Q3 2026 | Excel template export, multi-sheet output |
| **3** | Q3 2026 | Subject-wise intelligence (programming, theory, labs, commerce, humanities) |
| **4** | Q3–Q4 2026 | GitHub OER release, documentation, community framework |

---

## ⚡ Quick Start

### **Option 1: Use Online (No Installation Needed)**

Simply open the tool in any modern web browser:

```
1. Download or clone this repository
2. Open `SyllabusAutonomyAssistant.html` in your browser (double-click the file)
3. Start using immediately—no server required!
```

**Browser Requirements:**
- Chrome 90+ / Firefox 88+ / Safari 14+ / Edge 90+
- JavaScript enabled (enabled by default)
- 5 MB free storage (for local browser functionality)

---

### **Option 2: Deploy on GitHub Pages (Free Hosting)**

Host the tool publicly so students and colleagues can access it online.

#### **Step 1: Create a GitHub Repository**

```bash
# Create new repo on GitHub.com
# Name: SyllabusAutonomyAssistant
# Description: "Free OER tool for syllabus revision and BOS compliance"
# Make it PUBLIC
# Initialize with README (we'll replace it)
```

#### **Step 2: Clone & Setup Locally**

```bash
# Clone the repo to your computer
git clone https://github.com/YOUR-USERNAME/SyllabusAutonomyAssistant.git
cd SyllabusAutonomyAssistant

# Copy the HTML file into the repo
cp SyllabusAutonomyAssistant.html index.html

# Copy this README
cp README.md README.md
```

#### **Step 3: Push to GitHub**

```bash
git add .
git commit -m "Initial release: Free Version 1.0"
git push origin main
```

#### **Step 4: Enable GitHub Pages**

In your GitHub repo:
1. Go to **Settings** → **Pages**
2. Select **Deploy from a branch**
3. Branch: `main` | Folder: `/ (root)`
4. Click **Save**

**Your tool is now live at:**
```
https://YOUR-USERNAME.github.io/SyllabusAutonomyAssistant/
```

Share this link with your college and students!

---

### **Option 3: Deploy on Free Hosting Services**

If you prefer not to use GitHub Pages:

#### **Netlify (Recommended for ease)**

```bash
# 1. Push code to GitHub (Steps 1–3 above)

# 2. Go to netlify.com → Sign up (free)

# 3. Click "New site from Git"
#    Select GitHub repo
#    Build settings: Leave blank (static site)
#    Deploy!

# Your site: https://YOUR-SITE-NAME.netlify.app
```

#### **Vercel**

```bash
# 1. Go to vercel.com → Sign up (free)

# 2. Import GitHub repo

# 3. Default settings work—click Deploy

# Your site: https://YOUR-PROJECT.vercel.app
```

#### **Firebase Hosting**

```bash
npm install -g firebase-tools
firebase login
firebase init hosting
firebase deploy

# Your site: https://YOUR-PROJECT.firebaseapp.com
```

---

## 📂 Repository Structure

```
SyllabusAutonomyAssistant/
├── index.html                    # Main tool (rename from HTML file)
├── README.md                     # This file
├── LICENSE                       # CC BY 4.0 license
├── docs/
│   ├── INSTALLATION.md          # Detailed setup guide
│   ├── USER_GUIDE.md            # How to use the tool
│   ├── ROADMAP.md               # Development phases
│   └── SCREENSHOTS.md           # UI screenshots
├── phase-plans/
│   ├── PHASE_1_STREAMLIT.md     # Streamlit implementation plan
│   ├── PHASE_2_EXCEL.md         # Excel export details
│   ├── PHASE_3_INTELLIGENCE.md  # Subject-wise features
│   └── PHASE_4_RELEASE.md       # OER release checklist
└── .gitignore                   # Git ignore file
```

---

## 💻 Development (For Contributors)

### **Prerequisites**

- Git installed ([git-scm.com](https://git-scm.com))
- Text editor (VS Code, Sublime, etc.)
- GitHub account (free at github.com)

### **Fork & Contribute**

```bash
# 1. Fork the repo on GitHub

# 2. Clone your fork
git clone https://github.com/YOUR-USERNAME/SyllabusAutonomyAssistant.git
cd SyllabusAutonomyAssistant

# 3. Create a feature branch
git checkout -b feature/my-improvement

# 4. Make changes, test in browser

# 5. Commit & push
git add .
git commit -m "Add: [description of change]"
git push origin feature/my-improvement

# 6. Create Pull Request on GitHub
```

### **For Phase 1–4 Development**

See `/phase-plans/` directory for detailed implementation guides.

---

## 🧪 Testing

### **Local Testing**

```bash
# 1. Open the HTML file in your browser
#    File → Open File → Select index.html

# 2. Test all tabs:
#    - FREE TOOL: Upload form, subject selection, change intensity
#    - FEATURES & ROADMAP: Phase cards, feature boxes
#    - ABOUT: Creator info, links

# 3. Test interactivity:
#    - Click tab buttons
#    - Click "GENERATE" buttons
#    - Check output display
```

### **Browser Compatibility**

Test on multiple browsers:

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 90+ | ✅ Fully supported |
| Firefox | 88+ | ✅ Fully supported |
| Safari | 14+ | ✅ Fully supported |
| Edge | 90+ | ✅ Fully supported |
| IE 11 | - | ❌ Not supported |

---

## 🎨 Customization

### **Change College Name**

Edit `index.html`, find this line:

```html
<div class="college-info">SKR & SKR Government College for Women (Autonomous) | Kadapa, AP</div>
```

Replace with your college name.

### **Change Principal Name**

Find this line in the ABOUT tab:

```html
<strong>Dr. V. Saleem Basha</strong><br/>
Principal<br/>
SKR & SKR Government College for Women (Autonomous)<br/>
```

Update with your principal's details.

### **Change Creator Attribution**

Find this line in footer:

```html
© Dr. C. V. Krishnaveni | CC BY 4.0 International License
```

If you're using/modifying, update to:

```html
Original: Dr. C. V. Krishnaveni | CC BY 4.0 | Modified by [Your Name]
```

### **Customize Colors**

Edit CSS variables at the top of the `<style>` section:

```css
:root {
    --primary: #1a472a;           /* Dark green → Change this */
    --accent: #d4a574;            /* Gold → Change this */
    --bg-light: #faf8f3;          /* Light cream → Change this */
    /* ... other colors ... */
}
```

---

## 📱 Accessibility Features

✅ Large fonts (1.1rem–3.2rem)  
✅ High contrast (text-dark on light backgrounds)  
✅ Semantic HTML (screen reader friendly)  
✅ Responsive design (mobile, tablet, desktop)  
✅ No external dependencies (works offline)  

---

## 🔐 Data & Privacy

**No data collection.** This tool:
- ✅ Runs entirely in your browser
- ✅ Does not send files to any server
- ✅ Does not store data online
- ✅ Works offline (after first load)

All processing is **local to your device**.

---

## 📄 License

This work is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

You are free to:
- ✅ **Use** the tool for any purpose
- ✅ **Modify** the code for your needs
- ✅ **Distribute** copies to others
- ✅ **Adapt** for commercial use

**With attribution:**
- Include the original creator: "© Dr. C. V. Krishnaveni"
- Link to this license: https://creativecommons.org/licenses/by/4.0/
- Indicate if changes were made

See [LICENSE](LICENSE) file for full details.

---

## 👥 Creator & Contributors

### **Creator**

**Dr. C. V. Krishnaveni**  
Lecturer in Computer Science & Head of Department  
IQAC Coordinator  
SKR & SKR Government College for Women (Autonomous)  
Kadapa, Andhra Pradesh, India  

📧 Blog: [cvkrishnaveni.blogspot.com](https://cvkrishnaveni.blogspot.com)  
🔗 Google Scholar: [GQrjgHYAAAAJ](https://scholar.google.com/citations?user=GQrjgHYAAAAJ)  

### **Principal**

**Dr. V. Saleem Basha**  
Principal  
SKR & SKR Government College for Women (Autonomous)  
Kadapa, Andhra Pradesh, India  

### **Contributing**

Contributions are welcome! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m "Add: description"`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

Please follow the [Code of Conduct](CODE_OF_CONDUCT.md).

---

## 🐛 Issues & Feedback

Found a bug? Have a feature request?

1. **Check existing issues** on GitHub Issues
2. **Create a new issue** with:
   - Browser & OS
   - Steps to reproduce
   - Expected vs. actual behavior
   - Screenshots (if applicable)

---

## 📚 Documentation

- **[USER_GUIDE.md](docs/USER_GUIDE.md)** — How to use the tool
- **[INSTALLATION.md](docs/INSTALLATION.md)** — Detailed setup for different platforms
- **[ROADMAP.md](docs/ROADMAP.md)** — Development phases & timeline
- **[PHASE_1_STREAMLIT.md](phase-plans/PHASE_1_STREAMLIT.md)** — Backend implementation guide

---

## 🎓 Educational Use

This tool is designed for:

- **Faculty** at autonomous colleges revising syllabi for BOS approval
- **IQAC coordinators** documenting compliance and outcomes
- **Students** understanding syllabus design and learning outcomes
- **Researchers** studying pedagogical innovation and curriculum design

Classroom-tested at:
- **Madhu Educational Academy** (MSME: UDYAM-AP-05-0079178), Kadapa, AP

---

## 🌐 Deployment Checklist

Before going live:

- [ ] Repository created on GitHub (PUBLIC)
- [ ] README.md matches your college/institution
- [ ] index.html contains correct principal name
- [ ] Creator attribution updated (if modified)
- [ ] GitHub Pages OR alternative hosting configured
- [ ] URL tested in 3+ browsers
- [ ] Shared with faculty & students
- [ ] Submitted to EngageCSEdu (for ACM recognition)

---

## 🚀 Next Steps

### **Immediate (Q2 2026)**

1. Upload this to GitHub (this repo)
2. Test on GitHub Pages or Netlify
3. Share the live URL with your college
4. Document classroom usage at Madhu Academy
5. Gather feedback from faculty users

### **Phase 1 (Q2 2026)**

Start Streamlit backend:
- Python 3.8+
- Libraries: `streamlit`, `pypdf2`, `google-generativeai`
- See [PHASE_1_STREAMLIT.md](phase-plans/PHASE_1_STREAMLIT.md)

### **EngageCSEdu Submission (June 2026)**

- Document classroom testing results
- Prepare 3-page companion paper
- Submit to engagecsedu@acm.org

---

## 📞 Support

**Questions?**

- 📧 Email: [Your Institution Email]
- 🐙 GitHub Issues: [This Repo/Issues](https://github.com/YOUR-USERNAME/SyllabusAutonomyAssistant/issues)
- 📖 Documentation: See `/docs/` folder

---

## 🙏 Acknowledgments

- **APSCHE** (Andhra Pradesh State Council of Higher Education) for framework
- **ACM EngageCSEdu** for OER publication platform
- **SKR College** for institutional support
- **Madhu Educational Academy** for classroom testing

---

## 📊 Statistics & Metrics

Track your impact:

```
GitHub Stars: [ ]
Forks: [ ]
Issues: [ ]
Contributors: [ ]
GitHub Pages Views: [ ]
EngageCSEdu Downloads: [ ] (post-publication)
```

---

## 📝 Citation

If you use or modify this tool, please cite:

```bibtex
@software{krishnaveni2026syllabusautonomy,
  author = {Krishnaveni, C. V.},
  title = {Syllabus Autonomy Assistant for PRE-BOS: Free OER Tool for Autonomous College Syllabi},
  year = {2026},
  url = {https://github.com/YOUR-USERNAME/SyllabusAutonomyAssistant},
  license = {CC BY 4.0},
  institution = {SKR \& SKR Government College for Women (Autonomous), Kadapa, AP, India}
}
```

---

## 📅 Version History

### **v1.0 (April 2026)**
- ✅ Free version HTML tool released
- ✅ Interactive PDF upload interface
- ✅ Subject type selection (CS/Science/Commerce/Arts)
- ✅ Change intensity calibration (5%/10%/15%/20%)
- ✅ CO–PO mapping scaffold
- ✅ Bright, accessible UI
- ✅ GitHub OER ready

### **v1.1 (Q2 2026) — Planned**
- Python/Streamlit backend
- Actual PDF parsing
- Gemini API integration
- Excel export

### **v2.0 (Q3 2026) — Planned**
- Subject-wise intelligence
- Bloom's taxonomy integration
- BOS minutes draft generation

---

## ⭐ Show Your Support

If you find this tool useful:

- ⭐ **Star this repository** on GitHub
- 🍴 **Fork and contribute** improvements
- 📢 **Share** with other faculty
- 💬 **Leave feedback** via Issues

---

**Made with ❤️ for autonomous college faculty**

CC BY 4.0 — Open Educational Resource  
© Dr. C. V. Krishnaveni, 2026
