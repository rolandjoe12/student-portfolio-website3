# StudentSpace — Student Portfolio & Academic Management Website

A multi-page responsive website created for the COS 106 Introduction to Web Technologies practical project.

## Pages
- `index.html` — homepage with student name, profile image, welcome message, navigation and short biography.
- `about.html` — educational background, career aspirations, technical skills, hobbies and interests.
- `projects.html` — three sample project cards with descriptions.
- `planner.html` — interactive task planner: add tasks, mark complete, delete, filter and clear completed tasks. Tasks persist in browser local storage.
- `contact.html` — contact form with JavaScript validation for required fields, email format and digits-only phone number.

## Technologies
- Semantic HTML5, forms, image, tables/links and accessible labels.
- External CSS stylesheet at `css/style.css`, including responsive mobile layouts.
- JavaScript at `js/main.js` for navigation, planner interactions and form validation.
- A local SVG avatar at `images/profile.svg`.

## Run locally
1. Extract the ZIP file.
2. Open the `student_portfolio_project` folder in Visual Studio Code.
3. Open `index.html` in a browser (or use the Live Server extension).
4. Test every navigation link, add tasks on Academic Planner, and try invalid and valid values in Contact.

## Before submitting
1. Check that the name, biography, education details, skills, and contact information reflect your own details.
2. Replace the sample email `roland@example.com` on `contact.html`.
3. Make sure you understand the HTML, CSS, and JavaScript so you can explain your work.
4. Create a GitHub repository and upload all files while keeping the folder structure.
5. Publish the website using GitHub Pages. Submit both the live website URL and the GitHub repository URL.

## Notes
- The contact form is a front-end demonstration; it validates the form but does not email or store submitted messages on a server.
- The three project descriptions are sample descriptions. Update them with your own completed projects when appropriate.
