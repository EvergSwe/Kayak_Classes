# Kayak Freedom

![Responsive Test](/assests/img/responsive_check_kayaking_classes.PNG)

[View website on GitHub pages](https://github.com/EvergSwe/Kayak_Classes)

[View website](https://evergswe.github.io/Kayak_Classes/)

## UX process

### Strategy
Welcome to Kayaking Freedom - we provide kayaking cources for you to be safe out on the water, challenge yourself in small steps to be able to get close to the nature. We will prepare your skills for enjoyable experiences and lifelasting memories. Kayaking Freedom target middle age women and men who seek peace and harmony in life and in the same time keep up their health while doing so. Secondary target group are kids to target group one. Kayaking freedom love to see the whole family attending a course. Connecting with us should be easy.

### Scope
Minimal viable product to be created for the purpose of user feedback. Functionality aligned with strategy, easy navigation and easy to connect with good usability. Content shall be telling the story of each section with a hearo image creating feelings and awareness about Freedom, Safety, exposed environment where the kayaker need to trust their own competence.

### Structure & Skeleton
Pen and paper were used to build up different versions of wireframes where multi-page vs. single page structure where evaluted. One Page design approched where choosed as the scope is flat one-subject and one dimensional information structure with intention to connect with Kayaking Freedom to know more about the courses.

### Surface
 Natural color pattern chosed based on hero image toggle color picker of subject water, cliffs and sand to create consistancy between images and content.
 
 ![color_schema](/assests/img/color_schema1.png)
 
 Font style of headings choosed in the sama natural theme and remaining text for primarly for readability.

## Existing Features

### The Header
The header is fully responsive with maintained usability for different screen sizes. Small screens one column set-up with Logo on top followed by the Section links belwo, medium screens two rows with Logo on top and section links below and for wide screens one row with logo on the left and section links on the right. First intention was to keep a fixed top bar to easely navigate between different section, only visible at scrolling. However I did not mange to find solution without java code why this will be kept to next inctement for further development. MVP solution for top bar has an absolut positioning top of the page which has less usability as scrolling back to home is needed.

![Top bar design](/assests/img/tob_bar_design.PNG)

### Landing Page
Full screen landing page with a photograph with text overlay and button linking to contact form to easely connect for a kayaking course. All centralized with positioning and font-size fully responsive.

![Landing page](/assests/img/landing_page.PNG)

### Kayaking Section
Section intend to be informative, the things you need, putting safety as number one. Image chosed covering the scope of the text, full width to visually create a page break to the section. Section is fully responsive with image and text adapting to different screen sizes.

### Technique Section
Intend to provide the reader an understanding of the learning process in few headings, beginner to advanced. Image chosed covering the scope of the text, full width to visually create a page break to the section. Section fully responsive. 

### About Us Section
About us Secion intend to find out where we are located, get in contact by call, email or sending a form. Section is fully responsive

- Contact Details
  - Centralized contact details
  - Mailto functionality opening up your default email provider with mail address to Kayaking Freedom filled.

- Map
  - Embeded google map iframe fully responsive
  - full width to act as page breaker

- Connect with us form
  - form include types of text, email, options, input/reset button
  - validation rules for required data
  - validation rules for email character @
  - when submited form data is inserted to database table at Code Institute

### Footer

Footer section including links to social media sites for Kayaking Freedom. Links will open to new tab to allow easy navigation for the user.

### Development planned for next increment

- to improve the usability the topbar is to be fixed on top of the screen and visibal when scrolling is activated, else hidden.

- form pushed to email when submited to replace the existing data base insert with a confiramtion message

## Testing

### Feature testing
- [X] test case 1, Links in navigation bar shall take the user to beginning of relevant section without any issues
- [X] test case 2, Links in navigation bar shall change color when hovering cursor over relevant object
- [X] test case 3, 'Connect with us to join a course' button shall take the user to beginning of 'About us' section without any issues
- [X] test case 4, 'Connect with us to join a course' shall change color when hovering cursor over the object
- [X] test case 5, Google map shall have the point of interest in center of the map in all formats
- [X] test case 6
- [X] test case 7, Form required field shall have input
- [X] test case 8, Form input type validation
- [X] test case 9, Form shall have submit butten pushing infromation to code institute database
- [X] test case 10, form submit button shall change color when hovering cursor over
- [X] test case 11, form reset button shall clear form input
- [ ] test case 12, form reset button shall change color when hovering cursor over.
  - [X] test case 12.1, Colors where switched and after corrections successful test
- [X] test case 13, social link to Facebook shall open up separate browser tab when selecting
- [X] test case 14, social link to Twitter shall open up separate browser tab when selecting
- [X] test case 15, social link to Instagram shall open up separate browser tab when selecting

### Browser interface testing (UI)
Above 15 test cases where performed in below browser to verify viewport and feature functionality.

- Google Chrome (desktop device)
  - full responsiveness confirmed in google devtools for all 15 test cases without any issues

- Microsoft Edge (desktop device)
  - full responsiveness confirmed in google devtools for all 15 test cases without any issues

- Safari (mobile device)
  - feature validation performed in mobile device as I had no access to desktop version.
  - All 15 test cases passed the test

- Internet Explorer
  - Internet will soon be expired and replaced with Microsoft Edge
  - Test performed with poor result and below diviations identified
  - Rendering of webp images doesn't work
  - Google responsive map is not supported
  - Positioning of footer above form

### Automated testing

Automated testing of html, css programming language has been done by using third party tools. Google Chorme extension devtools, Lighthouse, has been used for general improvements of webpage quality. It has audits for performance, accessibility, progressive web apps, SEO

1. [HTML Validator by w3.org 'validator'](https://validator.w3.org/#validate_by_uri)

- Result
![HTML Validator](/assests/img/html_validation.PNG)

  - As select require None value option, adding 'option value="">None</option' resolved the error

2. [CSS Validator by w3.org 'jigsaw'](https://jigsaw.w3.org/css-validator/)

- Result
  - Passed without remarks
  <p>
    <a href="http://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
</p>

3. [Google Chrome Lighthouse Extension](https://developers.google.com/web/tools/lighthouse)

- Lighthouse test mobile:

![Lighthouse mobile test](/assests/img/lighthouse_check_kayaking_classes_mobile.PNG)

- Lighthouse test desktop:

![Lighthouse desktop test](/assests/img/lighthouse_check_kayaking_classes_desktop.PNG)

- Improvements note:
  - Perofrmance: Image format .jpg was indicated as outdated format with major impact to performance. Proposal to chose new generation of image format .webp. Converting and replacing the image files in repository and webpage increased performance from 66% to 93% for mobile devices.

  ### Test Conclution

- all 15 test cases is accepted (1 after code correction)
- webpage is fully responsive in all browsers except IE, however as IE is to be expired soon test is accepted
- after code error correction and image formate change automated tests are accepted

## Deployment

### Github deployment steps

1. Login into https://github.com/
2. Select Kayak_Classes -> https://github.com/EvergSwe/Kayak_Classes
3. Select Settings
4. Scroll down to Gibhub Pages and select the link to dedicated tab
5. Go to source drop down and select branch main, root and Save
6. Page is now successfully published on Github Pages
![Github pages published](/assests/img/Github_pages_deployment.PNG)

## Credits

### Content
Content and Idea was based on my own idea and intresst in this area.

### Media

- [Hero image](https://www.seakayakermag.com/best-kayak-paddles/) Landing page image
- [Kayaking image](https://www.nps.gov/apis/planyourvisit/proper-kayak-gear.htm) Kayaking section imave
- [Technique image](https://shop.laguuniin.fi/en_US/kayaking-courses-keilis/intermediate-kayaking-technique-course-3h-keilis) Technique section image
- [favicon](https://icon-library.com/icon/kayak-icon-4.html)
- [Fontawesome](https://fontawesome.com/) icons for social links
- [GoogleFonts](https://fonts.google.com/) has been explored and used

### Code

- General: Code institute - Coders Coffe house and Love Running project - Training material and video tutorials
- General: Considerations and thinking about design:https://twitter.com/ravikmmr/status/1502607452029992965?s=12
- HTML/CSS/Flexbox: Implementation and utilisation of Flexbox was assisted by CSS-Tricks and w3Schools
- Iframe: https://blog.duda.co/responsive-google-maps-for-your-website


