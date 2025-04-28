# airbnb-clone-project
Overview
This project is a simplified clone of the Airbnb platform, built to practice and demonstrate skills in full-stack web development. The goal is to replicate core features such as property listings, booking functionality, and user authentication, with a focus on clean UI/UX design.

Project Goals
Build a responsive, modern web application.

Implement user authentication (sign up, login, logout).

Create listings with images and descriptions.

Allow users to book available listings.

Learn and apply best practices for front-end and back-end development.

Tech Stack
Front-end: React.js, Tailwind CSS

Back-end: Node.js, Express.js

Database: MongoDB

Authentication: JWT (JSON Web Tokens)

Hosting: Vercel / Render / MongoDB Atlas

**UI/UX Design Planning**
Design Goals
Create a clean, intuitive, and responsive interface.

Ensure seamless navigation between pages.

Provide clear actions for users to view listings, explore details, and complete bookings.

Focus on minimizing clicks and maximizing ease of use.

Key Features
Browse property listings with images and prices.

View detailed information about each property.

Book properties through a simple, streamlined checkout process.

Mobile-friendly and fast-loading pages.

Primary Pages Overview

Page Name	Description
Property Listing View	Displays a grid or list of available properties with images, prices, and short descriptions. Users can filter and sort listings.


**Design Properties**

Color Styles
Primary Color: Green (#2E7D32) (based on the button and splash screen color seen)

Secondary Color: Dark Green / Black (#1B5E20) (for logo and text)

Secondary Color (light): Light Gray (#EEEEEE) (backgrounds, lighter elements)

Shimmer: Light Accent Color for Loading/Effects

Typography
Font Family: Likely a clean sans-serif (e.g., Poppins, Roboto, or similar) — check Figma properties if specified.

Font Weights:

Bold for headers (e.g., "Find your favorite place here")

Regular for body text (email/password fields)

Font Sizes:

Large size (~24–32px) for headers

Medium (~16–18px) for normal text and buttons

Small (~12–14px) for captions (e.g., “Forgot Password?”, "Join now")

Importance of Identifying Design Properties
Understanding the color styles, typography, and design properties of a mockup ensures consistency throughout the project. It allows developers and designers to maintain the same look and feel across different pages and components. It also speeds up the development process, improves collaboration, and creates a more professional and polished final product. Proper alignment to the mockup builds trust with users and ensures a cohesive user experience across the platform.


Listing Detailed View	Shows full details of a selected property, including images, amenities, location map, availability calendar, and a "Book Now" button.
Simple Checkout View	A minimal page where users confirm their booking by entering basic details (name, dates, payment info) and completing the reservation.
Importance of User-Friendly Design
A user-friendly design is crucial in a booking system because it reduces friction, builds trust, and improves the likelihood of users completing a booking. Clear layouts, intuitive navigation, and quick load times create a better user experience, leading to higher customer satisfaction and better conversion rates.


## Project Roles and Responsibilities

### Project Manager
- Oversees the project and ensures deadlines are met.
- Coordinates communication among team members.
- Tracks project progress and reports to stakeholders.

### Frontend Developer
- Develops the user-facing side of the application.
- Works closely with the UI/UX team to implement designs.

### Backend Developer
- Builds and maintains the server-side logic.
- Ensures data flows seamlessly between the frontend and backend.

### Designer
- Creates wireframes, prototypes, and final designs for the application.
- Collaborates with frontend developers to implement designs.

### QA/Testers
- Tests the application for bugs and usability issues.
- Ensures the application meets quality standards before release.

### DevOps Engineer
- Manages deployment pipelines and cloud infrastructure.
- Ensures the application is scalable and secure.

### Product Owner
- Defines the project goals and requirements.
- Acts as the voice of the customer and prioritizes features.

### Scrum Master
- Facilitates agile ceremonies (daily standups, sprint planning).
- Helps the team stay on track and removes blockers.
- 
## UI Component Patterns

### Navbar
- A top navigation bar that provides links to key sections of the app like Home, Search, and Profile.
- The navbar will also include a logo, a search bar, and user authentication options (login/signup).

### Property Card
- A card displaying a brief overview of each property, including an image, title, price, and key details like location and availability.
- Clicking on a Property Card will navigate to the Listing Detailed View page.

### Footer
- A footer with links to the About Us, Terms of Service, and Privacy Policy pages.
- The footer will be displayed at the bottom of all pages.



