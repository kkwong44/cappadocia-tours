# Cappadocia Tours <img src="assets/images/home-logo.png" alt="" width="35">

Cappadocia Tour is a company offer local guided tours in the Cappadocia region in Turkey.

## Objectives

    The Company would like to expand their business model by introducing an online reservation booking system to their business. The site will offer the available tours to the tourists in the region and allow them to make reservation.

    The target audients will be the tourists travelling to the Cappadocia region and wish to go on guided tours around the region.

    For the initial phase of this project, the tours are only available for the 2022 season, 3 are available and only 12 images in the gallery.

### Business Goals
* To make an online present
* Increase sales
* Streamline the reservation booking system

### User Goals
* Gain information about the region
* Check and reserve tours in the region

Click [here](https://kkwong44.github.io/cappadocia-tours/index.html) to access phase 1 project.

Multi Device Website Mockup Generator
>><img src="assets/images/readme/mockup.png" alt="Screenshot Home Page" width="1200">
>

## User Experience Design

### General
* All pages contain a logo "Cappadocia Tours", an image logo and a navigation menu at the top of the page
* The site will be directed to the home page when the user click on the logo or the image logo
* Navigation menu consist of links to the Home page, Gallery Page and Reservation Page
* User can navigate to these pages by clicking on these links
* All Pages conatin a footer. It has 3 section, Contact us with an email link, Copyright and links to Find us on Social Media
* When the email link is clicked. Local email client will be opened with an address to cappadocia tours
* Each social media link will be opened in a new window when its clicked

### Home Page
* A hero image of the Cappadocia region with cover text
* A button link to take the user to the tours section
* Offer tourists an information about Cappdocia region
* Provide information about the tours operate by the company
* Show the available tours and its itineraries
* To make reservation when click on the reserve button

### Gallery Page
* This page shows images from the region
* The images are display in a grid format
* Each image can be enlarge when hover on large screen devices

### Reservation Page
* The reservation form allows the user to make a reseravtion
* All input fields except message are requied to make reservation
* The input fields will be validated when the submit button is click
* A reset button is available to the user to reset the form with the default values

### Responsive and Accessibility
* The site is aim to all devices
* Accessibility has been incoporated into the design

## Features

### Header
All pages have the same header.

    * Company Name on the left as part of the logo
    * An image of the logo next to the company name
    * A navigation menu on the right with links to Home page, Gallery page and Reseravtion page
    * An underline will be appeared under the menu item when hover and disapper when hover away
    * Underline always show under the menu item to indicate the current page
#### Responsive
    * When the screen width is below 900px, navigation menu will move to the left under the company name
    * Also the font size on the navigation menu will be reduced

### Footer
All Pages have the same footer.
    * Contact details are on the left with an email link
    * Copyright in the center
    * Find us on social media on the right
    * The email link and the social medis icons will be darken when hover
    * Email client will be opened when clicked
    * A new window will be opened for each social media when clicked
#### Responsive
    * When the screen width is below 900px, the 3 sections will stack into a column

### Home Page
    * A hero Image
    * A cover text on the hero image
    * Call to Action button to the tours section
>
    * About Discover Cappadocia section
    * About Company tours section
>
    * Guided Tours section
    * 3 tours are available
    * An image and itineraries for each tour
    * Call to Action button on each tour to direct to reservation page

>><img src="assets/images/readme/screenshot-homepage.png" alt="Screenshot Home Page" width="400">
>
#### Responsive
    * When the screen width is below 1200px
        * Hero image - Container reduce height to 1/2
        * Hero cover text - Fontsize and size reduce
        * Hero CTA - Fontsize increase
>
    * When the screen width is below 900px
        * Use small hero image file
        * Tours section - Display in a single column
>
    * When the screen width is below 600px
        * Hero image - Container reduce height to 1/3
        * Hero cover text - Fontsize and size reduce further
        * Hero CTA - Fontsize increase further
        * Section titles - Fontsize reduce

### Gallery Page
    * 12 images in the gallery
    * Each image can be enlarge when hover over the image

>><img src="assets/images/readme/screenshot-gallerypage.png" alt="Screenshot Home Page" width="400">
>
>><img src="assets/images/readme/screenshot-gallerypage-hover.png" alt="Screenshot Home Page" width="400">
>
#### Responsive
    * The screen width will determine number of columns
    * When the screen width is below 600px
        * Image enlarge will be disabled

### Reservation Page
    * A reservation form can be filled and submmited to the company
    * All input fields except message are required
    * Each input field will be validated when submit button is clicked
    * Message will be display for missing or invalid data
    * All data can be reset to default values when Reset button is clicked
    * A message will be returned after the form is submitted

>><img src="assets/images/readme/screenshot-reservationpage.png" alt="Screenshot Home Page" width="400">
>
#### Responsive
    * When the screen width is below 520px
        * The width of the Reservation Form will reduce

## Future Features
### Home Page
    * The tour selected from the Call to Action button will automatically set as defalut in the reservation form
    * More tours will be added to this page but need to extend to other pages for performance issues
    * Information and tours need to be maintained and updated efficiently

### Gallery Page
    * More images can be added to this page
    * For performance issues, the gallery my need to extend to addtional pages
    * Images need to be maintained and updated efficiently

### Reservation Page
    * Date need to be beyond the current system date
    * Show available dates for each tour
    * Show available seats for each tour
    * Reservation fee is required and process credit card transaction
    * Confirmation email when reservation sucessfully processed
    * Payment and tour confirmation will be sent out after the the reservation has been carried out successfully

## Functional Testing
During the development phase, each feature was tested and ensured that the fundamental functions have achieved before going on to develop the next feature.

Once the site has been created, a full user acceptance testing was carried out to eliminate any bugs, errors or missing functionality. For example,
during the responsive tests, it was identified that the navigation menu was not functioning correctly for all pages. This was caused by the feature was developed on the home page but forgot to implement it to other pages. The tests then repeated until all issues are resolved.

This user acceptance testing was designed with all possible tests to simulate the user actions and the same tests are repeated on the live site to ensure all functionalties are working correctly.

There are 2 main test groups.
* Functional testing on each page
* Responsive testing on multiple devices

The following report shows the final tests result that have been carried out.

### User Acceptance Testing Report
<img src="assets/images/readme/test-report-page1.png" alt="Test Report Page 1" width="1200">
<img src="assets/images/readme/test-report-page2.png" alt="Test Report Page 2" width="1200">
<img src="assets/images/readme/test-report-page3.png" alt="Test Report Page 3" width="1200">
<img src="assets/images/readme/test-report-page4.png" alt="Test Report Page 4" width="1200">
<img src="assets/images/readme/test-report-page5.png" alt="Test Report Page 5" width="1200">
<img src="assets/images/readme/test-report-page6.png" alt="Test Report Page 6" width="1200">

## Validator Testing
Validator testing is used to validate codes that are legally written and to identify any possible errors. This can be done by using online automated testing tools to scan through the codes.
The tools used for this project are
* W3C Markup Validation Service to validate HTML - https://validator.w3.org/
* W3C CSS Validation Service to validate CSS - https://jigsaw.w3.org/css-validator/

The code can be copied and paste directly into the validator to perform the test. A report will be generated with the test results where it identified the errors. The validator will show passed when the code is free of error.

Although the site seems to be functioning correctly but during the initial validation test, it was identified that one of the ID name in the HTML was not unique and used in several places. This was rectified then repeat and passed the test.
# INSERT TEST RESULTS HERE

## Perfomance Testing
Lighthouse is a tool in Chrome Development Tools that allows developer to test their website. Performance is one of the tests carried out and it can identify where you can improve the performance.

The performance testing was carried out on the site and shows each page can be improved on the images that are used. There were several attempts to improve the performance by reducing dimensions, file sizes and file formats. The test cycle was repeated on each attempt and the final version was used the minimum dimensions on each image, converted into Webp from Jpg format and optimized the file size by using image optimiser tool.
# INSERT TEST RESULTS HERE