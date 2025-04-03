# Testing

> [!NOTE]
> Return back to the [README.md](README.md) file.

## Code Validation
### HTML


I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File                                                                                                     | URL                                                                                                                 | Screenshot                                                             |
| --------- | -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
|           | [404.html](https://github.com/yenmangu/ci-momentum/blob/main/404.html)                                   | [HTML Validator](https://validator.w3.org/nu/?doc=https://yenmangu.github.io/ci-momentum/404.html)                  | ![screenshot](documentation/validation/html--404.png)                  |
|           | [fitness-registration.html](https://github.com/yenmangu/ci-momentum/blob/main/fitness-registration.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://yenmangu.github.io/ci-momentum/fitness-registration.html) | ![screenshot](documentation/validation/html--fitness-registration.png) |
|           | [index.html](https://github.com/yenmangu/ci-momentum/blob/main/index.html)                               | [HTML Validator](https://validator.w3.org/nu/?doc=https://yenmangu.github.io/ci-momentum/index.html)                | ![screenshot](documentation/validation/html--index.png)                |
|           | [momentum.html](https://github.com/yenmangu/ci-momentum/blob/main/momentum.html)                         | [HTML Validator](https://validator.w3.org/nu/?doc=https://yenmangu.github.io/ci-momentum/momentum.html)             | ![screenshot](documentation/validation/html--momentum.png)             |
|           | [privacy.html](https://github.com/yenmangu/ci-momentum/blob/main/privacy.html)                           | [HTML Validator](https://validator.w3.org/nu/?doc=https://yenmangu.github.io/ci-momentum/privacy.html)              | ![screenshot](documentation/validation/html--privacy.png)              |
|           | [registration-success.html](https://github.com/yenmangu/ci-momentum/blob/main/registration-success.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://yenmangu.github.io/ci-momentum/registration-success.html) | ![screenshot](documentation/validation/html--registration-success.png) |


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File                                                                                | URL                                                                                                       | Screenshot                                                   |
| --------- | ----------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| assets    | [style.css](https://github.com/yenmangu/ci-momentum/blob/main/assets/css/style.css) | [CSS Validator](https://jigsaw.w3.org/css-validator/validator?uri=https://yenmangu.github.io/ci-momentum) | ![screenshot](documentation/validation/css-assets-style.png) |


## Responsiveness

I've tested my deployed project to check for responsiveness issues. I have also tested on my own device, as

| Page         | Mobile                                                              | Tablet                                                              | Desktop                                                              | iPhone                                                              | Notes             |
| ------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | -------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- |
| Home         | ![screenshot](documentation/responsiveness/mobile-home.png)         | ![screenshot](documentation/responsiveness/tablet-home.png)         | ![screenshot](documentation/responsiveness/desktop-home.png)         | ![screenshot](documentation/responsiveness/iphone-home.png)         | Works as expected |
| Momentum     | ![screenshot](documentation/responsiveness/mobile-momentum.png)     | ![screenshot](documentation/responsiveness/tablet-momentum.png)     | ![screenshot](documentation/responsiveness/desktop-momentum.png)     | ![screenshot](documentation/responsiveness/iphone-momentum.png)     | Works as expected |
| Registration | ![screenshot](documentation/responsiveness/mobile-registration.png) | ![screenshot](documentation/responsiveness/tablet-registration.png) | ![screenshot](documentation/responsiveness/desktop-registration.png) | ![screenshot](documentation/responsiveness/iphone-registration.png) | Works as expected |
| Success      | ![screenshot](documentation/responsiveness/mobile-success.png)      | ![screenshot](documentation/responsiveness/tablet-success.png)      | ![screenshot](documentation/responsiveness/desktop-success.png)      | ![screenshot](documentation/responsiveness/iphone-success.png)      | Works as expected |
| 404          | ![screenshot](documentation/responsiveness/mobile-404.png)          | ![screenshot](documentation/responsiveness/tablet-404.png)          | ![screenshot](documentation/responsiveness/desktop-404.png)          | ![screenshot](documentation/responsiveness/iphone-404.png)          | Works as expected |
| Privacy      | ![screenshot](documentation/responsiveness/mobile-privacy.png)      | ![screenshot](documentation/responsiveness/tablet-privacy.png)      | ![screenshot](documentation/responsiveness/desktop-privacy.png)      | ![screenshot](documentation/responsiveness/iphone-privacy.png)      | Works as expected |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Page         | Chrome                                                        | Opera                                                        | Safari                                                        | Notes             |
| ------------ | ------------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------- | ----------------- |
| Home         | ![screenshot](documentation/browsers/chrome-home.png)         | ![screenshot](documentation/browsers/opera-home.png)         | ![screenshot](documentation/browsers/safari-home.png)         | Works as expected |
| Mmomentum    | ![screenshot](documentation/browsers/chrome-momentum.png)     | ![screenshot](documentation/browsers/opera-momentum.png)     | ![screenshot](documentation/browsers/safari-momentum.png)     | Works as expected |
| Registration | ![screenshot](documentation/browsers/chrome-registration.png) | ![screenshot](documentation/browsers/opera-registration.png) | ![screenshot](documentation/browsers/safari-registration.png) | Works as expected |
| Success      | ![screenshot](documentation/browsers/chrome-success.png)      | ![screenshot](documentation/browsers/opera-success.png)      | ![screenshot](documentation/browsers/safari-success.png)      | Works as expected |
| 404          | ![screenshot](documentation/browsers/chrome-404.png)          | ![screenshot](documentation/browsers/opera-404.png)          | ![screenshot](documentation/browsers/safari-404.png)          | Works as expected |
| Privacy      | ![screenshot](documentation/browsers/chrome-privacy.png)      | ![screenshot](documentation/browsers/opera-privacy.png)      | ![screenshot](documentation/browsers/safari-privacy.png)      | Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues. Some warnings are outside of my control, and mobile results tend to be lower than desktop.

| Page         | Mobile                                                                  | Desktop                                                                  |
| ------------ | ----------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| Home         | ![screenshot](documentation/lighthouse/mobile-home.png)                 | ![screenshot](documentation/lighthouse/desktop-home.png)                 |
| Momentum     | ![screenshot](documentation/lighthouse/mobile-momentum.png)             | ![screenshot](documentation/lighthouse/desktop-momentum.png)             |
| Registration | ![screenshot](documentation/lighthouse/mobile-registration.png)         | ![screenshot](documentation/lighthouse/desktop-registration.png)         |
| Success      | ![screenshot](documentation/lighthouse/mobile-registration-success.png) | ![screenshot](documentation/lighthouse/desktop-registration-success.png) |
| 404          | ![screenshot](documentation/lighthouse/mobile-404.png)                  | ![screenshot](documentation/lighthouse/desktop-404.png)                  |
| Privacy      | ![screenshot](documentation/lighthouse/mobile-privacy.png)              | ![screenshot](documentation/lighthouse/desktop-privacy.png)              |

## Defensive Programming

Defensive programming was manually tested with the below user acceptance testing:

| Page/ Feature     | Expectation                                                                                              | Test                                                                                   | Result                                                                               | Screenshot                                                                                                   | Fix (if needed) |
| ----------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | --------------- |
| Navigation        | Expected to provide clear and accessible navigation links                                                | Verified that navigation links are clear and accessible                                | Navigation links appear and operate as expected                                      | ![screenshot](documentation/defensive/navigation.png)                                                        |                 |
|                   | Expected to be responsive across mutiple device sizes with mobile menu                                   | Test navigation menu across multiple screen sizes                                      | Navigation menu responsive as expected. Mobile menu shows at expected device widths. | ![screenshot](documentation/defensive/mobile-tablet-menu.png)                                                |                 |
| Home              | Expected to give user overview of the platform                                                           | Verified that page displays platform's mission and purpose in clear and concise manner | Mission and purpose displayed as expected                                            | ![screenshot](documentation/defensive/home.png)                                                              |                 |
|                   | Feature expected to be fully responsive                                                                  | Resized browser window and tested on multiple devices (mobile, tablet, desktop).       | Page was responsive across all tested screen sizes                                   | See [Responsiveness](#responsiveness)                                                                        |                 |
|                   | Expected to give user testimonials                                                                       | Verified user testimonials displayed in clear and readable manner.                     | Testimonials displayed as expected                                                   | ![screenshot](documentation/defensive/testimonials.png)                                                      |                 |
| Momentum          | Expected to showcase the features of the platform                                                        | Verified features of platform displayed in clear and concise manner                    | Features of platform displayed as expected                                           | ![screenshot](documentation/defensive/momentum.png)                                                          |                 |
| Registration      | Expected to have clear CTA for user registration                                                         | Verified CTA is clear and attractive                                                   | CTA is clear and attractive                                                          | ![screenshot](documentation/defensive/registration-cta.png)                                                  |                 |
| Registration Form | Expected to enforce valid input type for email field                                                     | Entered invalid data into email field                                                  | Error message displayed appropriately                                                | ![screenshot](documentation/defensive/invalid-data.png)                                                      |                 |
|                   | Expected to have enforce required fields, and prevent submission of empty form                           | Attempt to submit empty fields                                                         | Navigation links functional and accessible                                           | ![screenshot](documentation/defensive/empty-name.png),![screenshot](documentation/defensive/empty-email.png) |                 |
| Social Links      | Feature is expected to include working links to the club’s social platforms (Instagram, Facebook, etc.). | Clicked each social link to verify redirection to the correct platform page.           | All links redirected to the correct platform pages, opening in new browser tabs.     | ![screenshot](documentation/defensive/social-links.png)                                                      |                 |
| 404 Error Page    | Feature is expected to display a 404 error page for non-existent pages.                                  | Navigated to an invalid URL (e.g., `/test`) to test error handling.                    | A custom 404 error page was displayed as expected.                                   | ![screenshot](documentation/defensive/404.png)                                                               |                 |


## Implemented User Story Testing

| Target    | Expectation                                                                                   | Outcome                                                                                 | Screenshot                                             |
| --------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| As a user | I would like to know more about the platform                                                  | so that I can start my fitness journey                                                  | ![screenshot](documentation/features/about.png)        |
| As a user | I would like to see the details of a fitness platform features                                | so that I can choose my fitness app accordingly                                         | ![screenshot](documentation/features/features.png)     |
| As a user | I would like to sign up for a fitness platform                                                | so that I can use the app and enjoy its benefits.                                       | ![screenshot](documentation/features/registration.png) |
| As a user | I would like to follow the platform on various platforms (e.g., Instagram, Facebook, Twitter) | so that I can stay updated with platform news and events.                               | ![screenshot](documentation/features/social-icons.png) |
| As a user | I would like the website to be fully responsive                                               | so that I can easily navigate and access information from my phone, tablet, or desktop. | [See responsiveness](#responsiveness)                  |
| As a user | I would like to see a 404 error page if I get lost                                            | so that it's obvious that I've stumbled upon a page that doesn't exist.                 | ![screenshot](documentation/features/404.png)          |


## Bugs

### Fixed Bugs

[![GitHub issue custom search](https://img.shields.io/github/issues-search?query=repo%3Ayenmangu%2Fci-momentum%20label%3Abug&label=bugs)](https://www.github.com/yenmangu/ci-momentum/issues?q=is%3Aissue+is%3Aclosed+label%3Abug)

I've used [GitHub Issues](https://www.github.com/yenmangu/ci-momentum/issues) to track and manage bugs and issues during the development stages of my project.

All previously closed/fixed bugs can be tracked [here](https://www.github.com/yenmangu/ci-momentum/issues?q=is%3Aissue+is%3Aclosed+label%3Abug).

![screenshot](documentation/bugs/gh-issues-closed.png)

### Unfixed Bugs


[![GitHub issues](https://img.shields.io/github/issues/yenmangu/ci-momentum)](https://www.github.com/yenmangu/ci-momentum/issues)

Any remaining open issues can be tracked [here](https://www.github.com/yenmangu/ci-momentum/issues).

![screenshot](documentation/bugs/gh-issues-open.png)

### Known Issues


> [!IMPORTANT]
> There are no remaining bugs that I am aware of, though, even after thorough testing, I cannot rule out the possibility.

