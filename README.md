# Portfolio Website

## Overview
This is a professional portfolio website for **Kondabattini Nithin Kumar**, a motivated student focusing on software engineering, systems, and cloud technologies.

## Features

### 1. **Responsive Design**
- Mobile-first responsive layout
- Modern dark theme with cyan accents
- Optimized for all screen sizes
- Beautiful gradient backgrounds

### 2. **Email Validation**
- Client-side email validation using regex
- RFC 5322-compliant email format checking
- Real-time feedback on form submission

### 3. **Unit Tests for Email Validation**
The portfolio includes comprehensive unit tests for email validation:

```javascript
// Test cases include:
- valid@example.com => true
- user.name@domain.co.uk => true
- test+tag@example.com => true
- invalid@ => false
- @example.com => false
- nospacehere@domain => false
- (empty string) => false
- no-at-sign.com => false
```

**Running the tests:**
1. Open the portfolio in a web browser
2. Open the browser's Developer Console (F12 or Ctrl+Shift+I)
3. Look for the output showing: "Running email validation unit tests..."
4. The console will display test results with PASSED/FAILED status

### 4. **Contact Form**
- Full-featured contact form with validation
- Name, email, and message fields
- Real-time validation feedback
- Success and error messages with color coding

### 5. **Professional Information**
- Credentials and certifications section
- AWS Cloud Practitioner certification
- Microsoft Azure Fundamentals certification
- Course information (SESD, MICR)
- About section with professional summary

## Profile Information

**Name:** Kondabattini Nithin Kumar  
**Designation:** Student  
**Focus Areas:** Software Engineering, Systems, Cloud Technologies  
**Email:** nithin.kondabattini@example.com

## Certificates
- AWS Cloud Practitioner
- Microsoft Azure Fundamentals

## Courses Completed
- SESD (Software Engineering and Systems Development)
- MICR (Modern Infrastructure and Cloud Resources)

## Technologies Used
- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript (ES6+)
- Responsive Design Principles

## Email Validation Logic

The email validation uses a regular expression pattern:
```javascript
const re = /^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/;
```

This pattern ensures:
- Valid characters before @ sign
- Valid domain structure
- Minimum TLD length of 2 characters
- Proper dot notation in domain

## How to Use

1. **View the Portfolio:**
   - Open `index.html` in a web browser
   - The portfolio will be fully functional and interactive

2. **Test Email Validation:**
   - Try submitting the contact form with invalid emails
   - Open the console to see detailed test results

3. **Send a Message:**
   - Fill in the contact form with valid information
   - Receive confirmation message on successful submission

## Browser Compatibility
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Deployment
This portfolio is deployed on GitHub Pages and can be accessed at:
`https://github.com/Nithinkondabathini/portfolio-website`

## Author
**Kondabattini Nithin Kumar**  
Student | Software Engineering Enthusiast | Cloud Technology Advocate

## License
This project is open source and available under the MIT License.

---

*Last Updated: November 2025*
