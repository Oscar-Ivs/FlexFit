# FlexFit Gym Website Project

## Project Overview
FlexFit Gym's website is designed to provide a comprehensive online presence for our modern gym, catering to fitness enthusiasts of all levels. The site offers detailed information on gym facilities, membership options, fitness programs, and booking capabilities. Built with Bootstrap, the website ensures a responsive and user-friendly experience across all devices, from desktops to mobile phones.

## Technologies Used
- **HTML5**
- **CSS3**
- **JavaScript**
- **Bootstrap 5**: Utilized for responsive design to ensure that the website is accessible and performs well on devices of all sizes.

## User Stories

### User Story 1: Intuitive Interface and Responsive Design (Must-Have)
**As a First-Time Visitor**, I need the website to have intuitive navigation and a user-friendly design that adapts to my device, enabling me to find information efficiently and enhance my user experience.
- **Acceptance Criteria**:
  - The website must be responsive on various devices and screen sizes.
  - Navigation is straightforward, allowing quick access to essential sections.
- **Tasks**:
  - Implement responsive web design principles using Bootstrap.
  - Organize navigation elements to ensure high visibility and accessibility.

### User Story 2: Engaging Visuals and Descriptive Content (Must-Have)
**As a Potential Member**, I want to view high-quality images and read compelling descriptions of the gym's facilities and programs, so I can be motivated to join.
- **Acceptance Criteria**:
  - High-resolution images of the gym's facilities and equipment are featured prominently.
  - Each program has a detailed description highlighting its benefits.
- **Tasks**:
  - Create a gallery or carousel of high-quality images using Bootstrap components.
  - Write and integrate engaging content that accurately describes the gym's offerings.

### User Story 3: Essential Information Accessibility (Must-Have)
**As a Prospective Member**, I need quick access to the gym’s location, contact details, and operating hours, so I can plan my visits easily.
- **Acceptance Criteria**:
  - Information regarding location, contact details, and hours of operation is easily accessible.
- **Tasks**:
  - Design and place a dedicated section for this essential information using Bootstrap's grid system.

### User Story 4: Seamless Booking System (Must-Have)
**As a Gym Enthusiast**, I want to easily book classes or personal training sessions through a simple online form.
- **Acceptance Criteria**:
  - An online booking form is readily accessible and simple to use.
- **Tasks**:
  - Develop an intuitive booking form that integrates seamlessly with the gym’s class schedule.

### User Story 5: Transparent Membership Pricing (Should-Have)
**As a Budget-Conscious User**, I want clear information on membership options and pricing.
- **Acceptance Criteria**:
  - Detailed pricing for various membership tiers is displayed prominently.
- **Tasks**:
  - Display membership pricing clearly on a dedicated page or section using Bootstrap's components.

### User Story 6: Social Proof through Testimonials (Could-Have)
**As a Prospective Gym Member**, I want to read testimonials from current members.
- **Acceptance Criteria**:
  - A testimonials section is included, featuring positive reviews.
- **Tasks**:
  - Design a testimonials page that integrates smoothly into the website’s layout using Bootstrap.

### User Story 7: Newsletter Subscription (Could-Have)
**As a Regular Member**, I want to subscribe to the gym’s newsletter.
- **Acceptance Criteria**:
  - A newsletter subscription form is easily accessible on every page.
- **Tasks**:
  - Integrate a sign-up form into the website's navbar using Bootstrap modal.

## wireframe

### Desktop Version index.html
![Desktop Wireframe](assets/images/wireframes/index-desktop-wireframe.png)
---

### Tablet & Mobile Version index.html
![Tablet Wireframe](assets/images/wireframes/index-tablet-mobile-wireframe.png)
---

### Desktop Version membership.html
![Desktop Wireframe](assets/images/wireframes/membership-desktop-wireframe.png)
---

### Tablet & Mobile Version membership.html
![Tablet Wireframe](assets/images/wireframes/membership-tablet-mobile-wireframe.png)
---
### Desktop Version timetable.html
![Desktop Wireframe](assets/images/wireframes/timetable-desktop-wireframe.png)
---

### Tablet & Mobile Version timetable.html
![Tablet Wireframe](assets/images/wireframes/timetable-tablet-mobile-wireframe.png)
---
### Desktop Version contact.html
![Desktop Wireframe](assets/images/wireframes/contact-desktop-wireframe.png)
---

### Tablet & Mobile Version contact.html
![Tablet Wireframe](assets/images/wireframes/contact-tablet-mobile-wireframe.png)
---

## Webpage Testing Strategy

### Objective
To ensure that the FlexFit Gym website offers a seamless and efficient user experience across all devices and platforms, I will use a comprehensive testing strategy. This strategy encompasses various tools and methods to test functionality, responsiveness, accessibility, and performance.

### Tools and Methods Used

#### 1. **Chrome DevTools**
- **Purpose:** To initially test the responsiveness and functionality of the website.
- **Process:**
  - Use the responsive design mode to simulate various screen sizes.
  - Test website features and user interactions to ensure functionality across different simulated devices.

#### 2. **Lighthouse**
- **Purpose:** To assess the performance, accessibility, best practices, and SEO of the website.
- **Process:**
  - Run Lighthouse audits from within Chrome DevTools.
  - Analyze the reports to identify areas for improvement in terms of performance, accessibility, SEO, and adherence to web best practices.
  - Implement recommended changes and iterate the audit process to improve scores.

#### 3. **W3C Validation**
- **Purpose:** To ensure the HTML and CSS code meets industry standards and is free from errors.
- **Process:**
  - Use the W3C HTML Validator (https://validator.w3.org/) to validate the HTML of the website.
  - Use the W3C CSS Validator (https://jigsaw.w3.org/css-validator/) to check the CSS.
  - Document any errors or warnings identified and address them to ensure the code adheres to web standards.
  - Re-validate post-fixes to confirm that all issues have been successfully resolved.

#### 4. **Cross-Device Physical Testing**
- **Purpose:** To confirm that the website operates effectively on actual devices, not just in simulated environments.
- **Process:**
  - Test the website on various physical devices including different smartphones, tablets, and desktops.
  - Use a range of browsers (e.g., Chrome, Firefox, Safari, Edge) to ensure compatibility and functionality.
  - Check for visual consistency and interactive elements across devices.

#### 5. **Cross-Browser Testing**
- **Purpose:** To ensure the website displays and functions correctly across various web browsers.
- **Process:**
  - Test on the latest versions of major browsers like Chrome, Firefox, Safari, and Edge.
  - Look for any CSS or JavaScript compatibility issues.
  - Verify that layouts appear as intended and that all functionalities work.

### Reporting and Fixes
- **Bug Reporting:** Any issues found during testing will be documented.
- **Resolution:** Documented bugs will be prioritized based on their impact and fixed accordingly. Regression testing will be conducted post-fix to ensure no new issues have been introduced.

### Continuous Testing
- **Ongoing Testing:** Webpage testing is an ongoing process throughout the development cycle to catch regressions and bugs as new features are added.

By employing this structured approach to testing, including validation through W3C tools, we aim to deliver a robust, high-performing, and user-friendly website that meets the needs and expectations of all FlexFit Gym patrons.

## IC Lighthouse testing results for each page

### Home page or Index.html has a great result:

![Index.html](/assets/images/Lighthouse/Index-html.png)

### Membership.html page:

![Membership.html](assets/images/Lighthouse/Membership-html.png)

### Timetables.html page has a excellent performance result:

![Timetables.html](assets/images/Lighthouse/Timetables-html.png)

### Contact-us.html page:

![Contact-us.html](assets/images/Lighthouse/Contact-us-html.png)

### Poor score in Best Practices is do to Google iframe:

![Poor Best practices](assets/images/Lighthouse/Best-practices.png)


### To achieve maximum performance and fast loading of the web page, I tried to reduce the data size of each page. Since the largest amount of data is taken up by images, all images were converted to *.webp file format, thus minimizing their size while maintaining their quality.

# Other bug fixes:

I encountered a problem where I was getting unwanted spacings on different screen sizes.
### Removed Bootstrap gutters.
I found out that by default horizontal gutters provided by Bootstrap created unnecessary spacing and disrupted the intended layout consistency, particularly on smaller screens. I found the way how to fix this by applying following CSS rule:
> --bs-gutter-x: 0; /* Removes horizontal gutter space created by Bootstrap */


the horizontal padding between columns was removed, resulting in a cleaner, tighter layout, optimized especially for mobile responsiveness.

### Div element or hero-image on small screens takes too much space:
I found out in Bootstrap documentation that there is an option to hide elements.
I used this one to hide her-image on small screens:
> div class="col-12 col-md-6 d-none d-md-block"

### Adjusted CSS for certain screen sizes:
While testing on different type and size devices doesn't cause any problems, however in chrome DevTools gradiently decreasing screen size I noticed in Timetables.html that all 4 sections doesn't respond as should leaving gaps at some certain screen size.
I added specified Multimedia queries to solve it:

/* Smaller screens */

>@media screen and (max-width: 370px)
{
    #section-2 ul {
        width: 100% !important;
    }
    #section-3 ul {
        width: 100% !important;
    }
}


/* Specific screen size */

  >@media screen and (min-width: 768px) and (max-width: 887px)

  /* Adjust section-2 and section-3 at specific screen size to fill the empty hero img gaps */
  
  #section-2, #section-3 {
        height: 100%;
    }
  

  >@media screen and (min-width: 1200px) {
.modal-content h5 {
font-size: 1.2rem;
}
  }


# Java Scripts by 3rd party
 **Java Script to automatically update the copyright year:**
```javascript
// JavaScript code example
```javascript
<script>
    document.addEventListener('DOMContentLoaded', function () {
        const year = new Date().getFullYear(); // Get current year
        const copyright = document.querySelector('.text-container p'); // Select the copyright paragraph using the correct class selector
        copyright.innerHTML = `&copy; ${year} FlexFit GYM. All rights reserved.`; // Set text dynamically
    });
</script>
```


 **JavaScript code to ensure the Bootstrap mobile navbar collapses when navigating to in-page links:**
// JavaScript code example
```javascript
<script>
    document
        .querySelectorAll(".navbar-collapse .nav-link")
        .forEach((link) => {
            link.addEventListener("click", function (e) {
                let section = document.querySelector(e.target.getAttribute("href"));
                if (section) {
                    e.preventDefault(); // Prevent default anchor click behavior
                    let navbarHeight = document.querySelector(".navbar-toggler").offsetHeight;
                    window.scroll({
                        top: section.offsetTop - navbarHeight, // Adjust for navbar height
                        behavior: "smooth",
                    });
                    document
                        .querySelector(".navbar-collapse")
                        .classList.remove("show"); // Collapse navbar
                }
            });
        });
</script>
```

**JavaScript code to display message when "Contact Us" form successful submitted:**
```javascript
<script>
                    document.getElementById('signup-form').addEventListener('submit', function (event) {
                        event.preventDefault(); // Prevent the default form submission

                        // Display the modal
                        var modal = document.getElementById("myModal");
                        var span = document.getElementsByClassName("close")[0]; // Get the element that closes the modal
                        modal.style.display = "block";

                        console.log("Modal displayed");

                        // Debugging: Check if span is correctly retrieved
                        if (span) {
                            span.onclick = function () {
                                modal.style.display = "none";
                                document.getElementById('signup-form').reset(); // Reset the form fields
                                console.log("Span clicked, modal closed, and form reset");
                            }
                        } else {
                            console.error("Close button not found");
                        }

                        // When the user clicks anywhere outside of the modal content, close it
                        window.onclick = function (event) {
                            if (event.target === modal) {
                                modal.style.display = "none";
                                document.getElementById('signup-form').reset(); // Reset the form fields
                                console.log("Clicked outside modal, modal closed, and form reset");
                            }
                        }
                    });
</script>
```
**JavaScript code to display message when "Subscribe" form is successful submitted:**
```javascript              
<script>
            document.addEventListener('DOMContentLoaded', function() {
                var subscribeForm = document.getElementById('subscribe-form');
                var subscriptionModal = new bootstrap.Modal(document.getElementById('subscriptionModal'));
                var thankYouModal = new bootstrap.Modal(document.getElementById('thankYouModal'));
            
                subscribeForm.addEventListener('submit', function(event) {
                    event.preventDefault(); // Prevent the default form submission
            
                    // Close the subscription modal first
                    subscriptionModal.hide();
            
                    // You might want to delay the opening of the thank you modal to ensure the transition is smooth
                    setTimeout(function() {
                        thankYouModal.show();
                    }, 500); // Delay of 500 milliseconds
            
                    // Reset the form fields (if necessary, can be done before or after showing the thank you modal)
                    subscribeForm.reset();
            
                    console.log("Subscription modal closed and thank you modal displayed.");
                });
            
                // Optional: Listen to the 'hidden.bs.modal' event to open the thank you modal right after the subscription modal completely closes
                $('#subscriptionModal').on('hidden.bs.modal', function () {
                    thankYouModal.show();
                });
            });
            </script>
```
# Deployment

The project has been deployed using GitHub Pages, providing a live and accessible URL for public access.

## Steps I done for Deployment:

### 1. Pushed my Code to GitHub

Ensured that project is fully functional and tested locally, then pushed my final code to main GitHub repository:

git add .
git commit -m "Finalized version before deployment"
git push origin main

### 2. Activated GitHub Pages

Navigate to my repository: https://github.com/Oscar-Ivs/FlexFit

Get to Settings → Pages.

Under the Branch section, selected my deployment branch (main) and set the directory to root.

Clicked Save to activate GitHub Pages.

### 3. Verified Deployment

GitHub Pages will automatically deployed my website.

My live website URL appeared in the Pages settings area.
https://oscar-ivs.github.io/FlexFit/index.html

Visit my URL to confirm the deployment.


## **Contact Information**
For more information, please contact us at [hk57agob@students.codeinstitute.net](hk57agob@students.codeinstitute.net).
