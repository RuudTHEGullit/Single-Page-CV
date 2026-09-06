[# Single-Page-CV](https://roadmap.sh/projects/single-page-cv)
Personal Resume Website

A simple, responsive personal resume website built using HTML and CSS. The website presents my education, projects, technical skills, competitive programming achievements, and extracurricular activities in a clean, dark-themed layout.

Features:
Responsive resume layout
A4-friendly design for printing
Dark/black background
Orange section headings
Orange-highlighted first name
Education and project timelines
Technical skills section
Competitive programming achievements
Extracurricular activities
Responsive layout for mobile devices
Print-to-PDF support

Technologies Used:
HTML5 — Structure and content
CSS3 — Styling, layout, responsiveness, and print formatting

Project Structure:
resume/
│
├── index.html
├── style.css
└── README.md

Design:
The resume uses a dark theme:

Background: Black
Primary text: White
Accent: Orange
Font: Arial / Helvetica / sans-serif

The orange accent is used for section headings, skill labels, and the first name to provide visual contrast against the black background.

Sections:
The resume contains the following sections:

Personal Details
Education
Personal Projects
Predictiva: AI-Powered Stock Forecasting System
Movie Ticket Booking App
Technical Skills and Interests
Competitive Programming Highlights
Extra Curricular

Getting Started:
1. Clone the repository
git clone https://github.com/your-username/resume.git
2. Open the project

Navigate into the project directory:

cd resume
3. Run the website

Simply open index.html in your web browser.

You can also use Live Server in VS Code for easier development.

Export as PDF:

Open index.html in your browser.
Press Ctrl + P on Windows/Linux or Cmd + P on macOS.
Select Save as PDF.
Select A4 as the paper size.
Save the resume.

Responsive Design:
The layout automatically adapts to smaller screens.
On mobile devices:
Resume width becomes fluid.
Contact information is stacked vertically.
Education/project dates move below their respective headings.
Skills become easier to read on narrow screens.

Customization:
You can customize the resume by editing index.html.
For example, to change the name:

<h1>
    <span class="profile_firstName">Soumyadeep</span>
    <span class="profile_lastName">Barua</span>
</h1>

To change the accent color, modify:

#ff8c00

For example:

color: #ff8c00;

You can replace it with another color such as:

color: #ff9f1c;

License:
This project is intended for personal use. Feel free to modify the design and content for your own resume.

Author:

Soumyadeep Barua
