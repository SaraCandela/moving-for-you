# Moving for you 

Welcome to [Moving for you](https://saracandela.github.io/moving-for-you/).

Moving for you is a website for individuals or companies that want to have a professional and comfortable experience moving their goods national or international. For individuals both big and small projects and, in the case of companies, also within the same building or expansions. 

Users of this website will be able to find all about the company and their experience throughout the years, the services they offer and clear information of how to contact via message, social media or phone. 

![Responsive design](/assets/images/responsive-design.jpg)

## Features

* Navigation
    * Featured at the top of the page, the navigation shows the name of the company in the left corner: Moving for you that links to the top of the page.  
    * The other navigation links are to the right: About us, Services and Contact which include a form to send direct messages for more information and links to social media as well as phone number. 
    * The navigation colors as well as the name of the company are orange as that is the color to represent the company, as well as a light beige background that feed good with the orange. This color will be showing throughout the page.
    * The navigation is clear for the user with the name of the company and the section they can find in the site.  

    ![Navigation](/assets/images/moving-for-you-navigation.jpg)


* The Header
   * The header shows a background image with a worker for the moving company, adding also a side text that briefly explains the intentions of the website.
   * Using the same orange colors as the navigation menu and a contrast of white letters that fits good with the background image. 
   * These features introduce the user to the experience and history of the company. 

    ![Header](/assets/images/header.jpg)

* The About Us Section
   * The About us section give a further detail about what the history of the company and what it offers in a brief paragraph.
   * This section also include some icons with more visual representation of what the company can provide as well as other features such as experience and rating. 
   * These icons become a bit bigger as the user hovers with the mouse to give a bit of interaction to the section. 

    ![About us](/assets/images/about-us.jpg)

* The Services Section
   * This section specifies all three moving services available with a paragraph on each one of them explaining more in detail how the company works with each service. 
   * We continue seeing the orange background and white letters that combine perfectly with the header colors. 

   ![Services](/assets/images/services.jpg)

* Contact Us Section
   * Contact Us section includes a form the user can send direct messages to the company, this includes: Name, email and message area. 
   * Below the form, in the footer, it is placed all the social media links and a phone number. 

   ![Contact us](/assets/images/contact-us.jpg)

   * When the send button is press, it redirects to a page that confirm the message has been sent and a button sending back to home page.

   ![NextPage](/assets/images/nextpage.jpg) 

 ## Technologies used

 ### Two main languages:

 * HTML5
 * CSS3

 ## Testing

* I tested that this page works in different browsers: Chrome, Firefox, Explorer and Safari. 
* I confirmed that this project is responsive, looks good and functions on all standard screen sizes using the DevTools device toolbar. 
* I confirmed that the navigation, header, about us, services and contact us text are all readable and easy to understand. 
* I confirmed that the form works: requires entries in every field, will only accept an email in the email field, and the submit button works. 

### Bugs
* When I was trying to start the second section of my project, I realized that one of the pictures used in the About us section was creating a big border that didn't allow me to center the next section of the content. 
    * This was fixed by changing the border size on CSS. However, I decided to remove completely that image by the mid project.

* The website in the computer screen has this underline in the menu bar that when is hover with the mouse shows it, and after pressing it redirects to the section and the underline disappear. With smaller screens, the line didn't show when hover but when press the menu sections, and it didn't disappear until press other section. 
    * I used the following code to delete completely that line from smaller screen in the media queries.
       
        #menu a:hover {
        border-bottom: none;
    }
 

### Validator Testing 

* HTML
    * No errors were returned when passing through the official W3C validator. 
* CSS
    * No errors were found when passing through the official (Jigsaw) validator. 
* Accessibility 
   * I confirmed that the colors and fonts chosen are easy to read and accessible by running through lighthouse in DevTools. 

   
   ![Accessibility](/assets/images/accessibility.jpg) 

    ![Legend](/assets/images/legend.jpg) 


### Unfixed Bugs

* The icons in phone screens grows when pressing them in contrast with computer screen which grows when hover, ideally this effect should not take place in phone devices.
    
## Deployment 

* The site was deployed to GitHub pages. The steps to deploy are as follows:
    * In the GitHub repository, navigate to the Settings tab.
    * From the Code and automation section, select pages.
    * From the drop-down menu, select Main Branch.
    * Once the main branch has been selected, the page provided the link to the completed website. 

The live link can be found here - [Moving for you](https://saracandela.github.io/moving-for-you/)

## Credits

This is the first porfolio project from Code Institute. The website is inspired by Love Running Project studied and done earlier in this course. 
Code institute Slack community was checked to see common bugs with fellow peers. 

  * Code institute mentor Adegbenga Adeye was consulted especially for image issues and responsive styles. He was a big support through advice and suggestions. 
  * Google is the primary spot consulted for alternative coding and general inspiration. 
  * Other existing moving companies websites were looked at for inspiration with colors and ideas. 

### Content 

 * Use [Balsamiq-wireframes](https://balsamiq.com/wireframes) for the idea and planing of my project. 
 * The code from sizing the sections used for About us section and contact was taken from [W3shools](https://w3schools.com)
 * Check on google to conect how to conect the 404 page to my website. 

### Media

* The image in the header was taken from [Istock](https://www.istockphoto.com/)
* The icons in both "About us" and footer section was taken from [Font Awesome](https://fontawesome.com/icons)

