# Domus Mea Finance site
Domus Mea Finance is still in the process of building their brand name and online presence. 
Setting up a new website is an important step for the company. The site will serve as the face of the business, showcasing the company's competence and professionalism, provide information about the services the company offiers and facilitate contact between new clients and the company.

## Deployed at
https://koko-66.github.io/Project1_Domus-mea-finance/

## UX

### User Stories
1. As a first-time user:
1.1. I can easily understand the purpose of the site and the nature of its business.
1.2. I can easily find information about the various services the company offers and focus on those relevant to me. 
1.3. I can easily navigate between different parts of the site withough unnecessary scrolling.
1.4. I can find out more about the company, their ethos and professional affiliations.
1.5. I can easily locate contact information at any point in my journey through the site. 
1.6. I can get in touch with the company in several different ways, whichever suits me best.
1.7. I can check the company's presence and reviews on their social media.

2. As a returning site user:
2.1. On returning to the site on a different device I have the same experience and ease of navigation.
2.2. I can easily navigate to the information that is relevant to me. 
2.3. I can access the comapny's social media to leave a review.

### Design

#### Scope

As a starting point, the website is composed of three pages: Home Page, Services and Contact Us page in English. 
This set up allows a quick launch of site at its MVP to achieve its main purpose - increasing the company's online presence and reaching to more potential customers. 

This initial scope and ideas on the layout were captured in [wireframes](assets/data/Domus_mea_finance-revised.pdf), at the very start of the project. 

As the project progressed certain changes were applied to increase the value for the user: 
- swapped 'Why Choose Us?' and 'Services' sections on Home Page, to make the site's purpose clearer on first access.
- Merged the 'About Us' conent that was to be right under the hero image with the 'Why Choose Us?' section.
- 'What Our Client's Say?' section is presented as consequtive images at the moment. This might be revised at a later stage when more recommendations are available.
- Simplified Services page to better match the amount of available content.
- 'Where to Find Us' changed to 'Our Address' that includes address only, without map for the time being, considering restrictions on in-person meeting due to the Covid-19 situation. This might be updated to include Google Maps in the future. 

## Features

### Genearal Features

The website includes the following features: 

#### Header
Header is the same throughout all pages and contains:
- navigation bar at the top with the name of the current page highlighted;
- hero image, logo and tagline providing a quick introduction of the business purpose.
The header layout changes to fit in the mobile devices. Screenshots of these are available here: 
[Desktop layout](link)
[Mobile layout](link)

#### Footer
Footer is also the same across all pages and remains visible throughout the whole time the user is on the site. It contains: 
- company contact details: e-mail and telephone number;
- The e-mail and telephone number are linked to the email and phone clients to facilitate contact directly from the site;
- 'Recommend Us on Social Media' section with links to the social media sites. For the purpose of the course the links are generic but on live site, they will be linked to the company profiles.

The footer's layout also changes when displayed on mobile devices. Screenshots of these are available here: 
[Desktop layout](link)
[Mobile layout](link)

#### Home Page: 
'Home Page' contains the following information: 
- General overview of the three main types of services offerred &ndash; mortgages, equity release and protection (or insurance). At the end of each introductory text there is a link to the specific section on this particular services on the 'Services' page.
- 'Why Chose Us?' section with information about the company, their ethos, experience - its selling pitch.
- 'What Clients Say? section contains reviews lifted from the business's social media sites. 
- 'Accredited By' section with logos of Professional Bodies from which the company received accreditationa and of which it is a member.  
The content of each section has been adjusted for viewing on smaller screens: the sections with a row of three images ('Our Services' and 'What Our Clients Say?') switch to a view of a single image; the text content presented as two columns switches to one column and the 'Accredited By' section becomes hidden.

#### Services: 
This pages is split into 3 separate sections with more details about each service type and their sub-types.

##### Mortgages section - accordion:
Being the core service offered by the business, this appears first. 
Having considered the number of various types of this service, and the amount of text for each, I decided to use accordions to allow the user select the service they would like to read about and hide most content from view. This way the user is not forced to scroll through a lot of irrelevant conent while searching for what is of interest to them. 
Residential mortgages, being the majority of the company's business, were chosen as the section visible to the user when  first loading the page.

The accordion showing on the larger devices (over 750px) is different to that used on smaller device and both have been scripted using only CSS (radio-buttons with transition and display;hidden methods, using inspiration and ideas from an existing site and a tutorial, see [Credits](link) section below).

Accordion on large screen: 
(image here)

Accordion on smaller screen: 
(image here)

One piece of feedback and recommendation I received from my mentor about this feature was to avoid using vertical labels and change the style of the accordion on larger devices to match that of the smaller to improve user's reading experience. While I think that large accordion has aesthetic value and makes the site that little bit more interesting, I the user experience is a priority, so this feature will be further discussed with the client and consulted with a sample of users. 

##### Equity Release and Protection sections: 
These are relatively text-heavy and have been presented on large screen as two columns on larger devices and one column on smaller. 
The two columns are enclosed in div elements rather than simple columns, to allow for a better control over how the text is split. 

#### Contact Page: 

Contact page offers the user an option to contact the company using contact form.
It includes front-end validation of input: 
- Name, e-mail and telephone number are set to required values;
- e-mail requires the an email format and does not allow f
- telehone field accepts only phone format and no text
- At least one option has to be selected in 'What are you interested in?' to be able to submit the form.

<!-- As expected, at preent the form is not connected to any database.  -->


### Features Left to Implement
- Cookies to track traffic and GDPR information on form
- A Polish version of the site
- Section linking to industry news

## Technologies Used

### Languages
- HTML5
- CSS3
<!-- - PHP -->

### Frameworks, Libraries and Programs used

- VS Code: as the primary code editor
- Git: for version control
- Git Hub: to store project files
- Google Fonts: used to import fonts used in the project: Nunito and Relay
- Font Awesome: used for the social links icons in the footer
- Hover.css: for styling Contact From submit buttons
- Affinity Designer: to resize and adjust the images for the website
- Balsamiq: to create wireframes
- Lighthouse (Chrome extension): used to check the performance and accessibility of the website
- JS-CSS-HTML Formatter (VS Code extension): used to beautify the HTML and CSS code
- Dev Tools on Chrome and Safari: used for code testing and trials

## Testing

### Testing performance
1. [W3C Markup Validator - Results] (link to results)
2. [W3C CSS Validator - Results]
3. Run Lighthouse extension to check site performance. <!--[Results](...)-->
4. Tested for responsiveness and display on various devices: 
- Android (Samsung S8, Samsung Note8, Xiaomi)
- Samsung Browser
- iOS (iPhone S6) 
- Safari
- Chrome 
- Firefox
- iPad Pro 9.7 inch
<!-- - Microsoft Surf 11 inch -->
#### Bugs and fixes: 

- Labels in large accordion on the Services page were not showing horizontally properly on Safari; fixed issue by adding "display: inline-block;" to .accordion-h.
- On iPad Pro 9.7 inch in portrait view, the gap between the two columns in section using this layout was not visible; fixed by changing the "gap" styling to "padding".
- In the Contact form, telephone number did not allow for a format with country code 

## User Testing

1. As a first-time user:
1.1. I can easily understand the purpose of the site and the nature of its business: 
- On first opening the website I can identify the purpose of the site through the images, tagline and summary of servies visible right below the hero image.

1.2. I can easily find information about the various services the company offers and focus on those relevant to me. 
- On first opening the page, I can see a summary of the services right below the header. I can see the link to a separate page with Services on the navigation menu at the top.
- I can focus on the information relevant to me by selecting to read about the services type that interst. I can use links to specific sections on the Services Page, e.g. Mortgages, and then choose to read only about the type of mortgage that interests me by selecting relevant heading in the accordion.

1.3. I can easily navigate between different parts of the site without unnecessary scrolling.
- The site contains navigation bar, links to specific sections of the Services Page on Home Page and "Back to Top" link at the bottom of Home and Services Pages
<!-- - Links back to top after each section on Services Page? -->
<!-- - Links to the sectiions lower on the Home Page? -->

1.4. I can find out more about the company, their ethos and professional affiliations.
- Home Page includes "About us" and "Why Us?" sections with company statement, recommendations and logos of professional bodies of which the company is a member with links to their sites. 

1.5. I can easily locate contact information at any point in my journey through the site. 
- Contact Us section is clearly visible in the navigation menu.
- Footer, that is always visible, contains contact details.

1.6. I can get in touch with the company in several different ways, whichever suits me best.
- The contact details provided include: e-mail, telephone number and Contact Us form.

1.7. I can check the company's presence and reviews on their social media.
- The footer contains icons linked to business's social media site.

2. As a returning site user:
2.1. On returning to the site on a different device I have the same experience and ease of navigation.
- Various parts of each page change depending on the size of the screen
 <!-- i.e. layout of services section  -->

2.2. I can easily navigate to the information that is relevant to me. 
- Various links and organisation of the content makes it easy to focus specifiacally on the information relevant to you.

2.3. I can access the comapny's social media to leave a review.
- Footer contains a section "Recommend Us" links to social media pages.

## Credits

- Thank you to my mentor for pointing me in the right direction and making sure I am on track. 
- A great thanks to photographers kindly allowing for a free use of their photos via the sites mentioned in the Media section below: Andrea Piacquadio, Kindel Media, William Fortunato, Tma Miroshnichenko, PNW Production, Moose Photos, Mikhail Nilov, Lukas and Andrew Neel, Marek Studziński, Matthew Sleeper, Viktor Hanacek
- Thanks to https://webdesignerhut.com/pure-css-accordion-using-radio-buttons/ and https://tympanus.net/Tutorials/CSS3ImageAccordion/ for the inspiration and parts of code for the accordion sections on the Services page

- And of course to Stackoverflow community and code-boxx for various hints and tips. 

### Content
The text for individual pages was provided in full by Domus Mea Finance owner. 

### Media
- The photos used in this site were obtained from [Pexels](https://www.pexels.com/), [Unsplash](https://unsplash.com/) and [Pickjumbo](https://picjumbo.com/)

### Acknowledgements
- I received inspiration for this project from my friend, Dorota. I hope she will enjoy the site as much as I have enjoyed creating it!
