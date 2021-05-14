# Domus Mea Finance site
Domus Mea Finance is still in the process of building their brand name and online presence. 
Setting up a new website is an important step for the company - it will serve as the face of the business, showcasing the company's competence and professionalism and, of course, facilitate contact between new clients and the company. 
<!--(One or two paragraphs providing an overview of your project.
Essentially, this part is your sales pitch.)-->

## UX

As the site user I can easily understand the purpose of the site and the nature of the business.
    This is achieved by: 
        - relevant imagery, tag line in the header;
        - services overview placed right under the header of the Home Page.

As a user I can easily find information about the various services the company offers and focus on those relevant to me.
    This is achieved by:
        - links from services overview in the Home Page to specific sections in the Services page; 
        - minimalisation of scrolling through the use of accordion on Services page and Back to top links.

As a user I can easily locate contact information at any point in my journey. I can get in touch with the company in several different ways, including phone, e-mail and contact form, whichever suits me best. 
    This is achived by implementation of: 
        - sticky footer to show contact info at all times;
        - separate Contact Us page with contact form and the company address.

As a user I want to have the same experience and ease of navigation on mobile devices and desktop: 
    This is achived by: 
        - implementation of different header design for laptops/tablets and mobiles;
        - resising and adjusting the laout of images/text to better fit mobiles.

Links to wireframes (in pdf)
Screenshots of the site. 

<!--(Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.
In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user type, I want to perform an action, so that I can achieve a goal.
This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.)-->

## Features

The site features: 
Home Page: with overview of the services, the company and recommendations 
Services Page: containg more details about each service and their types
Contact Page: a Cotact From <!--(linked to what?)-->
<!--In this section, you should go over the different parts of your project, and describe each in a sentence or so.()-->

### Existing Features
- Links to social media sites - to allow users review recommendations and the company's social media presence
- Contact Form - if preferred, users can submit their contact details and query instead of contacting the company via email directly to avoid being blocked by spam filters
- Services associated with different kind of mortgages presented as accordion

<!--For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.
In addition, you may also use this section to discuss plans for additional features to be implemented in the future:-->

### Features Left to Implement
- Industry news section or blog
- 

## Technologies Used
HTML and CSS

## Testing
### 1st validations: 
#### CSS 

##### ERRORS:
26	body	Value Error : font-weight Too many values or values are not recognized : 1,100  - removed
186	#social-links	Value Error : float center is not a float value : center     - removed
530 .hvr-fade	#a78f18 is not a transition-property value : #a78f18,#fff9ec    - fixed

##### WARNINGS: 
344		-webkit-transition is an unknown vendor extension
345		-moz-transition is an unknown vendor extension
346		-o-transition is an unknown vendor extension
347		-ms-transition is an unknown vendor extension
391		alpha(opacity=0) is an unknown vendor extension
394		-webkit-appearance is an unknown vendor extension
395		-moz-appearance is an unknown vendor extension
402		*height is a CSS hack                                   - removed
403		*width is a CSS hack                                    - removed
407		-webkit-transition is an unknown vendor extension
408		-moz-transition is an unknown vendor extension
409		-o-transition is an unknown vendor extension
410		-ms-transition is an unknown vendor extension
URI : https://koko-66.github.io/Project1_Domus-mea-finance/
8		You should add a type attribute with a value of text/css to the link element - added


<!--In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.
Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.
For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:
1. Contact form:
1. Go to the "Contact Us" page
2. Try to submit the empty form and verify that an error message about the required fields appears
3. Try to submit the form with an invalid email address and verify that a relevant error message appears
4. Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.
You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.
If this section grows too long, you may want to split it off into a separate file and link to it from here.
## Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).
In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.-->

## Credits

Photos from: ...

Contact form radio buttons: https://stackoverflow.com/questions/48561970/css-style-radio-button-with-label-next-to-it
http://ianlunn.github.io/Hover/

Thanks to https://webdesignerhut.com/pure-css-accordion-using-radio-buttons/ and https://tympanus.net/Tutorials/CSS3ImageAccordion/ for the inspiration and parts of code for the accordion sections on the Services page 

As well as to Stackoverflow community and code-boxx for various hints and tips. 

### Content
The text for individual pages was provided in full by Domus Mea Finance owner. 

### Media
<!--- The photos used in this site were obtained from ...-->

### Acknowledgements
- I received inspiration for this project from my friend, Dorota. I hope she will enjoy the site as much as I have enjoyed creating it!
