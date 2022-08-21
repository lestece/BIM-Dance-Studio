# BIM Dance Studio Testing

1) ## MANUAL TESTING

- ### Internal links

![Internal links testing](docs/TESTING-images/internal-links-testing.gif)

- All of the buttons that link to internal parts of the website (other pages of the same one or section of the same page/other pages) have been tested and work with no issues.

- All of the navigation bar links work and link to the right pages

- The back to top button correctly does its job

- The logo links to the homepage if clicked with no error

![Booking confirmation book another class link testing](docs/TESTING-images/booking-confirmation-book-another-link-testing.gif)

The link to the book-now.html in the booking confirmation page has been tested and works.

![Booking confirmation link to homepage testing](docs/TESTING-images/booking-confirmation-homepage-link-testing.gif)

Also the link to the homepage in the booking confirmation page works with no issues.

- ### External links

![Footer external links testing](docs/TESTING-images/footer-external-links.gif)

The only external links in the website are found in the footer, social media section. 
All of them have been coded and tested for opening in a new tab.

2) ## CODE VALIDATION

All HTML for BIM Dance Studio website passes through the [W3C HTML validator](https://validator.w3.org/) with no errors or warnings.

- ### Booking page

![Booking page reset button testing](docs/TESTING-images/reset-button-form-testing.gif)

The reset button in the booking page resets the form correctly.

![Booking page form validation and submission testing](docs/TESTING-images/booking-form-testing.gif)

- The booking form inputs are rightly validated

- The submit button in the booking form has been tested to make sure it links to the booking confirmation page.

- ### W3C HTML VALIDATION RESULTS

1) #### Index.html

![index.html validated](docs/TESTING-images/homepage-validated.png)

2) #### Instructors.html

![instructors.html validated](docs/TESTING-images/instructors-page-validated.png)

3) #### classes-and-prices.html

![classes-and-prices.html validated](docs/TESTING-images/classes-and-prices-validated.png)

4) #### book-now.html

![book-now.html validated](docs/TESTING-images/booking-page-validated.png)

5) #### booking-confirmation.html

![booking-confirmation.html validated](docs/TESTING-images/booking-confirmation-validated.png)

- ### W3C (Jigsaw) CSS VALIDATION RESULTS

All the CSS written for BIM Dance Studio passes through the [Jigsaw CSS validator](https://jigsaw.w3.org/css-validator/) with no errors.

![CSS validation](docs/TESTING-images/css-validation.png)


3) ## RESPONSIVENESS TESTING

4) ## BROWSER COMPATIBILITY 

5) ## BUGS & FIXES

- Error (1) in the validation process from all of the html pages

![html validation error 1](docs/TESTING-images/html-error-1.png)

An error was returned while trying out the html validation during the website coding. Quickly fixed by deleting that extra/unnecessary space.

- Error (2) in the validation process from all of the html pages

![html validation error 2](docs/TESTING-images/html-error-2.png)

The initial approach of enclosing the buttons inside of an anchor element to link to the appropriate pages/parts of the pages was detected as an error from the HTML validation service. It was fixed by changing approach and linking the buttons using the "onclick" Javascript function.

- index.html validator warning:

![index.html validator warning](docs/TESTING-images/homepage-validation-warning.png)

The second time the homepage was run through the validator, it returned a warning: this was easily fixed by switching the paragraph in the "meet the team" section with an h2 and giving this last one an ID to target it in the styles.css and contrast the bold font-weight style that was coming from the other h2's style.

- instructors.html validator warning:

![instructors.html validator warning](docs/TESTING-images/instructors-page-validation-warning.png)

The instructors page gave back a warning regarding the buttons section: easily and quickly fixed by replacing the section with a division block instead. 

- Back-to-top button bug

![Back-to-top button bug](docs/TESTING-images/back-to-top-bug.gif)

While testing the website I noticed that, even if the Javascript function was instructing the button to stop before the footer, as soon as the screen kept been scrolled down at the end of the footer and scrolled back up, the back-to-top button started going below the footer and "shaking" up and down as if the function for keeping it above the footer wasn't agreeing with the CSS for the button that is positioning it 80px from the bottom.
I've decided to fix it by removing the function and allow the button to go below the footer, since in small screen devices this last one is anyway a large section that would be improved by the button presence.

- Booking page: payment option checkboxes required

![book-now.html payment checkboxes](docs/TESTING-images/booking-page-payment-checkbox-bug.gif)

Testing the booking page, I realised that the form couldn't be submitted because of the first payment option being set as "required". Since the initial goal was to make the block of checkboxes related to payment a required field, and not a specific checkbox, I've deciced to remove the required attribute and ignore it for now, because it would have needed the use of jQuery to reach my initial aim. It would be implemented in the future when the booking page is a properly functioning one and works as explained in the [future features to implement](README.md/#features-to-implement-in-the-future) section of the README file.

6) ## LIGHTHOUSE

All of the pages have been tested with [Lighthouse Chrome Developer tool](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en): Performance, Accessibility and Best Practices all came back with scores __above 90__ from the reports.

- Homepage Lighthouse report:

![index.html lighthouse report](docs/TESTING-images/homepage-lighthouse-report.png)

- Instructors page Lighthouse report:

![instructors.html lighthouse report](docs/TESTING-images/instructors-lighthouse-report.png)

- Classes & Prices Lighthouse report:

![classes-and-prices.html lighthouse report](docs/TESTING-images/classes%26prices-lighthouse-report.png)

- Booking page Lighthouse report:

![book-now.html lighthouse report](docs/TESTING-images/booking-page-lighthouse-report.png)

- Booking confirmation page Lighthouse report:

![booking-confirmation lighthouse report](docs/TESTING-images/booking-confirmation-lighthouse-report.png)

7) ## USER TESTING
