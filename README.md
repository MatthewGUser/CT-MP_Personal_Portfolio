# Personal Portfolio Website
## Project Overview
Welcome to my Personal Portfolio Website! This project showcases my skills, experiences, and personal interests. It serves as a digital representation of my journey, displaying my background, projects, and technical expertise. The portfolio is built using HTML and CSS to create a clean, professional, and visually appealing presentation of my work.

This portfolio includes separate sections or pages for each key aspect of my profile, making it easy for visitors to navigate and learn about me.

## Features
- Home Page: Provides a brief introduction, including my name, bio, and a profile picture.
- About Me: Offers detailed information about my background, education, career goals, and personal interests.
- Projects: Showcases my past projects with descriptions, images, links, and technologies used.
- Skills: Highlights my technical skills, programming languages, and software proficiency through a visual representation (e.g., skill bars or charts).
- Contact Page: Provides a contact form, email, and links to my social media profiles for easy communication.
## File Structure
The project is structured in a way that enhances readability and maintainability, with clear separations between different sections or pages. Here’s an overview of the file structure:

```
personal-portfolio/
├── assets/                     # Directory containing images, CSS files, and other assets.
│   ├── css/                    # Directory for CSS files to style the website.
│   │   └── style.css           # CSS file for styling the website.
│   └── images/                 # Directory for images used in the portfolio.
│       └── profile.jpg         # Profile picture or any image used in the portfolio.
├── index.html                  # Home page of the portfolio.
├── about.html                  # About Me section/page.
├── projects.html               # Projects section/page.
├── skills.html                 # Skills section/page.
├── contact.html                # Contact section/page.
└── README.md                   # Project overview and instructions.
```
## How to View the Website
1. Clone the Repository:
```
git clone https://github.com/MatthewGUser/Personal-Portfolio.git
cd Personal-Portfolio
```
2. Open the `index.html` file in your web browser to view the website:

- You can open the HTML files directly by navigating to the project directory and double-clicking on the index.html file, or
- Open the terminal and type the following command to run a simple local server:
```
python -m http.server
```
- Open your browser and visit http://localhost:8000 or http://127.0.0.1:5500/.
3. Navigate between pages using the menu or links on the homepage.

## Sections and Pages
1. Home Page
The Home Page serves as the main landing page and includes:
- A brief introduction to who I am.
- My profile picture.
- A short welcome message.
Example snippet from `index.html`:
```
<header>
    <h1>Welcome to My Portfolio</h1>
    <p>Hello! I'm Matthew, a passionate developer.</p>
    <img src="assets/images/profile.jpg" alt="Profile Picture">
</header>
```
2. About Me
The About Me section provides in-depth details about my background:
- Educational history.
- Career goals.
- Personal interests and hobbies.
Example snippet from `about.html`:
```
<section>
    <h2>About Me</h2>
    <p>I am a developer with a passion for learning and creating new things...</p>
</section>
```
3. Projects
The Projects page highlights key projects I’ve worked on:
- Project descriptions.
- Links to project repositories or live demos.
- Technologies and tools used.
Example snippet from `projects.html`:
```
<section>
    <h2>Projects</h2>
    <div class="project">
        <h3>Project Name</h3>
        <p>A short description of the project...</p>
        <a href="https://github.com/MatthewGUser/Project-Repo" target="_blank">View on GitHub</a>
    </div>
</section>
```
4. Skills
The Skills section showcases my technical skills through visual representations such as:
- Skill bars or charts for programming languages and frameworks.
- A list of software tools I am proficient in.
Example snippet from skills.html:
```
<section>
    <h2>Skills</h2>
    <ul>
        <li>HTML & CSS - 90%</li>
        <li>JavaScript - 80%</li>
        <li>Python - 85%</li>
    </ul>
</section>
```
5. Contact
The Contact page provides a way for visitors to get in touch with me:
- A contact form for sending messages.
- Links to social media profiles.
- Email address.
Example snippet from contact.html:
```
<section>
    <h2>Contact Me</h2>
    <form action="submit_form.php" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <input type="submit" value="Send">
    </form>
    <p>Email: matthew@example.com</p>
</section>
```
## Conclusion
This Personal Portfolio website is designed to provide a clear, structured overview of my skills, experiences, and projects.