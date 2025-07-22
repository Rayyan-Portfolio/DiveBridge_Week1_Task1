# DiveBridge_Week1_Task1
# Ahmad Rayyan – Portfolio Website

This is a personal portfolio website created using **HTML and CSS**. The goal of the website is to showcase my skills, background, personal interests, and contact information in a clean, structured, and responsive layout.

---

## 🔧 Technologies Used

- **HTML5**: For structuring the content and layout of the website.
- **CSS3**: For styling the layout, animations, responsiveness, and color theme.
- **Font Awesome**: For social media icons and the mobile menu icon.

---

## 📁 Project Structure

project-folder/
│
├── index.html # Main HTML file with all sections
├── style.css # External CSS for styling
├── port1.png # Logo image
├── pic1.jpg # Home section image
├── pic2.png # About section image
├── skills.jpg # Skills section image


---

## 📑 How I Used HTML

I used **HTML** to build the content and structure of the website across various semantic sections, ensuring that each part of the portfolio is clearly defined and easy to navigate:

### 1. **Header and Navigation**
- Created using the `<header>` and `<nav>` tags.
- Includes a logo (`port1.png`), horizontal menu with anchor links, and a mobile menu button.
- The navigation links are anchored to internal section IDs for smooth scrolling.

### 2. **Home Section**
- Tag used: `<section class="Home" id="Home-page">`
- Displays a welcome message with a brief introduction and a personal image (`pic1.jpg`).
- Content is wrapped in two `<div>` blocks: one for text and one for the image, using a flexible layout.

### 3. **Skills Section**
- Tag used: `<section class="Skills" id="skills-page">`
- Includes a paragraph describing technical competencies (HTML5, CSS3, JavaScript, UI/UX, server management).
- A supporting graphic (`skills.jpg`) is displayed on the side.

### 4. **About Section**
- Tag used: `<section class="About" id="about-page">`
- Describes my approach as a frontend developer, emphasis on clean code and responsive design.
- Accompanied by a relevant image (`pic2.png`).

### 5. **Personal Statement Section**
- Tag used: `<section class="personal" id="personal-page">`
- A detailed paragraph reflecting my passion for computer science, career goals, and hobbies like photography.
- No image to keep the focus on the text.

### 6. **Contact Section**
- Tag used: `<section class="Section-contact" id="Contact-page">`
- A functional contact form with:
  - `<input>` fields for Name, Email, and Subject
  - `<textarea>` for the message
  - A submit `<button>` styled for interaction
- Note: JavaScript is not connected to actually send the form data; the layout is visual and front-end only.

### 7. **Footer**
- Contains social media links with icons powered by **Font Awesome**.
- A copyright message.
- Social links are wrapped in `<div class="SocialIcons">` and styled as circular icons.

---

## 📱 Responsiveness

HTML tags are used with proper structure and class names, making it easy to apply CSS Flexbox and media queries. This ensures that the layout adjusts gracefully on tablets and mobile devices.

- The mobile navigation menu is triggered using a `<button>` with a hamburger icon from Font Awesome.
- JavaScript is used briefly to toggle the visibility of nav links on smaller screens (optional and minimal).

---

## 🚀 How to Run the Project

1. Clone or download the repository.
2. Ensure all image files (`port1.png`, `pic1.jpg`, `pic2.png`, `skills.jpg`) are in the same directory.
3. Open `index.html` in any web browser.

---

## ✨ Credits

This website was designed and built by **Ahmad Rayyan** using pure HTML and CSS with a minimalist, user-friendly, and responsive approach.

---

## 📌 Future Enhancements

- Add JavaScript functionality to handle form submissions.
- Introduce a Projects section with image cards and modal views.
- Add animations on scroll using CSS or animation libraries.
- Connect to backend for live contact form.

