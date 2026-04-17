# GPA Calculator

A professional, fully client-side web application for calculating SGPA (Semester Grade Point Average) and CGPA (Cumulative Grade Point Average). Built with HTML, CSS, and vanilla JavaScript, this tool supports customizable grading scales and handles both CIE+SEE mark-based calculations and simple CGPA averaging.

## Features

- **SGPA Calculator**: Convert CIE (Continuous Internal Evaluation) and SEE (Semester End Exam) marks to grade points using institution-specific grading scales.
- **CGPA Calculator**: Compute cumulative GPA by averaging semester SGPAs.
- **Custom Grading Scales**: Define your own mark ranges and corresponding grade points (e.g., 90-100 = 10 points).
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices.
- **Privacy-Focused**: All calculations run entirely in the browser; no data storage or transmission.
- **Educational Resources**: Guides on CGPA vs SGPA, grading systems, and calculation methods.
- **No Dependencies**: Pure vanilla JavaScript, CSS, and HTML. Zero external libraries or build tools required.

## Project Structure

```
d:/GPA Calculator/
├── index.html              # Landing page with calculator previews and resources
├── calculator.html         # Core SGPA/CGPA calculator with customizable grading
├── percentage-converter.html # Marks to percentage/grade conversion tool
├── about.html              # About the project
├── faq.html                # Frequently asked questions
├── cgpa-vs-sgpa.html       # CGPA vs SGPA explanation
├── grading-system-guide.html # Global grading systems overview
├── how-to-calculate-cgpa.html # CGPA calculation guide
├── how-to-calculate-sgpa.html # SGPA calculation guide
├── contact.html            # Contact information
├── privacy-policy.html     # Privacy policy
├── terms.html              # Terms of service
├── disclaimer.html         # Legal disclaimer
└── README.md               # This file
```

## How It Works

### SGPA Calculation (CIE + SEE Method)
1. Define your grading scale (e.g., 90-100 marks = 10 grade points).
2. Input CIE marks (out of 50) and SEE marks (out of 100) per subject.
3. SEE is normalized to out of 50; total marks = CIE + normalized SEE.
4. Grade points are assigned based on total marks and your scale.
5. **Formula**: SGPA = Σ(Grade Points × Credits) / Σ(Credits)

### CGPA Calculation
1. Input SGPA from each semester.
2. **Formula**: CGPA = Average of all SGPAs

## Quick Start

1. Open `index.html` in any modern web browser.
2. Click "Open Calculator" to access the main tool.
3. Customize the grading scale in the settings section.
4. Add subjects and input marks to calculate instantly.

No installation or server required. Fully static and portable.

## Supported Grading Scales

- Default: Indian 10-point scale (O/A+/A/B+/B/C/P/F)
- Fully customizable: Edit min/max marks and grade points directly
- Common scales pre-configured or easily adaptable

## Technical Details

- **Frontend**: HTML5, CSS3 (custom properties, flexbox/grid, responsive design)
- **JavaScript**: Vanilla ES6+ (no frameworks or libraries)
- **Features**: Dynamic form generation, real-time calculations, local storage-free
- **Browser Support**: Chrome 80+, Firefox 75+, Safari 13.1+, Edge 80+
- **Performance**: <100KB total size, instant calculations

## Customization

To adapt for different institutions:

1. Modify grading scale in calculator.html settings.
2. Update grade point mappings in the JavaScript `getGradePoint()` function if needed.
3. Adjust CIE/SEE weightings by changing normalization logic.
4. Customize colors/themes via CSS custom properties.

## Deployment

Deploy as a static site to any hosting service:

```bash
# Netlify/Vercel: Drag &amp; drop the folder
# GitHub Pages: Push to gh-pages branch
# Any static host: Upload all HTML files
```

Current demo: https://gpamastercalc.netlify.app/

## Academic Accuracy

- Matches standard university formulas (VTU, Anna University, etc.)
- Handles credit-weighted averages correctly
- Supports variable credit hours per subject
- Transparent calculation explanations provided

## License

MIT License - Free for personal, educational, and commercial use.

## Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/new-feature`)
3. Commit changes (`git commit -m 'Add new feature'`)
4. Push to branch (`git push origin feature/new-feature`)
5. Open Pull Request

## Support

- [FAQ](faq.html)
- [Contact](contact.html)

---

Built with precision for students worldwide. Calculate accurately, plan strategically.

