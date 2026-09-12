# CampusFlow — Smart Campus Infrastructure & Resource Monetization

## Submission-ready landing page

This project is a responsive HTML5 landing page inspired by the visual language of the two provided construction/real-estate references: strong dark hero sections, premium editorial typography, warm gold highlights, structured content blocks, project/venue cards, and clear calls to action.

The design is **not a login/register application**. There are no login or registration forms.

## Main concept

CampusFlow addresses the problem of university facilities being underutilized outside peak academic hours.

The page communicates:
- AI-assisted dynamic pricing for venue rentals
- Automatic booking conflict detection
- Streamlined student club reservations
- Resource monetization and utilization analytics
- External client/community partner venue inquiries
- Facility manager and finance administrator benefits
- Student club booking benefits

## Required rubric elements

- HTML5 Semantic Tags: `header`, `nav`, `main`, `section`, `article`, `ol`, `form`, `address`, `footer`
- Page title
- Navigation menu
- Hero section
- More than 3 content sections
- Footer
- Responsive design
- Accessibility skip link
- Form labels and validation
- ARIA attributes
- Interactive mobile menu
- Interactive AI pricing concept
- Hover interactions and scroll reveal
- No login/register

## Color combination

Primary palette:
- Deep Navy: `#071A2B`
- Navy Blue: `#0B2742`
- Royal Blue: `#175EA8`
- Warm Gold: `#D6A85F`
- Ivory/Cream: `#F6F1E8`
- Teal: `#1D7A78`
- Mist: `#EEF3F5`

The navy/gold combination gives a premium institutional feel similar to the supplied references, while blue and teal communicate technology, trust, and sustainability.

## Technologies

- HTML5
- Tailwind CSS via CDN
- Vanilla JavaScript
- Responsive CSS
- Unsplash image URLs for demonstration imagery

## Run locally

Open `index.html` directly in a browser.

Or run:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## GitHub submission

```bash
git init
git add .
git commit -m "Create CampusFlow smart campus landing page"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

For GitHub Pages:
1. Push the repository.
2. Open repository Settings.
3. Open Pages.
4. Select the `main` branch and root folder.
5. Save.
6. Open the generated Pages URL.

## Testing completed

The HTML structure was programmatically checked for:
- HTML5 doctype
- Required semantic tags
- Page title
- Navigation
- Hero section
- Multiple content sections
- Footer
- Form labels
- No login/register wording or form controls

The page also contains client-side validation for the inquiry form and JavaScript interaction for the mobile menu and pricing demonstration.
