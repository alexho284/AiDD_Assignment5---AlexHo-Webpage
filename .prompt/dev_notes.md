Prompt Log
Prompt 1
1) Prompt:
Create a multi-page personal website with `index.html`, `about.html`, `resume.html`, `projects.html`, `contact.html`, and `thankyou.html`. Use semantic HTML (`<header>`, `<nav>`, `<main>`, `<footer>`), consistent navigation on every page.
2) AI output (summary):
Generated skeleton HTML for all six pages, each with a shared navigation list linking to the others (Home, About, Resume, Projects, Contact). Added a short intro on the homepage; an About page section with a photo placeholder and headings for Background, Interests, Goals; a Resume page organized into Education, Experience, Skills, Achievements; a Projects page with two project slots and image placeholders; a Contact page with a basic form stub; and a Thank You page as the redirect target. Confirmed each page should link the single stylesheet `styles.css`.
3) Agreed with the suggestions

Prompt 2
1) Prompt:
Write a responsive `styles.css` that uses Tottenham colors (deep navy #132257, white, sky-blue accent), the Montserrat font, and pill-style nav buttons. On hover, keep link text white but add a subtle sky-blue ring/underline. Include styles for project “cards”, the contact form (labels, inputs, focus states)
2) AI output (summary):
Provided CSS custom properties for the palette; set global font-family to Montserrat; styled headings and body text for readability. Built a pill-shaped nav with white text, then added hover/focus that slightly darkens the navy background, shows a sky-blue outline using box-shadow, and animates a 2px sky-blue underline via a `::after` pseudo-element—without changing text color. Included a light “surface” card style with rounded corners and soft shadow for `.project-card`, accessible focus states on inputs, and a responsive layout that adjusts spacing and keeps content readable on small screens. Ensured one shared stylesheet is referenced by all pages.
3) Agreed with the suggestions

Prompt 3
1) Prompt:
Implement contact form validation and accessibility. Fields: First Name, Last Name, Email, Password (min 8), Confirm Password (must match). Use HTML attributes and minimal JS to enforce password match with clear error messages. Ensure every input has a `<label>` with matching `for`/`id`. On submit, redirect to `thankyou.html`
2) AI output (summary):
Recommended keeping semantic `<label>`+`id` pairs for all inputs and enabling built-in browser checks with `required`, `type="email"`, and `minlength="8"`. Suggested an optional `pattern` to require a letter and a number. Provided a small JS snippet that listens for input and `submit`, uses `setCustomValidity()` to show “Passwords must match” when the confirm field differs, and clears the message on match. Kept the form `action="thankyou.html"` so successful submission routes to the thank-you page. Emphasized accessible error messaging, preserving keyboard focus, and avoiding intrusive alerts.
3) Agreed with the suggestions


AI-Reflection
Coming back to HTML/CSS after a gap, AI really helped me speed up the setting up of the backbone as well as styling suggestions so I could focus more on content and polish. Copilot/ChatGPT generated the multi-page skeleton and a responsive consistent themed stylesheet in minutes—tasks that would have taken me much longer complete on my own from scratch. Where AI struggled was with details I cared about: keeping the nav hover readable (white text instead of turning black) or ensuring the header adapted when the nav wrapped on small screens. I had to modify variables, edited the hover states, and tighten spacing. For compliance, I double-checked assignment requirements. My approach to balance: use AI for setting up backbone and for suggestions, then continuously edit and modify details and contents while also making sure that I followed the rubric and instructions of the assignment. Overall, AI significantly reduce the time and trouble I had to go through to finish this assignment and refresh on HTML and CSS knowwledge while also helping me improve overall quality of the finished application.
