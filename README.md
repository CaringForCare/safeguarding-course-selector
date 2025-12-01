Safeguarding Course Finder App

An interactive, single-page web application designed to guide users to the correct safeguarding training course based on their role and responsibilities. This tool mimics a decision-tree logic flow (e.g., Frontline vs. Manager -> DSL vs. Strategic Leader) to recommend specific courses.

Features

Interactive Q&A: Step-by-step questions to determine user requirements.

Branching Logic: Dynamically routes users to Level 2, Level 3 (Manager/DSL), Level 4, or Level 5 courses.

Context Awareness: Adjusts course recommendations based on whether the user works with Adults, Children, or both.

Responsive Design: Built with Tailwind CSS for mobile and desktop compatibility.

Single File Deployment: The entire app runs from a single HTML file with no build process required.

Quick Start

Download or clone this repository.

Locate the safeguarding_app.html file.

Double-click the file to open it in your web browser.

No server, installation, or build steps are required.

Customization

You can easily edit the course data, links, or logic within the HTML file.

Open safeguarding_app.html in any text editor (VS Code, Notepad++, etc.).

Scroll down to the <script> section.

Locate the COURSES constant object.

To change links: Update the link property for the specific level.

To change text: Update the title, subtitle, or objectives arrays.

const COURSES = {
    LEVEL_2: {
        // ...
        link: '[https://your-new-link.com](https://your-new-link.com)'
    },
    // ...
};


Technologies Used

HTML5/CSS3/JavaScript: Core technologies.

Tailwind CSS (via CDN): For styling and responsive layout.

Lucide Icons (via CDN): For visual iconography.

License

This project is open source and available under the MIT License.
