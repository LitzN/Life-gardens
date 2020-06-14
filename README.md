# **Life Gardens**  

My project is a website for a gardening company providing design, building and maintenance called Life Gardens. 
This website is for attracting and informing potential customers about the services the business provides. 
The website should also ensure customers feel the business is trustworthy, reliable and affordable as this is 
often an issue when choosing a building service.  

Project consists of four pages. The index page makes the user familiar with the brand and location of the business and 
contains navigation to the rest of the site. 'Services' is the first navigation link, on this page all information
about the services provided is outlined as well as the procedure. Also on this page is a section describing why potential 
customers should choose Life gardens, this section will link to the gallery page. The gallery page contains pictures 
of previous work and customer testemonials. Lastly, the contact page will contain a form where users can make an enquiry
about work they are looking to have done.


### **User stories and UX**

* **As a prospective customer, I want to know what the company can provide me and whether they are suitable for the work I need.**

* __As a prospective customer who has never used a design/building company before, I want information on how the process works.__  

* __As a customer looking to have work done, I want to see previous work from the company so I can judge the quality and decide whether to use their services.__  

* **As a returning customer deciding to engage with the company, I want to be able to initiate contact easily.**  


### **Wireframes**

Wireframes for this project were created on Balsamiq. [View wireframes](wireframes/wireframes.pdf)


## **Features** 

#### **Index page**
* Strong background of a garden will elicit positive feelings from customers and immediately gives the user an indication of what the business does.
* Navigation bar for this page is transparent to ensure all focus is on the image and heading, the links are bolder to ensure visibility.
* A large heading introduces the brand so it must stand out to the user, media queries were used to increase font size on larger screens for this purpose.
* A few lines of text with basic information on what the company does and where they operate. The dark translucent background ensures the text is readable whilst maintaining the style of the page.

#### **Services Page**
* The first section provides information about the four main services offered in more detail in the form of cards, which break up the information in an attractive way by including relevant images. Customers understand what’s offered.
* Section two, process, provides an explanation of what steps must be taken by the user to work with the company. 
* Section three, why choose us, concludes the page with the key benefits of using the company and invites users to view the gallery page through a text link.

#### **Gallery Page**

* Contains rows of images, customers can see examples of the work provided by the company. Reassurance is provided through the variety of projects in the images and by showing customers the quality they can expect.
* Row of testimonials, shows the company is trustworthy. Contains positive quotes from customers who’ve used different packages.

#### **Contact Page**
* Strong positive background image motivates customer to take final step and get in touch with the business
* Form for contact, allows users to get in touch with the company and provide the information necessary to start the process. 

### **Features left to implement**

* Add a message when form is filled correctly to tell user their form has been submitted.

## **Technologies Used**
* **HTML** was used to build all the pages for the site.
* **CSS** was used to style the html.
* [**Bootstrap**](https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css) was used to add responsive grid structure to the site.
* [**Fontawesome**](https://kit.fontawesome.com/c2af92f582.js) was used to add icons throughout the site.
* [**Google fonts**](https://fonts.googleapis.com/css2?family=Lobster&display=swap) was used for the main font style used throughout the site.
* **W3C Validator** was used to check HTML for errors.
* **Jigsaw validator** was used to check CSS for errors.

## **Testing** 

To test my code, first I put it through a validator, Jigsaw for CSS and W3C for HTML. No errors were found in any of the pages so it meets the standards set by W3C.
Sites used for validation: [Jigsaw](https://jigsaw.w3.org/css-validator/) , [W3C](https://validator.w3.org/)

### **Testing whether needs in user stories have been addressed**
* **As a prospective customer, I want to know what the company can provide me and whether they are suitable for the work I need.** <br>
    The services information section is created to address this, it informs clients of  the four areas of focus in the company “Design, Build, Plant and Maintenance” in a clear organised way. It is the first feature visible when the services page is visited.  

* __As a prospective customer who has never used a design/building company before, I want information on how the process works.__
    The process section in the services page provides this information and is found below the services information as it is likely the next concern for a prospective client. It clearly describes the steps which need to be taken to enlist the company’s services.  

* __As a customer looking to have work done, I want to see previous work from the company so I can judge the quality and decide whether to use their services.__  
    The Gallery page is created for this purpose, it provides images of previous work as well as testimonials to reassure new customers they will receive a quality service.
The Why choose us section on the Services page also contains a link to the gallery, so users who have finished learning about the company are invited to view the work.  

* **As a returning customer deciding to engage with the company, I want to be able to initiate contact easily.**  
    Contact is encouraged throughout the site through the alert under the navigation bar, which contains a link to the contact page and a message encouraging users to enquire.
The contact number is displayed on the footer, so can be found at the end of each page.
The Contact page includes a form to be filled out in order to start the process, there are fields for email, a few basic questions and a textbox for further information users wish to provide. Further details will be gathered by the company after this as too many questions on the form is likely to put off users.


### **Functionality and Responsiveness**
 
I tested functionality by loading each page and checking the features detailed below work as planned.
Google developer tools were used to view all pages on different viewports and assess responsive qualities.

### **Site wide feactures**
* **Functionality:**<br>
	* Navigation links: All links direct to the named page. The background and text of the links change color when the mouse hovers over them. The brand name on the left changes font color on hovering and directs to the index page. On smaller screens the toggle button is functional. 
	* Footer links: External links to social media accounts all open in a separate tab.
* **Responsive Design:** <br>
    * Navbar is collapsible on smaller screens, an icon leading to the links is used.


### **Index Page**
* **Functionality:**<br>
	* Navigation links: All links direct to the named page. Background of links changes to gray when the mouse hovers over them. On smaller screens the toggle button correctly displays navigation links.
* **Responsive Design:** <br>
	* On Laptop/Tablet: Font size of heading and welcome text is increased. Paragraph is positioned on the right as the key focus in the background is on the left. 
	* On Mobile devices: Background image is fixed in the top left allowing the main feature in the background image to remain on the screen. Text is smaller and centered for readability.


### **Services Page**
* **Functionality:**<br>
	* Alert link: is underlined on hovering and leads to the expected page.
	* Link in the why choose us section changes color when the mouse hovers over it and leads to the page expected.
* **Responsive Design:** <br>
	* On Laptop/Tablet: Cards in the services information section are displayed two in a row.
    * On Mobile devices: Cards in the services information section are stacked, only showing one card per row.

### **Gallery Page**
* **Functionality:**<br>
	* Alert link: is underlined on hovering and leads to the expected page.
* **Responsive Design:** <br>
    * On Laptop/Tablet: A row of three images, followed by a row of blockquotes and another row of images below.
    * On Mobile devices: Images are stacked so they are still clearly visible on smaller screens and dividing lines appear between blockquotes to break them up. 


### **Contact Page**
* **Functionality:**<br>
	* Form: Email input field expects a valid email and displays alert when @ is omitted. Submission is not allowed without input into email and text fields.
* **Responsive Design:** <br>
    * On Laptop/Tablet: Background image is clearly displayed with the contact form in the center of the screen.
    * On Mobile devices: Contact form takes up all of the screen, with the background only appearing in the transparent navigation bar. 
    This ensures the form is fully and clearly visible as it is the main purpose of the page.

## **Bugs**
### **Fixed**
* A horizontal scroll bar and white strip to appear on the side of the services page, adding the no gutters class 
consistently removed this
* Footer on services page was not taking up the full width of the page, removing the no gutters class from
the fixed footer fixed the problem.
### **Not yet fixed**
* On the smallest device in developer tools (mobile-320px), the cards on the services page are appearing at full width of the screen
whereas the rest of the page does not and is compressed.


## **Deployment**

The project was created on gitpod and pushed to the github repository 'Life-gardens' regularly. The 
master branch of this repository was then used as a source for publishing to Github Pages.

For deployed page, [click here](https://litzn.github.io/Life-gardens/).

## **Credits**
### **Content**
The text for section Y was copied from the Wikipedia article Z
Media
background-image-1 Photo by Creative Vix from Pexels
contact-image Image by <a href="https://pixabay.com/users/DreamyArt-512893/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=571940">Selling of my photos with StockAgencies is not permitted</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=571940">Pixabay</a>
Design-image Image by <a href="https://pixabay.com/users/27707-27707/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=969989">Kevin Phillips</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=969989">Pixabay</a>
Plant-image Image by <a href="https://pixabay.com/users/Larisa-K-1107275/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=19830">Larisa Koshkina</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=19830">Pixabay</a>
Build-image Image by <a href="https://pixabay.com/users/UweDigital-139992/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=260307">Uwe Jacobs</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=260307">Pixabay</a>
GALLERY IMAGES
1 Image by <a href="https://pixabay.com/users/zhugher-15594727/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=5085356">zhugher</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=5085356">Pixabay</a>
2 Image by <a href="https://pixabay.com/photos/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=691704">Free-Photos</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=691704">Pixabay</a>
3 Image by Image by <a href="https://pixabay.com/users/krakowgardendesign-8671385/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=3346929">Marzenna Gaines</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=3346929">Pixabay</a>
arch Image by <a href="https://pixabay.com/users/JillWellington-334088/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1543673">Jill Wellington</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1543673">Pixabay</a>
Patio Image by <a href="https://pixabay.com/users/StockSnap-894430/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2628075">StockSnap</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2628075">Pixabay</a>
Modern Image by <a href="https://pixabay.com/users/AndyG-144138/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=254716">Andy Giraud</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=254716">Pixabay</a>
The photos used in this site were obtained from ...
Acknowledgements
I received inspiration for this project from X