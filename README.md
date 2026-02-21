# HTA Economic Evaluation Interpretation Session

**Interactive Learning Website** for interpreting economic evaluation results in Health Technology Assessment.

Created for the HTA Workshop at IGGMC, Nagpur | February 24-25, 2026

---

## 🎯 Quick Start

### Online (Recommended)
Visit the live website: [hta.aiimsbhopal.edu.in](#) (when deployed)

### Local Preview
```bash
# Install Quarto
# Download from: https://quarto.org

# Clone/download this repository
cd hta_session

# Preview locally
quarto preview

# The site will open at http://localhost:3456
```

---

## 📁 Website Structure

```
hta_session/
├── index.qmd              # Homepage with navigation
├── session.qmd            # Interactive ICER calculator & tools
├── slides.qmd             # Reveal.js presentation
├── practice.qmd           # 3 practice cases with solutions
├── resources.qmd          # Curated links & tools (30+)
├── about.qmd              # Facilitator info & workshop details
├── _quarto.yml            # Configuration
├── styles.css             # Custom styling
└── README.md              # This file
```

---

## 🚀 Deployment Options

### Option 1: GitHub Pages (Free & Recommended)

```bash
# Initialize git repo
git init
git add .
git commit -m "Initial commit: HTA session website"

# Create GitHub repo called 'hta-session'
# Push to GitHub
git remote add origin https://github.com/yourusername/hta-session.git
git branch -M main
git push -u origin main

# Enable Pages in GitHub:
# Settings → Pages → Source: Deploy from branch → main /docs
```

Site will be available at: `yourusername.github.io/hta-session`

### Option 2: Netlify (Automatic Deployment)

1. Connect GitHub repo to Netlify
2. Set build command: `quarto render`
3. Set publish directory: `docs`
4. Deploy automatically on every push

### Option 3: Self-Hosted
```bash
# Render the site
quarto render

# Upload the 'docs' folder to your web server
# Configure server to serve from /docs
```

---

## 🎓 Features

### Fully Flexible Interactive Tools
✓ ICER calculator (any cost/QALY values)  
✓ CE plane visualization with PSA  
✓ CEAC curves (all quadrants)  
✓ Real-time interpretation  
✓ Handles all quadrants (NE, NW, SE, SW)  

### Comprehensive Resources
✓ Links to HTAIn and PGIMER  
✓ 30+ curated references  
✓ International guidelines  
✓ Video resources  
✓ Software tools & code  

### Presentation Materials
✓ Reveal.js slides (animated)  
✓ PDF download option  
✓ Speaker notes included  
✓ Presentation mode support  

### Learning Materials
✓ 3 practice cases  
✓ Error identification exercises  
✓ Decision frameworks  
✓ Real-world examples  

---

## 📊 Content Overview

### Home Page
- Quick navigation to all sections
- Learning objectives
- Key features
- Links to resources

### Interactive Session
- **Part 1**: ICER Basics with calculator
- **Part 2**: Cost-Effectiveness Plane (all quadrants)
- **Part 3**: WTP Thresholds
- **Part 4**: Case study (Portable Dialysis)
- **Part 5**: Spot-the-error exercises

### Presentation Slides
- 20+ slides in Reveal.js format
- Animated bullet points
- Speaker notes for each slide
- Downloadable as PDF
- Full-screen presentation mode

### Practice Cases
- **Case 1**: HPV vaccination program
- **Case 2**: Generic drug substitution
- **Case 3**: Telemedicine for rural clinics
- All with solutions and interpretation guides

### Resources
- HTAIn portal & "What We Do" resources
- PGIMER health economics courses
- International guidelines (NICE, ISPOR, WHO)
- Software tools (R packages, Excel templates)
- YouTube videos & tutorials
- Research databases & journals

### About Page
- Facilitator biography (Dr. Abhijit P. Pakhare)
- RRC-HTA information
- Workshop details (Feb 24-25, 2026, Nagpur)
- Institutional partners
- Contact information

---

## 🔧 Customization

### Update Facilitator Information
Edit `about.qmd` and `index.qmd`:
```markdown
- Name, position, email
- Institution details
- Research interests
- Contact information
```

### Add Your Own Content
1. Create new `.qmd` files
2. Add to navbar in `_quarto.yml`
3. Include in `index.qmd` navigation

### Change Theme
In `_quarto.yml`, modify:
```yaml
theme: 
  light: cosmo  # Try: default, lux, morph, quartz, simplex, solar, vapor
  dark: darkly  # Try: cyborg, darkly, dracula, superhero
```

### Customize Styling
Edit `styles.css` for custom colors, fonts, spacing

---

## 📱 Browser Support

Works on:
- ✓ Chrome/Edge (latest)
- ✓ Firefox (latest)
- ✓ Safari (latest)
- ✓ Mobile browsers (responsive design)

---

## 📧 Contact & Support

**For questions about the content**:
- Email: [hta@aiimsbhopal.edu.in](mailto:hta@aiimsbhopal.edu.in)
- Facilitator: Dr. Abhijit P. Pakhare

**For technical issues**:
- Check Quarto documentation: [https://quarto.org](https://quarto.org)
- GitHub Issues (if deployed to GitHub)

---

## 📋 File Descriptions

### index.qmd
Homepage with welcome message, quick navigation, learning objectives, and quick-start options for different user types.

### session.qmd
Main interactive learning session with 5 parts:
- ICER calculator with interpretation
- CE plane visualization (all quadrants)
- PSA scatter plots
- CEAC curves
- Real case study
- Error identification exercises
- Feedback form

### slides.qmd
Reveal.js presentation with 20+ slides covering all concepts. Supports speaker notes, animations, and PDF export. Perfect for in-class presentation.

### practice.qmd
Three detailed practice cases:
1. HPV vaccination program (cost-effective)
2. Generic drug substitution (dominant)
3. Telemedicine for rural clinics (moderate cost-effectiveness)

Each includes background, study data, questions, and solutions.

### resources.qmd
Comprehensive resource compilation:
- 30+ curated links
- HTAIn and PGIMER portals
- International guidelines
- Software tools
- Recommended readings
- Video resources
- Quick links table

### about.qmd
Detailed information about:
- Dr. Abhijit P. Pakhare (facilitator)
- RRC-HTA AIIMS Bhopal
- Workshop details
- Faculty involved
- Institutional partners
- Citation instructions

### _quarto.yml
Quarto configuration file specifying:
- Website structure and navigation
- Theme and format options
- Footer information
- Build settings

### styles.css
Custom CSS for styling callout boxes, tables, details sections, and responsive design.

---

## 🎯 Use Cases

### Workshop at IGGMC, Nagpur
- Share link with participants
- Display slides during session
- Participants can explore tools afterward
- Download materials for offline use

### Teaching in Your Institution
- Embed session or slides in your course
- Use practice cases in tutorials
- Direct students to resources
- Customize with your examples

### Self-Study
- Work through session at your own pace
- Practice with interactive tools
- Explore PGIMER courses
- Reference materials as needed

### Research Reference
- Cite the materials in publications
- Link to resources in your papers
- Share with collaborators
- Use as teaching resource

---

## 📝 Citation

If using these materials in teaching or research, please cite:

```bibtex
@misc{Pakhare2026,
  author = {Pakhare, Abhijit P.},
  year = {2026},
  title = {Interpretation of Economic Evaluation Results in {H}ealth {T}echnology {A}ssessment},
  organization = {Regional Resource Centre for HTA, AIIMS Bhopal},
  url = {https://hta.aiimsbhopal.edu.in}
}
```

---

## 📄 License

These materials are provided for educational and training purposes.

---

## 🙏 Acknowledgments

- Department of Health Research, Ministry of Health & Family Welfare, Government of India
- ICMR-NITVAR, Pune (National Coordination)
- HTAIn Network institutions
- All workshop faculty members
- Participants for feedback

---

## ✨ Version History

**v2.1** (February 2026)
- Added Reveal.js presentation slides
- Enhanced resources with 30+ links
- New "About" page with institutional info
- Updated navigation and homepage
- Improved documentation

**v2.0** (February 2026)
- Fully flexible calculators (all quadrants)
- PSA and CEAC for all scenarios
- Interactive session tool
- Practice cases
- Resource compilation

---

**Last Updated**: February 17, 2026  
**Contact**: [hta@aiimsbhopal.edu.in](mailto:hta@aiimsbhopal.edu.in)
