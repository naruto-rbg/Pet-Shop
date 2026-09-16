🐾 PAWORA — Premium Pet Shop Website
PAWORA is a modern, responsive, multi-page pet shop website built using HTML5 and CSS3.

The website is designed to provide a premium and attractive user interface for a pet store, featuring real animal photography, animated elements, 3D-style hover effects, pet listings, services, company information, and a contact form.

🌐 Project Overview
PAWORA is designed as a complete front-end pet shop website with 5 interconnected pages.

The website focuses on:

Modern UI design
Real animal photography
CSS animations
3D-style visual effects
Responsive design
Clean navigation
Pet listings
Pet care services
About section
Contact form
The project is completely front-end based and does not require a backend or database.

📄 Website Pages
1. Home — index.html
The home page introduces the PAWORA brand and provides an overview of the website.

Includes:

Hero section
3D-style featured dog image
Animated floating information cards
Pet categories
Featured pets
Call-to-action section
Navigation to other pages
2. Pets — pets.html
The Pets page displays available animals.

Includes:

Dogs
Cats
Rabbits
Birds
Pet photographs
Pet names
Breed information
Age
Prices
Availability labels
Enquiry buttons
Category filter-style buttons
3. Services — services.html
The Services page presents the different pet-care services offered by PAWORA.

Services include:

Pet Grooming
Veterinary Care
Pet Training
Pet Boarding
Pet Food
Pet Consultation
Each service is displayed using an animated card with a 3D-style hover effect.

4. About — about.html
The About page explains the purpose and values of PAWORA.

Includes:

Company story
Mission and values
Real animal photography
Experience statistics
Happy customer statistics
Pets rehomed statistics
Pet expert statistics
Reasons to choose PAWORA
5. Contact — contact.html
The Contact page allows visitors to find contact information and submit an enquiry.

Includes:

Contact information
Store address
Phone number
Email address
Opening hours
Contact form
Service selection
Message field
Store location section
📁 Project Structure
PAWORA-Pet-Shop/
│
├── index.html
├── pets.html
├── services.html
├── about.html
├── contact.html
│
├── style.css
│
└── README.md
🎨 Design Features
Modern UI
The website uses a clean and premium visual style combining:

Dark navy
Warm orange
Cream backgrounds
White cards
Rounded corners
Soft shadows
3D Effects
CSS 3D transforms are used throughout the website.

Examples include:

transform: rotateY(-10deg) rotateX(5deg);
and:

transform: translateY(-12px) rotateY(-4deg);
These create depth and give the website a more dynamic appearance.

Hover Effects
Cards and buttons respond when the user moves the mouse over them.

Examples:

Card elevation
Image zoom
3D rotation
Button movement
Shadow changes
Color transitions
Animations
The project includes CSS animations such as:

Floating elements
Image movement
Pulsing background
Rotating elements
Page entrance animations
Example:

@keyframes floating {
    0%, 100% {
        transform: translateY(0);
    }

    50% {
        transform: translateY(-18px);
    }
}
📱 Responsive Design
The website is designed to work across different screen sizes.

Responsive layouts are provided for:

Desktop
Laptop
Tablet
Mobile
CSS media queries are used to change the layout depending on the screen width.

For example:

@media (max-width: 650px) {
    ...
}
🖼️ Images
The project uses real animal photographs rather than animal icons or emojis.

The current HTML uses image URLs from Unsplash.

For example:

<img
    src="https://images.unsplash.com/..."
    alt="Golden Retriever"
>
Recommended for final submission
For a college submission or GitHub project, it is better to download the required images and store them locally.

A recommended structure is:

PAWORA-Pet-Shop/
│
├── images/
│   ├── dog.jpg
│   ├── cat.jpg
│   ├── rabbit.jpg
│   ├── bird.jpg
│   └── ...
│
├── index.html
├── pets.html
├── services.html
├── about.html
├── contact.html
└── style.css
Then change the image paths from external URLs to:

<img src="images/dog.jpg" alt="Golden Retriever">
This allows the website to work without depending on an internet connection for the images.

🛠️ Technologies Used
Technology	Purpose
HTML5	Website structure
CSS3	Styling and layout
CSS Grid	Card and page layouts
CSS Flexbox	Alignment and navigation
CSS Animations	Motion effects
CSS 3D Transforms	3D visual effects
Media Queries	Responsive design
Unsplash	Animal photography
🚀 How to Run the Project
Method 1 — Open Directly
Download or clone the project.
Open the project folder.
Double-click index.html.
The website will open in your browser.
Method 2 — Using VS Code
Open the project folder in Visual Studio Code.
Make sure all HTML files and style.css are in the same folder.
Open index.html.
Use the Live Server extension if installed.
Click Go Live.
The website will open in your browser.

🔗 Page Navigation
All pages are connected through the navigation bar.

index.html
     │
     ├── pets.html
     │
     ├── services.html
     │
     ├── about.html
     │
     └── contact.html
The footer also contains links to all major pages.

⚠️ Current Limitations
This project is currently a front-end static website.

The following features are visual only and are not connected to a backend:

Pet purchasing
Shopping cart
Online payment
User accounts
Database
Real-time pet availability
Contact form database submission
Pet category filtering
Appointment booking
Veterinary appointment management
The contact form currently provides the user interface but does not store submitted information.

The filter buttons on the Pets page are also currently interface elements and require JavaScript to perform actual filtering.

🔮 Future Improvements
The project can be expanded into a complete pet-shop application by adding:

JavaScript
Working pet filters
Pet detail pages
Image sliders
Shopping cart
Interactive forms
Search functionality
Mobile navigation menu
Form validation
Backend
A backend could provide:

User registration
Login
Pet database
Product database
Appointment booking
Contact message storage
Order management
E-Commerce Features
Future versions could include:

Add to Cart
Checkout
Online payments
Pet food products
Pet accessories
Order tracking
Customer accounts
🎯 Project Objective
The main objective of PAWORA is to demonstrate how HTML and CSS can be used to create a professional-looking, multi-page website with:

Structured HTML
Reusable CSS
Responsive layouts
Modern UI design
Real-world images
CSS animations
CSS 3D effects
Multi-page navigation
👨‍💻 Author
Shivam Sharma

Project
PAWORA — Premium Pet Shop Website

Built With
HTML5 + CSS3

📌 License
This project is intended for educational and portfolio purposes.

Animal photographs are sourced from Unsplash and remain subject to their respective licenses and terms.