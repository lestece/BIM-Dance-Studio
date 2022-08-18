# BIM Dance Studio Testing

1) ## MANUAL TESTING

2) ## CODE VALIDATION

All HTML for BIM Dance Studio website passes through the [W3C HTML validator](https://validator.w3.org/) with no errors or warnings.

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

