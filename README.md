This README provides a comprehensive overview of the structure, components, and usage of the Careers page for the Shamrockseniors (PVT) LTD website. It includes technical details, design intentions, and instructions for future maintenance or updates.

Table of Contents 1. Project Overview 2. Folder & File Structure 3. Page Purpose 4. HTML Structure 5. Design & Styling 6. Navigation & Routing 7. Content Categories 8. Footer Details 9. Responsive Design 10. Future Enhancements

1. Project Overview
   This page is part of the Shamrockseniors website and serves as the central hub for current and potential employees seeking information about available roles, benefits of working with Shamrockseniors, and career development.

2. Folder & File Structure

project-root/
|-- index.html (this page)
|-- styles/
| |-- main.css
|-- pages/
| |-- nursing.html
| |-- management.html
| |-- nchd.html
| |-- consultant.html
| |-- patient-care.html
| |-- allied-health.html
| |-- support-staff.html

main.css contains global styles.

Each job category links to a dedicated HTML page for role listings.

3. Page Purpose
   The goal is to:
   Offer an overview of Shamrockseniors as an employer.
   Allow users to browse open positions by category.
   Provide easy access to HR and career resources.

4. HTML Structure
   The HTML layout is divided into logical sections:

<head>

Page title: Careers @ Shamrockseniors

Meta tags for responsive design and SEO.

Linked stylesheet: styles/main.css

<body>

Header
Contains the main title Careers.
Includes breadcrumb navigation.
Social sharing links.
Main Content
Intro Section: Briefly describes the company culture and career opportunities.
Browse by Category: Grid layout linking to various job categories.
Quick Links: Provides additional links to other relevant HR and career-related content.

Footer
Displays company name and physical address.
Provides a clickable telephone link.

5. Design & Styling
   Styled using main.css.
   Color palette and card design are consistent with the overall site branding.
   Utilizes a grid layout for the category cards.
   Typography and spacing optimized for readability.

6. Navigation & Routing
   Each card in the "Browse by Category" section links to a corresponding HTML file in the /pages directory. These are static pages prebuilt with role listings and category-specific content.
   Breadcrumb navigation is static and currently just a placeholder: Home / Careers. Consider enhancing with real routing if JavaScript or server-side rendering is introduced later.

7. Content Categories
   Currently supported categories:
   Nursing
   Management / Admin / ICT
   NCHD
   Consultant
   Patient & Client Care
   Allied Health & Social Care
   General Support Staff

Each links to an individual page detailing job roles in that area.

8. Footer Details
   The footer contains:
   Company name
   Full address in Sri Lanka
   Clickable telephone link

The footer is uniform and intended to appear across all pages for consistency and professionalism.

9. Responsive Design
   The layout is responsive and scales across mobile, tablet, and desktop devices. Key elements include:
   meta viewport tag for mobile scaling
   Grid-based layout in the Browse section
   Mobile-friendly navigation and spacing

10. Future Enhancements
    Add JavaScript for improved routing and breadcrumb logic.
    Include CMS integration for dynamic job listings.
    Add animations or hover effects for cards.
    Enable form submission for CV or application upload.
    Add accessibility enhancements (ARIA tags, keyboard nav).
    Implement analytics tracking on share links.

Contact
For support or contributions, please contact: contact@shamrockseniors.com
This README was generated to help developers and collaborators understand the purpose, structure, and maintenance of the Shamrockseniors Careers webpage.
