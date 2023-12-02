# Testing

Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdavidfb94.github.io%2Fgym-buddies%2Findex.html) | ![screenshot](documentation/validation/html-validation-index.png) | Section lacks header h2-h6 warning |
| About | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdavidfb94.github.io%2Fgym-buddies%2Fabout.html) | ![screenshot](documentation/validation/html-validation-about.png) | Pass: No Errors|
| Pictures| [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdavidfb94.github.io%2Fgym-buddies%2Fpictures.html) | ![screenshot](documentation/validation/html-validation-pictures.png) | Pass: No Errors |
| Sign-up | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdavidfb94.github.io%2Fgym-buddies%2Fsign-up.html) | ![screenshot](documentation/validation/html-validation-signup.png) | End tag with open element, unclosed element, stray div. Fixed.|
| Confirmation | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdavidfb94.github.io%2Fgym-buddies%2Fconfirmation.html%3Ff-name%3DTesting%26l-name%3DTesting%26email%3Dtesting%2540testing.com) | ![screenshot](documentation/validation/html-validation-confirmation.png) | Section lacks header h2-h6 warning |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdavidfb94.github.io%2Fgym-buddies%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv) | ![screenshot](documentation/validation/css-validator.png) | Pass: No Errors |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | About | Pictures | Sign-up | Confirmation | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Google Chrome | ![screenshot](documentation/browsers/chrome-home.png) | ![screenshot](documentation/browsers/chrome-about.png) | ![screenshot](documentation/browsers/chrome-pictures.png) | ![screenshot](documentation/browsers/chrome-signup.png) | ![screenshot](documentation/browsers/chrome-confirmation.png) | Works as expected |
| Firefox Developer Edition | ![screenshot](documentation/browsers/firefoxdev-home.png) | ![screenshot](documentation/browsers/firefoxdev-about.png) | ![screenshot](documentation/browsers/firefoxdev-pictures.png) | ![screenshot](documentation/browsers/firefoxdev-signup.png) | ![screenshot](documentation/browsers/firefoxdev-confirmation.png) | Works as expected |
| Microsoft Edge | ![screenshot](documentation/browsers/msedge-home.png) | ![screenshot](documentation/browsers/msedge-about.png) | ![screenshot](documentation/browsers/msedge-pictures.png) | ![screenshot](documentation/browsers/msedge-signup.png) | ![screenshot](documentation/browsers/msedge-confirmation.png) | Works as expected |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | About | Pictures | Sign-up | Confirmation | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/responsiveness/mobile-home.png) | ![screenshot](documentation/responsiveness/mobile-about.png) | ![screenshot](documentation/responsiveness/mobile-pictures.png) | ![screenshot](documentation/responsiveness/mobile-signup.png) | ![screenshot](documentation/responsiveness/mobile-confirmation.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/responsiveness/tablet-home.png) | ![screenshot](documentation/responsiveness/tablet-about.png) | ![screenshot](documentation/responsiveness/tablet-pictures.png) | ![screenshot](documentation/responsiveness/tablet-signup.png) | ![screenshot](documentation/responsiveness/tablet-confirmation.png) | Works as expected |
| Desktop | ![screenshot](documentation/browsers/chrome-home.png) | ![screenshot](documentation/browsers/chrome-about.png) | ![screenshot](documentation/browsers/chrome-pictures.png) | ![screenshot](documentation/browsers/chrome-signup.png) | ![screenshot](documentation/browsers/chrome-confirmation.png) | Works as expected |
| Sony Xperia 10 | ![screenshot](documentation/responsiveness/xperia-home.jpg) | ![screenshot](documentation/responsiveness/xperia-about.jpg) | ![screenshot](documentation/responsiveness/xperia-pictures.jpg) | ![screenshot](documentation/responsiveness/xperia-signup.jpg) | ![screenshot](documentation/responsiveness/xperia-confirmation.jpg) | Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse/lighthouse-mobile-home.png) | ![screenshot](documentation/lighthouse/lighthouse-desktop-home.png) | Some minor warnings |
| About | ![screenshot](documentation/lighthouse/lighthouse-mobile-about.png) | ![screenshot](documentation/lighthouse/lighthouse-desktop-about.png) | Some minor warnings |
| Pictures| ![screenshot](documentation/lighthouse/lighthouse-mobile-pictures.png) | ![screenshot](documentation/lighthouse/lighthouse-desktop-pictures.png) | Warning for image file sizes. Attempted fix: Image compression and format change. |
| Sign-up| ![screenshot](documentation/lighthouse/lighthouse-mobile-signup.png) | ![screenshot](documentation/lighthouse/lighthouse-desktop-signup.png) | Some minor warnings |
| Confirmation| ![screenshot](documentation/lighthouse/lighthouse-mobile-confirmation.png) | ![screenshot](documentation/lighthouse/lighthouse-desktop-confirmation.png) | Some minor warnings. Accessibility fixed. |

## Bugs

- : `Background and foreground colors do not have sufficient contrast ratio`

    ![screenshot](documentation/bug01.png)

  - To fix this, I modified the color slightly, and increased the font weight.

## Unfixed Bugs

- There are no remaining bugs that I am aware of.
  