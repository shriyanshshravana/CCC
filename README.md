# ☁️ Nimbus 3.0 — Cloud Computing Cell

A responsive event website designed for the **Cloud Computing Cell (CCC)** of **Ajay Kumar Garg Engineering College (AKGEC)** for the **Nimbus 3.0** event.

The website presents information about the Cloud Computing Cell, its community, technical domains, event speakers, schedule, and registration.

## 🌐 Live Website

[Visit Nimbus 3.0 Website](https://ccc-shriyanshshravanas-projects.vercel.app/)

---

## 📌 About the Project

**Nimbus 3.0** is a frontend web development project created for the Cloud Computing Cell (CCC) of Ajay Kumar Garg Engineering College.

The main purpose of the website is to provide a clean and modern online platform for presenting the event and giving visitors quick access to important information such as:

* About the Cloud Computing Cell
* Community information
* Technical domains
* Event highlights
* Speakers
* Event schedule
* Registration
* Contact information

The website follows a dark, modern technology-inspired visual style using a purple accent color.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Create a professional event website for Nimbus 3.0.
* Present information about the Cloud Computing Cell.
* Provide easy navigation between different sections.
* Highlight the technical domains explored by the society.
* Display speaker information.
* Provide the event schedule.
* Provide direct registration and contact links.
* Create a responsive layout for different screen sizes.
* Deploy the completed website online.

---

## ✨ Features

### 1. Fixed Navigation Bar

The website contains a fixed navigation bar at the top of the page.

It includes:

* CCC logo
* Cloud Computing Cell name
* About Us
* Know More
* Domains
* Events
* Contact
* Register button

The navigation links allow users to move between sections or visit external CCC pages.

### 2. Hero Section

The hero section introduces Nimbus 3.0 with:

* Cloud Computing Cell branding
* Event motto
* Main heading
* Event description
* Register Now button
* Explore button

The main message is:

> Think | Develop | Deploy

### 3. About Us Section

This section provides information about the Cloud Computing Cell, including its establishment, purpose, learning opportunities, and coordination.

It also provides links to the official AKGEC Cloud Computing Cell page and the CCC contact page.

### 4. Who Are We Section

This section introduces the CCC community and describes the team's interests and collaborative approach.

The section contains:

* Team image
* Community description
* Technology areas
* About Us button

### 5. Domains Section

The website presents the major technical domains explored by the society:

* Cloud Computing
* Web and App Development
* UI/UX Design
* Machine Learning

### 6. What You Can Expect

This section uses cards to present the major learning opportunities of Nimbus 3.0:

* Cloud Computing
* Emerging Tech
* Hands-on Learning

### 7. Speakers Section

The website displays six speakers/team members with their respective roles:

* Ayush Pratap — ML Developer
* Suhani Dubey — UI/UX Designer
* Shaurya Verma — Frontend Developer
* Shubham Pandey — App Developer
* Aryan Singh — Cloud Developer
* Manas Sharma — Backend Developer

### 8. Event Schedule

The schedule section displays the planned event timeline:

| Time     | Activity               |
| -------- | ---------------------- |
| 10:00 AM | Registration & Welcome |
| 11:00 AM | Keynote Session        |
| 12:30 PM | Interactive Workshop   |
| 02:30 PM | Networking & Closing   |

### 9. Registration Section

A final call-to-action section encourages visitors to register for Nimbus 3.0.

### 10. Footer

The footer contains:

* Cloud Computing Cell name
* Motto
* Event link
* Team link
* Contact link
* Registration link
* Official email address

---

## 🛠️ Technologies Used

### HTML5

HTML is used to create the structure and content of the website.

Major HTML concepts used include:

* Semantic elements
* Navigation
* Sections
* Headings
* Paragraphs
* Images
* Links
* Lists
* Div containers

### CSS3

CSS is used to control the visual appearance and layout.

Major CSS concepts used include:

* CSS reset
* Flexbox
* CSS Grid
* Responsive design
* Media queries
* Colors
* Spacing
* Borders
* Border radius
* Typography
* Hover effects
* Fixed positioning
* Gradients
* `clamp()`
* `object-fit`

### Git

Git was used for version control and managing the project locally.

### GitHub

GitHub was used to store and manage the source code repository.

### Vercel

Vercel was used to deploy the website and make it accessible online.

---

## 📂 Project Structure

```text
CCC-Nimbus-3.0/
│
├── index.html
├── style.css
│
├── CCC.jpeg
├── team1.jpg
├── Ayush.png
├── Suhani.png
├── Shaurya.png
├── Shubham.png
├── Aryan.png
├── Manas.png
│
└── README.md
```

### `index.html`

Contains the complete structure and content of the website.

### `style.css`

Contains the styling, layout, colors, spacing, responsiveness, and visual effects.

### Image Files

The image files are used for:

* CCC logo
* Team image
* Speaker images

### `README.md`

Contains documentation about the project, technologies, structure, features, and deployment.

---

## 🧱 HTML Structure

The website follows a section-based structure.

The main structure is:

```text
HTML
│
├── Head
│   ├── Meta information
│   ├── Viewport
│   ├── Title
│   └── CSS file
│
└── Body
    │
    ├── Header
    │   └── Navigation
    │
    ├── Hero Section
    │
    ├── About Section
    │
    ├── Community Section
    │
    ├── Domains Section
    │
    ├── What You Can Expect
    │
    ├── Speakers Section
    │
    ├── Schedule Section
    │
    ├── Final Registration Section
    │
    └── Footer
```

---

## 🎨 CSS Structure

The CSS file is organized into different sections according to the website components.

### Global Reset

The universal selector is used to remove default browser margins and padding.

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
```

### Body Styling

The body defines the overall:

* Font
* Background color
* Text color
* Line height

### Navigation

The `.navbar` class creates the fixed navigation bar.

Flexbox is used to align the logo, navigation links, and register button.

### Hero Section

The `.hero` class creates the main landing section.

Flexbox is used to center the content vertically and horizontally.

### Sections

The `.section` class provides common:

* Maximum width
* Padding
* Centered layout

This avoids writing the same styling repeatedly for every section.

### Grid Layout

CSS Grid is used for:

* Community content
* Feature cards
* Speakers

For example:

```css
grid-template-columns: repeat(3, 1fr);
```

creates three equal-width columns.

### Responsive Design

Media queries are used to adapt the website to smaller screens.

```css
@media (max-width: 800px)
```

changes the layout for tablets and smaller devices.

Another media query:

```css
@media (max-width: 500px)
```

handles smaller mobile screens.

---

## 📱 Responsive Design

The website is designed to adapt to different screen sizes.

On smaller screens:

* Navigation links are hidden.
* Content changes from multiple columns to one column.
* Domain box becomes full width.
* Hero heading becomes smaller.
* Hero buttons become vertically arranged.
* Schedule information becomes vertically arranged.
* Logo text is hidden on very small screens.

This makes the website more usable on mobile devices.

---

## 🔗 Navigation

The website uses two types of links.

### Internal Links

Internal links use section IDs.

Example:

```html
<a href="#about">About Us</a>
```

This moves the user to the About section.

### External Links

External links are used to connect the website with the official CCC/AKGEC pages.

Examples include:

* Official CCC information
* Events
* Contact
* Registration

External links are opened in a new browser tab using:

```html
target="_blank"
```

---

## 🚀 Deployment

The project was first developed locally using **Visual Studio Code**.

After completing the website:

1. The project was initialized as a Git repository.
2. The files were added using Git.
3. Changes were committed.
4. The repository was connected to GitHub.
5. The project was pushed to GitHub.
6. The GitHub repository was connected to Vercel.
7. Vercel deployed the website.
8. The deployed website became accessible through a public URL.

---

## 🔄 Development Workflow

```text
Idea
  ↓
HTML Structure
  ↓
CSS Styling
  ↓
Testing in Browser
  ↓
Fixing Layout/Design
  ↓
Git Repository
  ↓
GitHub
  ↓
Vercel Deployment
  ↓
Live Website
```

---

## 💻 How to Run Locally

1. Clone or download the repository.

2. Open the project folder in Visual Studio Code.

3. Make sure `index.html`, `style.css`, and the image files are present in the correct location.

4. Open `index.html` in a browser.

Alternatively, use the **Live Server** extension in Visual Studio Code for easier development and testing.

---

## 🔮 Future Improvements

Possible future improvements include:

* Add JavaScript for interactive functionality.
* Add a mobile hamburger navigation menu.
* Add animations and scroll effects.
* Add an event registration form directly to the website.
* Add speaker profiles with more information.
* Add an event countdown timer.
* Add social media links.
* Add a gallery section.
* Improve accessibility.
* Add form validation.
* Connect the registration system with a backend/database.

---

## 📚 Learning Outcomes

Through this project, I practiced:

* HTML5 structure
* Semantic HTML
* CSS styling
* Flexbox
* CSS Grid
* Responsive web design
* Media queries
* Navigation
* External links
* Image handling
* Git
* GitHub
* Vercel deployment
* Basic project documentation

---

## 👨‍💻 Author

Shriyansh Mishra

Frontend Web Development Project
Cloud Computing Cell — Nimbus 3.0

---

## 📄 License

This project was created as an academic/society event website project for the Cloud Computing Cell.

---
