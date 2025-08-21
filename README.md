# Professional Portfolio Website

## Overview
This is a modern, responsive portfolio website template designed to showcase your professional work, skills, and experience. The website features a clean, minimalist design with smooth animations and interactive elements.

## Features
- Responsive design that works on all devices (mobile, tablet, desktop)
- Modern UI with smooth animations and transitions
- Interactive navigation with scroll spy functionality
- Project filtering system to categorize your work
- Contact form for potential clients or employers to reach out
- Social media integration
- Skills visualization with progress bars
- Clean and well-organized code structure

## Pages/Sections
1. **Home/Hero** - Introduction and call-to-action
2. **About** - Personal information and professional background
3. **Skills** - Technical expertise and competencies
4. **Projects** - Portfolio of your work with filtering options
5. **Contact** - Contact form and information

## Technologies Used
- HTML5
- CSS3 (with custom variables and animations)
- JavaScript (vanilla JS, no frameworks)
- Font Awesome for icons
- Google Fonts

## Setup Instructions

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic knowledge of HTML/CSS/JavaScript if you want to customize

### Installation
1. Clone or download this repository to your local machine
2. Open the `index.html` file in your web browser to view the website

### Customization

#### Personal Information
1. Open `index.html` in a text editor
2. Replace "Your Name" with your actual name throughout the document
3. Update the email, location, and other personal details
4. Replace placeholder text in the About section with your own information

#### Projects
1. To add your own projects, locate the Projects section in `index.html`
2. Follow the existing project card structure to add new projects
3. Update the project images in the `images` folder
4. Modify the project categories as needed

#### Skills
1. Find the Skills section in `index.html`
2. Adjust the skill names and progress percentages to match your expertise
3. Add or remove skill cards as necessary

#### Styling
1. Open `css/styles.css` to customize colors, fonts, and other styling
2. The main color scheme can be changed by modifying the CSS variables at the top of the file

#### Social Media
1. Update the social media links in the Hero and Contact sections
2. Add or remove social media icons as needed

#### Contact Form Email Functionality
1. Create a free account at [EmailJS](https://www.emailjs.com/)
2. Create an Email Service (Gmail, Outlook, etc.) in your EmailJS dashboard
3. Create an Email Template with template parameters: `from_name`, `from_email`, `subject`, and `message`
4. Get your EmailJS User ID from Account > API Keys
5. Open `index.html` and replace `YOUR_USER_ID` with your actual EmailJS User ID (line 396)
6. Open `js/script.js` and replace:
   - `YOUR_SERVICE_ID` with your EmailJS service ID (line 203)
   - `YOUR_TEMPLATE_ID` with your EmailJS template ID (line 204)
7. Test the contact form to ensure emails are being sent correctly

**Important Notes:**
- The contact form now includes built-in error handling that will display helpful messages if EmailJS is not properly configured
- You can use the `email-test.html` file to test your EmailJS configuration separately from the main website
- If you see error messages about configuration, follow the instructions above to set up EmailJS properly
- The form will not attempt to send emails until all configuration values are properly set

## Deployment
To deploy this website to a live server:

1. Upload all files to your web hosting service
2. Ensure the file structure remains intact
3. Point your domain to the directory containing the `index.html` file

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## License
Feel free to use this template for your personal portfolio. Attribution is appreciated but not required.

## Credits
- Font Awesome for icons
- Google Fonts for typography
- Unsplash for placeholder images (if used)

---

## Contact
If you have any questions or need assistance with this template, please contact:

- Email: your.email@example.com
- Website: [Your Website](https://yourwebsite.com)

---

Happy coding! 🚀