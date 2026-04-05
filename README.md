# [ummadiviany.github.io](https://ummadiviany.github.io)
> Personal website of Vinay Ummadi - Graduate Student in Medical Imaging and Informatics at IIT Kharagpur

## Website Structure

```
.
├── index.html                  # Homepage - profile, news, publications
├── bio/
│   └── index.html              # Bio/CV page - education, experience
├── projects/
│   ├── index.html              # Projects listing
│   ├── agriculture-application-robot/
│   ├── ai-based-telepathology/
│   └── diabetic-retinopathy-grading/
├── publications/
│   └── index.html              # Publications page
├── assets/
│   ├── css/main.css            # Main stylesheet
│   ├── js/                     # JavaScript files
│   ├── img/                    # Images
│   └── docs/                   # Documents (PDFs)
└── CNAME                       # Custom domain (if applicable)
```

## How to Update Website

### Update Profile Information (index.html)
- **Profile Image**: Replace `assets/img/profile.jpeg`
- **Bio Text**: Edit the `<div class="clearfix">` section in `index.html`
- **Contact Links**: Update social media links in the `<div class="social">` section

### Update News Section
- Edit the `<div class="news">` section in `index.html`
- Each news item follows this format:
```html
<div class="row p-2 d-flex justify-content-between">
  <div class="col-2">Date</div>
  <div class="col-10">News content here</div>
</div>
```

### Update Publications (publications/index.html)
- Add new publication cards in the publications section
- Include: title, authors, date, abstract

### Update Projects (projects/index.html)
- Add new project cards with: title, description, collaborators, dates
- Create a new directory under `projects/` for detailed project pages

### Update Bio/CV (bio/index.html)
- **Education**: Edit the education section
- **Experience**: Edit the experience section
- **Resume PDF**: Replace `assets/docs/Vinay_Resume.pdf`

## Recent Updates

<!-- Edit this section to add updates. Format: Date | Update description -->
<!-- When ready, prompt to sync these to the website index.html news section -->

| Date | Update |
|------|--------|
| 2026-04-05 | Fixed merge conflict in index.html |
| 2026-04-05 | Added lazy loading to all images |
| 2026-04-05 | Added width/height attributes to prevent layout shift |
| 2026-04-05 | Added preconnect hints for CDN resources |
| 2026-04-05 | Removed custom domain - using ummadiviany.github.io |
| 2026-04-05 | Fixed image dimensions for project thumbnails |

## Deployment

Website is deployed from the `ud` branch. Push changes to `ud` branch to deploy.

```bash
git add -A
git commit -m "Your commit message"
git push origin ud
```

## Contact

- Email: ummadi.vinay2000@gmail.com
- GitHub: [ummadiviany](https://github.com/ummadiviany)
- LinkedIn: [ummadivinay](https://linkedin.com/in/ummadivinay)
