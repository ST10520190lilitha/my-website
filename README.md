Forever Living by Sindi Jubati

Student Name: Lilitha Jubati Student Number: ST10520190 Module: Web Development (Introduction) Module Code: WEDE5020 Project: Forever Living Website

Project Overview

This project is a website created for a local Forever Living business owned by Sindi Jubati. Forever Living Products is a wellness company founded in 1978 that is best known for its aloe vera-based products [1]. The purpose of the website is to provide an organised and easy-to-use platform where customers can view the products available, learn more about the business, find contact information and make product enquiries.

The website was created to make it easier for the business owner to advertise and provide information about her products. Instead of having to search through a phone gallery or PDF to find a specific product, the products can be displayed and accessed directly through the website.

Website Goals and Objectives

The main goal of this website is to make managing and advertising the business's products easier and more efficient.

The objectives of the website are to:

Display Forever Living products in an organised way.
Provide information about the different products.
Make product information easier for customers to find.
Provide contact information for the business owner.
Allow customers to submit enquiries.
Create a simple and professional online presence for the business.
Make it easier for the business owner to advertise products to customers.
Website Pages
Homepage

The homepage introduces the Forever Living business and provides an overview of what the business offers. It includes the business name, branding and navigation links to the other pages.

About Us

The About Us page provides information about the specific business owner and the Forever Living business. This helps customers understand who is behind the business.

Products

The Products page displays the different Forever Living products available in three categories: Aloe Drinks, Skincare & Anti-Aging, and Personal Care. Products include images, names, prices and information about their listed benefits. Product details are adapted from the manufacturer's product information [1]. The page also includes a search feature that filters the product tables as the visitor types.

Contact Us

The Contact Us page provides customers with information on how to contact the business owner. It includes a contact form with validation and location information (an embedded map) to help customers find the business.

Enquiry

The Enquiry page contains a form that allows customers to submit questions or enquiries about the products. Users enter their name, phone number and email address, select a product category and write their enquiry. The form is validated before it is accepted.

Key Features
Responsive website layout.
Navigation menu connecting all main pages, with a CSS-only mobile menu.
Product catalogue with images and prices.
Product search functionality (JavaScript).
Contact form and enquiry form with JavaScript validation [2].
Live clock in the footer of each page (dynamic content) [3].
Contact information.
Embedded map/location section.
Business information and branding.
Custom CSS styling.
Product images stored in the Assets folder.
IEEE-style in-text citations and reference lists on every page.
Technologies Used

The website was developed using:

HTML5 – Used to create the structure and content of the website.
CSS3 – Used to style the website, including colours, fonts, spacing and layout.
JavaScript – Used for form validation, the product search and the live clock.
Images – Used to display the Forever Living logo and product images.
Git/GitHub – Used for version control and managing the project.
Project Structure
text
my-website/
│
├── index.html
│
├── Pages/
│   ├── about.html
│   ├── contact.html
│   ├── enquiry.html
│   └── products.html
│
├── Assets/
│   ├── css/
│   │   └── style.css
│   │
│   └── images/
│       ├── forever-living-logo_8268.png
│       ├── Aloevera gel.jpg
│       ├── berry nector.jpg
│       ├── Forever Aloe Peaches.jpg
│       ├── Hydrating Serum.jpg
│       ├── Forever Marine Collagen (box of 30 Sachets).jpg
│       ├── Infinite Skin Care (ANTIAGING solution).jpg
│       ├── Inifinite By Forever hydrating cleaner.jpg
│       ├── Infinite By Forever firming serum.jpg
│       ├── Inifinite by Forever restoring creme.jpg
│       ├── Logic by Forever Skin Care System (NEW).jpg
│       ├── Logic by forever aloe gel cleasner.jpg
│       ├── Logic by Forever Balancing Aloe Essence.jpg
│       ├── Logic by Forever Soothing Gel Moisturizer.jpg
│       ├── Aloe Lips.jpg
│       ├── Forever Bright Toothgel.jpg
│       └── Aloe Ever-Shield.jpg
│
└── README.md
Design

The website uses a natural colour scheme based around green, cream/beige and brown/gold tones. These colours were chosen to create a clean and natural appearance that matches the type of products being advertised.

The website uses a combination of Georgia/Times New Roman and Arial fonts to create a simple but professional appearance. Product images are also used to make it easier for customers to identify products.

Target Audience

The target audience is customers who are interested in Forever Living products, including skincare, nutritional products, fitness and weight-loss products and immune-support products.

The website is also designed to help the business owner by providing an organised way to present product information to customers.

How to Run the Website

The website is a static HTML website, so it does not require a server or database to run.

To open the website:

Download or clone the project.
Open the my-website folder.
Open index.html in a web browser.
Use the navigation menu to move between the different pages.

The website can also be opened using a code editor such as Visual Studio Code with a live-server extension.

Future Improvements

Some improvements that could be made to the website in the future include:

Adding an online shopping/cart system.
Connecting the contact and enquiry forms to a database or email service, so submissions are actually delivered (the forms currently use action="#" as a placeholder).
Adding more products and product categories.
Improving the search functionality.
Adding customer reviews.
Adding social media links.
Improving accessibility features.
Adding more responsive design features for mobile devices.
Adding a secure online payment system if online purchasing is introduced.
Timeline and Milestones
Date	Type of Submission
14 August 2026	Part 1
8 September 2026	Part 2
Conclusion

The Forever Living website provides a simple online platform for displaying products and business information. It makes it easier for customers to find product information and contact the business owner. The website also reduces the amount of time the business owner needs to spend searching through pictures or documents when customers ask about specific products.

This project demonstrates the use of HTML, CSS, JavaScript, images, navigation, forms and basic website design principles to create a functional business website.

References

References are in IEEE style and numbered in the order they are first cited in this document.

[1] Forever Living Products, "Forever Living Products." Accessed: Nov. 2, 2026. [Online]. Available: https://www.foreverliving.com

[2] MDN Contributors, "Client-side form validation," MDN Web Docs. Accessed: Nov. 2, 2026. [Online]. Available: https://developer.mozilla.org/docs/Learn_web_development/Extensions/Forms/Form_validation

[3] MDN Contributors, "Date," MDN Web Docs. Accessed: Nov. 2, 2026. [Online]. Available: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date

#Part 3

##Changelog for Part 3

###Contact page

Added JavaScript validation to the contact form, based on the approach in [2].

Required fields: if the user leaves a field empty, the message "All input fields are required." is displayed.

Email: if the email address is not in a valid format (for example, it has no @ sign), the message "Incorrect email format." is displayed.

Phone number: the number must be 10 digits long and start with 0, otherwise an error message is displayed.

Message length: the message must be at least 10 characters long.

When the form meets all the requirements, the message "Your message was submitted successfully." is displayed and the form is cleared.

Fixed the phone number field: its id contained a space and did not match its label.

Removed a check for a "surname" field that does not exist on the form, and the duplicated clock code that stopped the script from running.

###Enquiry 

Rebuilt the page structure: the Submit button and the script were outside the form, and the closing tags were missing.

Added a product category drop-down, a phone number field, and the same validation as the contact page.

Added error and success messages that the script can display.

Changed the page heading from "Project Inquiry Form" to "Enquiry Form".

###Products page

Added a product search that filters the tables as the visitor types.

Added table captions and proper table headers (thead and tbody) for accessibility.

Replaced the Forever Aloe Peaches benefits, which had been copied from a face gel product.

Added a note that the information is not medical advice.

###About page

Removed JavaScript for a hamburger menu, accordion and lightbox that do not exist on the page and caused errors.

Made the business name in the title and footer consistent with the other pages.

###All pages

Added the live clock to the footer (the script existed but the element it needed was missing).

Added IEEE-style in-text citations and a numbered reference list to every page, matching the references in this README.

Added aria-current to the active menu link and a description meta tag to each page.

###CSS

Removed a leftover merge-conflict marker (HEAD) and merged the duplicated contact and enquiry form styles.

Added styles for phone number inputs, submit buttons, form messages, table captions and the reference lists.