# Online CV

A single-page personal CV website built with pure HTML and CSS.

## Preview
Visit [https://hetai.github.io/cv/](https://hetai.github.io/cv/) to see the live version.

## Features
- Responsive design
- Semantic HTML structure
- Clear visual hierarchy
- Dynamic path configuration for local development and production
- SEO-friendly meta tags
- Social media sharing with Open Graph tags

## Tech Stack
- HTML5
- CSS3
- JavaScript (for path configuration)

## Project Structure
```
cv/
├── index.html          # Main page
├── styles.css          # Stylesheet
├── dev-config.js       # Development configuration
├── site.webmanifest    # PWA configuration
├── .nojekyll          # GitHub Pages configuration
└── README.md          # Project documentation
```

## Local Development
1. Clone the repository
```
git clone https://github.com/hetai/cv.git
cd cv
```

2. Start local server
```
# Using Python
python -m http.server 8000

# Or using Node.js
npx http-server . -p 8000
```

3. Visit `http://localhost:8000` to view the site

## Deployment
The project is deployed using GitHub Pages. Changes pushed to the main branch will automatically deploy to production.

## Customization
1. Update personal information in `index.html`
2. Adjust styles in `styles.css`
3. Replace favicon and other icon files

## License
MIT License

## Author
[He Tai](https://github.com/hetai)

## Reference
This project is inspired by the [Single-Page CV project](https://roadmap.sh/projects/single-page-cv) from roadmap.sh.
