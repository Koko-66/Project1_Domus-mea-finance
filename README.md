# Domus Mea Finance site
Domus Mea Finance is still in the process of building their brand name and online presence. 
Setting up a new website is an important step for the company. The site will serve as the face of the business, showcasing the company's competence and professionalism, provide information about the services the company offers and facilitate contact between new clients and the company.

## Deployed at
https://koko-66.github.io/Project1_Domus-mea-finance/

## UX

### User Stories
1. As a first-time user:
    - I can easily understand the purpose of the site and the nature of its business.
    - I can easily find information about the various services the company offers and focus on those relevant to me. 
    - I can easily navigate between different parts of the site without unnecessary scrolling.
    - I can find out more about the company, their ethos and accreditations.
    - I can easily locate contact information at any point in my journey through the site. 
    - I can get in touch with the company in several different ways, whichever suits me best.
    - I can check the company's presence and reviews on their social media.

2. As a returning site user:
    - On returning to the site on a different device I have the same experience and ease of navigation.
    - I can easily navigate through the site to find information that is relevant to me. 
    - I can access the company’s social media to leave a review.

### Design

#### Scope

As a starting point, the website is composed of three pages: Home Page, Services and Contact Us page in English. 
This set up allows a quick launch of site as an MVP to achieve its main purpose - increasing the company's online presence and reaching more potential customers. 

The initial scope and ideas about the layout were captured in [wireframes](assets/data/Domus_mea_finance-revised.pdf) at the start of the project. 

As the project progressed certain changes were applied to increase the value for the user: 
- Swapped _Why Choose Us?_ and _Services_ sections on __Home Page__, to make the site's purpose clearer on first access.
- Merged the _About Us_ content that was to be right under the hero image with the _Why Choose Us?_ section.
- _What Our Client's Say?_ section is presented as a simple row of images with reviews at the moment, rather than a carousel. This might be revised at a later stage when more recommendations are available.
- Simplified __Services__ page to better match the amount of available content.
- Considering restrictions on in-person meetings due to the Covid-19 situation, _Where to Find Us_ changed to _Our Address_ on __Contact Page__ without the map for the time being. This might be updated to include Google Maps in the future. 

## Features

### General Features

The website includes the following features: 

#### Header and Footer
Header and footer remain the same across all pages and are fully responsive. 

##### Header features:
- navigation bar at the top with the name of the current page highlighted and a hover animation
- hero image, logo and tagline providing a quick introduction of the business purpose.

##### Footer features:
- company contact details: e-mail address, telephone number and links to social media.
- The e-mail and telephone number are linked to the email and phone clients to facilitate contact directly from the site.
- _Recommend Us on Social Media_ section with links to the social media sites. For the purpose of the course the links are generic but on live site, they will be linked to the company profiles.

The header and footer layout changes to fit in the mobile devices. Screenshots of these are available here: 
- [Desktop layout](assets/data/Large_header_and_footer.png)
- [Mobile layout](assets/data/Small_header_and_footer.png)

#### Home Page: 
__Home Page__ contains the following information: 
- _Our Services_ section with general overview of the three main types of services offered &ndash; mortgages, equity release and protection (or insurance). At the end of each introductory text there is a link to the specific section on that service on the ==Services page==.
- _Why Chose Us?_ section with information about the company, their ethos, experience - the company's selling pitch.
- _What Clients Say?_ section contains reviews lifted from the business's social media sites. 
- _Accredited By_ section with logos of the organisation from which the company received accreditation and is a member of. These link to the organisations' sites, which open in another tab.

The content of each section has been adjusted for viewing on smaller screens: the sections with a row of three images (_Our Services_ and _What Our Clients Say?_) switch to a view of a single image per row with; the text content presented as two columns switches to one column and the _Accredited By_ section becomes hidden.

#### Services: 
This page is split into 3 separate sections with more details about each service type and their sub-types.

##### Mortgages section - accordion:
Being the core service offered by the business, this appears first. 
Having considered that there are 6 types of this service, and the amount of text describing each, I decided to use accordions allowing the user to select the service they would like to read about and hide other content from view. This way the user is not forced to scroll through a lot of irrelevant content while searching for what is of interest to them. 
Residential mortgages, being most of the the company's business, were chosen as the section visible to the user when  first loading the page.

The accordion showing on the larger devices (over 700px) is different to that used on smaller devices and both have been scripted using only CSS (radio-buttons with transition and display: none methods, using inspiration and ideas from an existing site and a tutorial, see [Credits](#credits) section below).

Accordion on large screen: 
(image here)

Accordion on smaller screen: 
(image here)

The initial idea for an accordion was a bit different to the final design. The accordion worked similarly but was arranged with labels running vertically on the side of individual divs, which my mentor recommended to change to improve user experience since it caused difficulty reading. 

##### Equity Release and Protection sections: 
These are relatively text-heavy, therefore are presented on larger screens as two columns and one column on smaller ones. 
Rather than using 'columns' within a paragraph, I used div elements to have greater control over how the text is split when the screen size changes. 

#### Contact Us Page: 

__Contact Us__ page offers the user an option to contact the company using contact form.
It includes front-end validation of input: 
- name, e-mail and telephone number are set to required values;
- e-mail requires an email format;
- at least one option must be selected in 'What are you interested in?' to be able to submit the form.

As expected, at present the form is not connected to any database. 

### Features Left to Implement
- Cookies to track traffic and GDPR information on form
- A Polish version of the site
- Section linking to industry news
- Add highlight/colour to the selected label in the large accordion
- adjust design for Dark mode

## Technologies Used

### Languages
- HTML
- CSS

### Frameworks, Libraries and Programs used

- VS Code: used as the primary code editor
- Git: used for version control
- Git Hub: used to store project files
- Google Fonts: used to import fonts used in the project: Nunito and Relay
- Font Awesome: used for the social links icons in the footer
- Affinity Designer: to resize and adjust the images for the website
- Balsamiq: to create wireframes
- Lighthouse (Chrome extension): used to check the performance and accessibility of the website
- JS-CSS-HTML Formatter (VS Code extension): used to beautify the HTML and CSS code
- Dev Tools on Chrome and Safari: used for code testing and trials

## Testing

### Testing performance
1. W3C Markup Validator - [Results](assets/data/HTML_validation.pdf)
2. W3C CSS Validator - [Results](assets/data/CSS_Validation.pdf)
    - the validator picked up 13 errors all relating to the use of -webkit elements. Considering compatibility with different browsers a priority, I decided to ignore these warnings and keep these elements.
3. Run Lighthouse extension to check site performance. Results: [Home Page](assets/data/Lighthouse_Report_HomePage.pdf), [Services](assets/data/Lighthouse_Report_Services.pdf), [Contact Us](assets/data/Lighthouse_Report_Contact-Us.pdf)
4. Tested the form and all devices listed below
5. Tested for responsiveness and display on various devices: 
    - Android (Samsung S8, Samsung Note8, Xiaomi)
    - iOS (iPhone S6) 
    - iPad Pro 9.7 inch
    - Microsoft Surf 11 inch
    and browsers:
    - Safari
    - Chrome 
    - Firefox
    - Edge
    - Opera

#### Bugs and fixes: 
- Labels in large accordion on the Services page were not showing vertically on Safari; fixed issue by adding 'display: inline-block;' to .accordion-h.
- On iPad Pro 9.7 inch in portrait view, the gap between the two columns in section using this layout was not visible; fixed by changing 'gap' styling to 'padding'.
- In the Contact form, telephone number did not allow for a format with country code using '+'. Changed field type from number to 'tel'.
- The images in _Our Services_ section on __Home Page__ when resizing the screen were pushed out of line. To fix it, changed the layout to fit text and images in separate divs on larger screens. 
- The fix above caused and issue with the images no longer being visible on mobile. Fixed by duplicating the images in the paragraphs and setting them to 'display:none;' on larger screens.
- The site does not have enough contrast when viewed in dark mode. This is still to be investigated.

## User Testing

1. As a first-time user:
    - I can easily understand the purpose of the site and the nature of its business: 
        - On first opening the website I can identify the purpose of the site through the images, tagline and summary of services visible right below the hero image.

    - I can easily find information about the various services the company offers and focus on those relevant to me. 
        - On first opening the page, I can see a summary of the services right below the header. I can see the link to a separate page with services on the navigation menu at the top.
        - I can focus on the information relevant to me by selecting to read about the services type that interest me. I can use links to specific sections on the **Services** page, e.g., Mortgages, and then choose to read only about the type of mortgage that interests me by selecting a relevant heading in the accordion.

    - I can easily navigate between different parts of the site without unnecessary scrolling.
        - The site contains navigation bar, links to specific sections of the **Services** page on **Home Page** and _Back to Top_ link at the bottom of **Home Page** and **Services**.

    - I can find out more about the company, their ethos and professional affiliations.
        - Home Page includes _About us_ and _Why Choose Us?_ sections with company statement, recommendations, and logos of professional bodies of which the company is a member with links to their sites. 

    - I can easily locate contact information at any point in my journey through the site. 
        - There is a separate **Contact Us** accessible from the navigation menu.
        - Footer with contact details is always visible.

    - I can get in touch with the company in several different ways, whichever suits me best.
        - The contact details provided include: e-mail, telephone number and Contact Us form.

    - I can check the company's presence and reviews on their social media.
        - The footer contains icons linked to business's social media site.

2. As a returning site user:
    - On returning to the site on a different device I have the same experience and ease of navigation.
        - Ensured that all features work in the same way on all browsers.
        - Responsive design to ensure that each page displays content in a way that is suitable for the size of the screen being used.

    - I can easily navigate to the information that is relevant to me. 
        - Various links and organisation of the content make it easy for me as a user to find and focus specifically on the information relevant to the me.

    - I can access the company's social media to leave a review.
        - Footer contains a section _Recommend Us_ links to social media pages.

## <a name="credits"></a> Credits

Great thanks to: 
- my mentor for pointing me in the right direction and making sure I am on track
- Hover.css for help in styling footer animations and Contact From submit buttons
- https://webdesignerhut.com/pure-css-accordion-using-radio-buttons/ and https://tympanus.net/Tutorials/CSS3ImageAccordion/ sites for the inspiration and parts of code for the accordion sections on the Services page
- photographers kindly allowing for a free use of their photos via the sites mentioned in the Media section below: Andrea Piacquadio, Kindel Media, William Fortunato, Tma Miroshnichenko, PNW Production, Moose Photos, Mikhail Nilov, Lukas and Andrew Neel, Marek Studziński, Matthew Sleeper, Viktor Hanacek
- Stackoverflow community and code-boxx for various hints and tips

### Content
The text for individual pages was provided in full by Domus Mea Finance owner. 

### Media
- The photos used in this site were obtained from [Pexels](https://www.pexels.com/), [Unsplash](https://unsplash.com/) and [Pickjumbo](https://picjumbo.com/). Individual artists are mentioned in the [Credits](#credits) section above.