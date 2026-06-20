# Ece Mersozlu — Academic Website

A minimalist, elegant personal academic website for a Political Science PhD candidate.

## Features

- **Responsive Design** — Looks perfect on desktop, tablet, and mobile
- **Elegant Typography** — Serif titles (Georgia/Garamond), sans-serif body text
- **Custom Color Palette** — Warm, scholarly aesthetic (#F2EBE2 background, custom oklch text color)
- **Multiple Pages** — Home, Research, Teaching, CV, Contact
- **Easy Customization** — Simple HTML structure with clear sections to fill in

## Pages

1. **Home (index.html)** — Landing page with profile photo, bio, and social links
2. **Research (research.html)** — Working papers and works in progress
3. **Teaching (teaching.html)** — Teaching experience (instructor & TA roles)
4. **CV (cv.html)** — Education, publications, awards, and skills
5. **Contact (contact.html)** — Contact information and contact form

## How to Customize

### 1. Home Page (index.html)
- Replace `[University Name]`, `[research area]`, `[degree]`, `[institution]`, etc. with your information
- Replace profile links (Twitter, Google Scholar, Email) with your actual URLs
- Add your bio in the "About" section

### 2. Profile Photo
- Add your photo to an `images/` folder as `profile.jpg`
- Create the folder:
  ```
  mkdir images
  ```
- Upload a square photo (ideally 400x400px or larger)

### 3. Research Page
- Add your working papers and works in progress
- Link to PDFs by adding files to your repository and updating `href="#"` values

### 4. Teaching Page
- Add your teaching experience with course titles, roles, and descriptions

### 5. CV Page
- Fill in your education, publications, awards, and skills
- To add a downloadable PDF: upload `cv.pdf` to the repository and link to it

### 6. Contact Page
- Update email address in the `<a href="mailto:">` link
- Update mailing address (Department, University, City, State)
- To enable the contact form:
  1. Sign up for free at [Formspree](https://formspree.io/)
  2. Create a new form and get your Form ID
  3. Replace `YOUR_FORM_ID` in the form action with your actual ID

### 7. Styling
All styling is in `style.css`. To modify:
- **Colors**: Edit the `:root` variables at the top (bg-color, text-color, etc.)
- **Fonts**: Change `--serif-font` or `--sans-serif-font` variables
- **Spacing**: Adjust `padding`, `margin`, and `gap` values as needed

## GitHub Pages Setup

Your site is automatically deployed at `https://ecemersozlu.github.io` when you push to this repository. No additional configuration needed!

## File Structure

```
ecemersozlu.github.io/
├── index.html          # Landing page
├── research.html       # Research papers
├── teaching.html       # Teaching experience
├── cv.html            # Curriculum vitae
├── contact.html       # Contact page
├── style.css          # All styling
├── images/            # Folder for images (profile photo)
│   └── profile.jpg
├── cv.pdf             # (Optional) PDF of your CV
└── README.md          # This file
```

## Tips

- Keep it simple and minimal — this design works best with concise, well-organized content
- Use subheadings (h3) to organize sections within pages
- Keep paper abstracts to 2-3 sentences for readability
- Test on mobile by opening your site on a phone or using browser dev tools
- Use `<strong>` tags for emphasis in CV descriptions

## License

Feel free to use and modify as needed for your academic website.
