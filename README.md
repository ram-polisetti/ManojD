# Professional Portfolio Website

A modern, responsive portfolio website showcasing professional experience, academic achievements, and providing contact options through email and calendar booking.

## Features

- Responsive design that works on all devices
- Professional layout with smooth scrolling navigation
- Sections for professional journey and academic achievements
- Contact form with EmailJS integration
- Google Calendar integration for consultation booking
- Social media links
- Modern animations and transitions

## Setup Instructions

1. Clone this repository
2. Replace the following placeholders in the code:
   - In `script.js`:
     - Replace `YOUR_USER_ID` with your EmailJS user ID
     - Replace `template_id` with your EmailJS template ID
     - Replace `YOUR_CALENDAR_ID` with your Google Calendar scheduling link
   - In `index.html`:
     - Update the professional information with your details
     - Update social media links
     - Add your own background image if desired

## Email Integration Setup

1. Sign up at [EmailJS](https://www.emailjs.com/)
2. Create a new email template
3. Get your user ID and template ID
4. Update the credentials in `script.js`

## Calendar Integration Setup

1. Set up a Google Calendar appointment scheduling page
2. Copy your calendar scheduling link
3. Update the `calendarURL` in `script.js`

## GitHub Pages Deployment

1. Go to your repository settings
2. Navigate to the "Pages" section
3. Select the main branch as the source
4. Save the settings
5. Your site will be published at `https://[username].github.io/[repository-name]`

## Technologies Used

- HTML5
- CSS3
- JavaScript
- EmailJS for email functionality
- Google Calendar API for scheduling
- Font Awesome for icons

## Customization

Feel free to customize the colors by modifying the CSS variables in the `:root` selector in `styles.css`:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --text-color: #333;
    --light-bg: #f5f6fa;
    --white: #ffffff;
}
```

## License

MIT License - feel free to use this template for your own portfolio!
