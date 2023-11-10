# Testing

Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FDavidFB94.github.io%2Fproject-1-grouptraining%2Findex.html) | ![screenshot](documentation/html-validation-home.png) | Section lacks header h2-h6 warning |
| About | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FDavidFB94.github.io%2Fproject-1-grouptraining%2Fabout.html) | ![screenshot](documentation/html-validation-about.png) | Pass: No Errors|
| Pictures| [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FDavidFB94.github.io%2Fproject-1-grouptraining%2Fpictures.html) | ![screenshot](documentation/html-validation-pictures.png) | Pass: No Errors |
| Sign-up | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FDavidFB94.github.io%2Fproject-1-grouptraining%2Fsign-up.html) | ![screenshot](documentation/html-validation-add-blog.png) | End tag with open element, unclosed element, stray div. Fixed.|

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2FDavidFB94.github.io%2Fproject-1-grouptraining) | ![screenshot](documentation/css-validation-style.png) | Pass: No Errors |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | About | Pictures | Sign-up | Notes |
| --- | --- | --- | --- | --- | --- |
| ![Chrome](https://raw.githubusercontent.com/TravelTimN/markdown-builder/main/assets/img/chrome.png) | ![screenshot](documentation/browser-chrome-home.png) | ![screenshot](documentation/browser-chrome-about.png) | ![screenshot](documentation/browser-chrome-contact.png) | ![screenshot](documentation/browser-chrome-etc.png) | Works as expected |
| ![Firefox](https://raw.githubusercontent.com/TravelTimN/markdown-builder/main/assets/img/firefox.png) | ![screenshot](documentation/browser-firefox-home.png) | ![screenshot](documentation/browser-firefox-about.png) | ![screenshot](documentation/browser-firefox-contact.png) | ![screenshot](documentation/browser-firefox-etc.png) | Works as expected |
| ![Edge](https://raw.githubusercontent.com/TravelTimN/markdown-builder/main/assets/img/edge.png) | ![screenshot](documentation/browser-edge-home.png) | ![screenshot](documentation/browser-edge-about.png) | ![screenshot](documentation/browser-chrome-edge.png) | ![screenshot](documentation/browser-edge-etc.png) | Works as expected |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | About | Contact | etc | Notes |
| --- | --- | --- | --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/responsive-mobile-home.png) | ![screenshot](documentation/responsive-mobile-about.png) | ![screenshot](documentation/responsive-mobile-contact.png) | ![screenshot](documentation/responsive-mobile-etc.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/responsive-tablet-home.png) | ![screenshot](documentation/responsive-tablet-about.png) | ![screenshot](documentation/responsive-tablet-contact.png) | ![screenshot](documentation/responsive-tablet-etc.png) | Works as expected |
| Desktop | ![screenshot](documentation/responsive-desktop-home.png) | ![screenshot](documentation/responsive-desktop-about.png) | ![screenshot](documentation/responsive-desktop-contact.png) | ![screenshot](documentation/responsive-desktop-etc.png) | Works as expected |
| Sony Xperia 10 | ![screenshot](documentation/responsive-xl-home.png) | ![screenshot](documentation/responsive-xl-about.png) | ![screenshot](documentation/responsive-xl-contact.png) | ![screenshot](documentation/responsive-xl-etc.png) | Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse-home-mobile.png) | ![screenshot](documentation/lighthouse-home-desktop.png) | Some minor warnings |
| About | ![screenshot](documentation/lighthouse-about-mobile.png) | ![screenshot](documentation/lighthouse-about-desktop.png) | Some minor warnings |
| Pictures| ![screenshot](documentation/lighthouse-gallery-mobile.png) | ![screenshot](documentation/lighthouse-gallery-desktop.png) | Slow response time due to large images |
| Sign-up| ![screenshot](documentation/lighthouse-gallery-mobile.png) | ![screenshot](documentation/lighthouse-gallery-desktop.png) |  |

## Bugs

- : `-----`

    ![screenshot](documentation/bug01.png)

  - To fix this, I _____________________.

## Unfixed Bugs

- On screens smaller than 260px, the text in the form no longer aligns correctly, and moves outside of the background box.

    ![screenshot](documentation/unfixed-bug01.png)

  - Attempted fix:

- On screens smaller than 170px, the content stops filling the screen width properly.

    ![screenshot](documentation/unfixed-bug02.png)

  - Attempted fix:
