# Testing

### Automated testing
    
the Cookbook websites has bee tested using the following methods:
- [Code Validation](#code-validation)
    - [W3C HTML Validator](#w3c-html-validator) 
    - [W3C CSS Validator](#w3c-css-validator)
    - [JSHINT Javascript Code Quality Tool](#jshint-javascript-code-quality-tool)
- [Lighthouse](#lighthouse)
- [Responsiveness](#responsiveness)
- [A11y Color Contrast Accessibility Checker](#a11y-color-contrast-accessibility-checker)
- [Browser Compatibility](#browser-compatibility)
- [Testing User Stories](#testing-user-stories)
    - [Medical Memory Testing](#medical-memory-testing)
    - [Young Children in Schools](#young-children-in-schools)
- [Peer Review](#peer-review)
- [Bugs](#bugs)
    - [Unresolved](#unresolved)

# Code Validation

## W3C HTML Validator
The cook book website passed all tests using the [W3C HTML](https://validator.w3.org/nu/) Validator tool.

<h2 align="center"><image src="assets/ReadMe/Testing/w3chtmlval.png"></h2>

## W3C CSS Validator
The Memory Game Website passed all tests using the [W3C CSS](https://jigsaw.w3.org/css-validator/) Validator tool


<h2 align="center"><image src="assets/ReadMe/Testing/W3CCSSVAL.PNG"></h2>

# lighthouse

### Lighthouse Report for Game Page (Desktop)

<h2 align="center"><image src="assets/ReadMe/Testing/LighthouseTestDT.PNG"></h2>

### Lighthouse Report for Game Page (Mobile)

<h2 align="center"><image src="assets/ReadMe/Testing/LighthouseTestMB.PNG"></h2>

I used the Lighthouse reports in Google Developer Tools to examine the pages of the website for the following
- Performace
- Accessibility
- Best Practices 
- SEO

All Pages performed well (scored 95 and above) in:
- Performance, Accessibility, Best Practices and SEO on Desktop
- Accessibility, Best Practices and SEO on Mobile


# A11ly Colour Contrast Accessibility Checker 

The website page were tested using the A11y Color Contrast Accessibility Checker and no automated colour contrast issues were found.

<h2 align="center"><image src="assets/ReadMe/Testing/ColourContrastTest.PNG"></h2>

# Browser Compatabillity 

The site was tested in Google Chrome, Microsoft Edge and Mozilla Firefox on desktop.

The site was tested in Google Chrome and Safari on mobile and tablet.

No issues arose during browser testing. CSS transitions worked on all browsers tested. 

Appearance, functionality and responsiveness were largely consistent across browsers and devices.

# Responsiveness

Responsivity tests were carried out using Google Chrome DevTools. Device screen sizes covered include:
- iPhone SE
- iPhone XR
- iPhone 12 Pro
- Pixel 5
- Samsung Galaxy S8+
- Samsung Galaxy S20 Ultra
- iPad Mini
- iPad Air
- Surface Pro 7
- Surface Duo
- Galaxy Fold
- Samsung Galaxy A51/71
- Nest Hub
- Nest Hub Max

# testing User Stories 

## Medical Memory Testing
    - Using this website in the Field of medicine could be beneficial to not only students but patients.
        - Flash cards remain one of the most recommended ways to revise information for study as its quick and efficient making it the ideal for medical students with little time.
        - Along side this Flash card memory games such as this could be used to test for deseases that cause memory loss on a short term bases.
        - 

## Young Children in Schools
    - Using This website in Schools could help teachers and students alike.
        -Using emoji's as images for the cards could help the student retain focus 
        -Using this website could help tteachers guage how well the student's visual memory is developing
        - Using this website could also help bolster a sense of friendly competition within class rooms 

# Peer Reveiw
    
    - Getting a Family friend who works within the Field of creating web pages opened my eys to some flaws within the Game these are currently listed in the [Bugs](#Unresolved-bugs) Section.

# Bugs 

## Unresolved 

- Testing done by a family friend who works within the field of web design 
    - once a cards been picked, you shouldnt be able to re-select it. This becomes apparent where I can just keep getting the win message repeatedly once they're all matched and 'match' them again.
    - Adding to that, one the first card selected does the 'flip over' action again after clicking 'ok'
    
    - The second image flips over too quickly to really see what it is unless you've got it correct, I'd suggest even though its spotted that its wrong, leaving it for like a second so it can go 'okay thats what the two cards are' will help. Or at least making the transition slower."

