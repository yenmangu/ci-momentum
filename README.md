# Momentum

Momentum is a fitness-focused platform designed to support users at any stage of their fitness journey — whether you're just getting started or already committed to an active lifestyle. Our goal is to provide the tools, guidance, and motivation needed to help you stay consistent and make progress at your own pace. From personalized workout plans to expert tips, Momentum is built to keep you moving forward.

The website described here is a signup page for both types of user, to register interest to the main platform.

**Mockup here**

<!-- Mockup here -->

---

## User Experience

<!-- UX here -->

## UX

### UX Overview

This platform is meant to attract two types of users.

**Primary User** -
users of any age and background, who share a common goal of wanting to stay on track with their fitness goals.

**Secondary User** -
any existing fitness organisation/gym owner who currently doesn't but wishes to offer fitness or goal tracking services to existing customers.

There is clear navigation for both types of User, designed to clearly guide the user towards the appropriate section.

Users can directly contact Momentum if they wish to work with us as we are always looking for new talent to join our growing family.

### The 5 Planes of UX

#### 1. Strategy Plane
##### Purpose
- Advertise and introduce the App to new Users
- Provide a sign up service to new Users for the App
- Provide information to Users about the App and the services it provides.

##### Business Goals
- New Users signing up to the Momentum App
- Return business from User Subscription to the Momentum App

##### Primary User Needs
- Registration forms
- Details of the services the Momentum platform will provide
- Information on how to start getting into fitness
- Links to fitness articles (this could provide SEO opportunities with back linking)


#### 2. Scope Plane
##### Features
- A full list of [Features](#features-1) can be viewed in detail below.

##### Content Requirements
- Clear, motivational text about the Momentum platform's mission.
- Photos showcasing the platform
- Descriptions of platform features.
- Forms for User sign-up.

#### 3. Structure Plane
##### Information Architecture
- **Navigation Menu**:
  - Accessible links in the navbar.
- **Hierarchy**:
  - Clear call-to-action buttons.
  - Prominent placement of social media links in the footer.

##### User Flow
1. User lands on the home page → learns about the Momentum platform's mission.
2. Navigates to the fitness user page → learns about the Momentum plaform's features.
3. Signs up via the sign-up page.


#### 4. Skeleton Plane
##### Wireframe Suggestions
- A full list of [Wireframes](#wireframes) can be viewed in detail below.

#### 5. Surface Plane
##### Visual Design Elements
- **[Colours](#colour-scheme)**: see below
- **[Typography](#typography)**: see below

### Colour Scheme

I used [coolors.co](https://coolors.co/6a0dad-ff3b30-1e1e1e-f2f2f2-ff9500) to generate my color palette.

- `rgb(224,131,0)` / `#FF9500` Primary.
- `rgb(106, 13, 173)` / `#6A0DAD` Primary highlights & secondary text.
- `rgb(30,30,30)` / `#1E1E1E` Primary text.
- `rgb(235,235,235)` / `#F2F2f2` Background and tertiary.
- `rgb(255,59,48)` / `#FF3B30` Secondary highlights.

Other colours used
-`` / `#`

![screenshot](documentation/ux/colours/momentum-palette.png)

### Typography

- [Chakra Petch](https://fonts.google.com/specimen/Chakra+Petch) Was used for the logo typeface, and main header.
- [Montserrat](https://fonts.google.com/specimen/Montserrat) was used for the secondary headers and text body.
- [Font Awesome](https://fontawesome.com) icons were used throughout the site, such as the social media icons in the footer.

## User Stories

| Target    | Expectation                                                                                   | Outcome                                                                                 |
| --------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| As a user | I would like to know more about the platform                                                  | so that I can start my fitness journey                                                  |
| As a user | I would like information on a fitness tracking system                                         | so that I can monitor my fitness journey.                                               |
| As a user | I would like to see the details of a fitness platform features                                | so that I can choose my fitness app accordingly                                         |
| As a user | I would like to view a gallery of images from a fitness platform                              | so that I can see examples of the fitness platform will look.                           |
| As a user | I would like to sign up for a fitness platform                                                | so that I can use the app and enjoy its benefits.                                       |
| As a user | I would like to follow the platform on various platforms (e.g., Instagram, Facebook, Twitter) | so that I can stay updated with platform news and events.                               |
| As a user | I would like the website to be fully responsive                                               | so that I can easily navigate and access information from my phone, tablet, or desktop. |
| As a user | I would like to see a 404 error page if I get lost                                            | so that it's obvious that I've stumbled upon a page that doesn't exist.                 |

## Wireframes

To follow best practice, wireframes were developed for mobile, tablet, and desktop sizes.
I've used [Figma](https://www.figma.com/) to design my site wireframes.

| Page              | Mobile                                                               | Tablet                                                                  | Desktop                                                                  |
| ----------------- | -------------------------------------------------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| Home              | ![screenshot](documentation/ux/wireframes/ios-home.png)              | ![screenshot](documentation/ux/wireframes/tablet-home.png)              | ![screenshot](documentation/ux/wireframes/desktop-home.png)              |
| Features          | ![screenshot](documentation/ux/wireframes/ios-features.png)          | ![screenshot](documentation/ux/wireframes/tablet-features.png)          | ![screenshot](documentation/ux/wireframes/desktop-features.png)          |
| Registration      | ![screenshot](documentation/ux/wireframes/ios-registration.png)      | ![screenshot](documentation/ux/wireframes/tablet-registration.png)      | ![screenshot](documentation/ux/wireframes/desktop-registration.png)      |
| Registration Form | ![screenshot](documentation/ux/wireframes/ios-registration-form.png) | ![screenshot](documentation/ux/wireframes/tablet-registration-form.png) | ![screenshot](documentation/ux/wireframes/desktop-registration-form.png) |

## Features

| Feature            | Notes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Screenshot                                                                                                      |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| Navbar             | Featured on everypage, the fully responsive navbar includes links to the Home page, Momentum platform page and the Registration page. It is identical across all pages to alllow for easy navigation. On the smallest screen size the burger icon is used to toggle the navbar drawer so it doesnt take up too much space. This section will allow the user to navigate from page to page across all devices without having to revert back to the previous page via the 'back' button. The navbar is also `fixed`, so it stays in view even if the user scrolls. | ![Desktop](documentation/ux/features/navbar-desktop.png) ![Mobile](documentation/ux/features/navbar-mobile.png) |
| About Momentum     | This section of the home page will include an overview of the *Momentum* platform. It will have a clear CTA to guide the user to signing up                                                                                                                                                                                                                                                                                                                                                                                                                      | ![About](documentation/ux/features/about.png)                                                                   |
| 404                | The 404 error page will indicate when a user has somehow navigated to a page that doesnt exist. This replaces the default GitHub 404 page, and ties in with the look, feel and tone of the *Momentum* site, while also mainting uniformity by using the same navbar and footer                                                                                                                                                                                                                                                                                   | ![404 page](documentation/ux/features/404.png)                                                                  |
| Registration Form  | This page will allow the user to sign up to *Momentum* and start their running journey with the community. The user will be able specify if they would like to take part in road, trail, or both types of running. The user will be asked to submit their full name and email address.                                                                                                                                                                                                                                                                           | ![Registration form](documentation/ux/features/registration.png)                                                |
| Momentum features  | This page details the features of the momentum platform and how it will benefit the user. To be built and styled with Bootstrap grid, this page will present the information to the user without overwhelming them. The grid system will ensure full responsiveness.                                                                                                                                                                                                                                                                                             | ![Momentum features](documentation/ux/features/features.png)                                                    |
| Social Media Links | Situated in the footer, these will provide an instantly recognisable way to engage with the Momentum platform on various social medias.                                                                                                                                                                                                                                                                                                                                                                                                                          | ![Social Icons](documentation/ux/features/social-icons.png)                                                     |
| Success Page       | The success page will give the illusion that the signup form was submitted successfully to the *Momentum* platform. Due to the lack of a database or email system so far, this is a fake confirmation page and includes a *Home* link for the user to navigate home                                                                                                                                                                                                                                                                                              | ![Success Page](documentation/ux/features/success.png)                                                          |

### Future Features

<!-- Features to implement here -->
- **Gallery of Momentum platform images**: Showcase images of the Momentum platform in use.
- **Gym Owner Partnerships**: Add a feature that allows gym owners to partner with *Momentum* to provide an all in one service to customers
- **Fitness Tracking System**: Add a feature to have showcase the personalised fitness tracking system.

### **MoSCoW** Prioritisation

Using the **Must-Have**, **Should-Have**, **Could-Have** and **Won't-Have** prioritisation method, the user stories are prioritised in order to better manage the time and resources of the project effectively.

I've decomposed my Epics into User Stories for prioritizing and implementing them. Using this approach, I was able to apply "MoSCow" prioritization and labels to my User Stories within the Issues tab.

- **Must Have**: guaranteed to be delivered - required to Pass the project (*max ~60% of stories*)
- **Should Have**: adds significant value, but not vital (*~20% of stories*)
- **Could Have**: has small impact if left out (*the rest ~20% of stories*)
- **Won't Have**: not a priority for this iteration - future features

## Testing

> [!NOTE]
> For all testing, please refer to the [TESTING.md](TESTING.md) file.

## Tools & Technologies

| Tool / Tech                                                                                                             | Use                                                                         |
| ----------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| [![badge](https://img.shields.io/badge/Markdown_Builder-grey?logo=markdown&logoColor=000000)](https://markdown.2bn.dev) | Generate README and TESTING templates.                                      |
| [![badge](https://img.shields.io/badge/Git-grey?logo=git&logoColor=F05032)](https://git-scm.com)                        | Version control. (`git add`, `git commit`, `git push`)                      |
| [![badge](https://img.shields.io/badge/GitHub-grey?logo=github&logoColor=181717)](https://github.com)                   | Secure online code storage.                                                 |
| [![badge](https://img.shields.io/badge/VSCode-grey?logo=htmx&logoColor=007ACC)](https://code.visualstudio.com)          | Local IDE for development.                                                  |
| [![badge](https://img.shields.io/badge/HTML-grey?logo=html5&logoColor=E34F26)](https://en.wikipedia.org/wiki/HTML)      | Main site content and layout.                                               |
| [![badge](https://img.shields.io/badge/CSS-grey?logo=css3&logoColor=1572B6)](https://en.wikipedia.org/wiki/CSS)         | Design and layout.                                                          |
| [![badge](https://img.shields.io/badge/GitHub_Pages-grey?logo=githubpages&logoColor=222222)](https://pages.github.com)  | Hosting the deployed front-end site.                                        |
| [![badge](https://img.shields.io/badge/Bootstrap-grey?logo=bootstrap&logoColor=7952B3)](https://getbootstrap.com)       | Front-end CSS framework for modern responsiveness and pre-built components. |
| [![badge](https://img.shields.io/badge/Figma-grey?logo=figma&logoColor=F24E1E)](https://www.figma.com)                  | Creating wireframes.                                                        |
| [![badge](https://img.shields.io/badge/Font_Awesome-grey?logo=fontawesome&logoColor=528DD7)](https://fontawesome.com)   | Icons.                                                                      |

## Agile Development Process

### GitHub Projects

[GitHub Projects](https://www.github.com/yenmangu/ci-momentum/projects) served as an Agile tool for this project. Through it, User Stories, issues/bugs, and Milestone tasks were planned, then subsequently tracked on a regular basis using the Kanban project board.

![screenshot](documentation/agile/gh-projects.png)

### GitHub Pages

The site was deployed to GitHub Pages. The steps to deploy are as follows:

- In the [GitHub repository](https://www.github.com/yenmangu/ci-momentum), navigate to the "Settings" tab.
- In Settings, click on the "Pages" link from the menu on the left.
- From the "Build and deployment" section, click the drop-down called "Branch", and select the **main** branch, then click "Save".
- The page will be automatically refreshed with a detailed message display to indicate the successful deployment.
- Allow up to 5 minutes for the site to fully deploy.

The live link can be found on [GitHub Pages](https://yenmangu.github.io/ci-momentum).

### Local Development

This project can be cloned or forked in order to make a local copy on your own system.

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://www.github.com/yenmangu/ci-momentum).
2. Locate and click on the green "Code" button at the very top, above the commits and files.
3. Select whether you prefer to clone using "HTTPS", "SSH", or "GitHub CLI", and click the "copy" button to copy the URL to your clipboard.
4. Open "Git Bash" or "Terminal".
5. Change the current working directory to the location where you want the cloned directory.
6. In your IDE Terminal, type the following command to clone the repository:
	- `git clone https://www.github.com/yenmangu/ci-momentum.git`
7. Press "Enter" to create your local clone.


#### Forking

By forking the GitHub Repository, you make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original owner's repository. You can fork this repository by using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://www.github.com/yenmangu/ci-momentum).
2. At the top of the Repository, just below the "Settings" button on the menu, locate and click the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!

### Local VS Deployment

There are no remaining major differences between the local version when compared to the deployed version online.

## Credits

### Content

| Source                                                             | Notes                                                                   |
| ------------------------------------------------------------------ | ----------------------------------------------------------------------- |
| [MDN Web Docs_ ](https://developer.mozilla.org/en-US/docs/Web/CSS) | CSS Syntax & Reference Material                                         |
| [Markdown Builder](https://markdown.2bn.dev)                       | Help generating Markdown files                                          |
| [Chris Beams](https://chris.beams.io/posts/git-commit)             | "How to Write a Git Commit Message"                                     |
| [Rosie Resumé](https://codeinstitute.net)                          | Code Institute walkthrough project inspiration                          |
| [Bootstrap](https://getbootstrap.com)                              | Various components / responsive front-end framework                     |
| [ChatGPT](https://chatgpt.com)                                     | Help with asset generation, website copy and colour palette inspiration |

### Media

| Source                                                  | Notes                                                |
| ------------------------------------------------------- | ---------------------------------------------------- |
| [favicon.io](https://favicon.io)                        | Generating the favicon                               |
| [Rosie CV](https://codeinstitute.net)                   | Sample images provided from the walkthrough projects |
| [Font Awesome](https://fontawesome.com)                 | Icons used throughout the site                       |
| [DALL-E 3](https://openai.com/index/dall-e-3)           | AI generated artwork                                 |
| [CloudConvert](https://cloudconvert.com/webp-converter) | Converting images to `.webp`                         |

### Acknowledgements

- I would like to thank my Code Institute mentor, [Tim Nelson](https://www.github.com/TravelTimN) for the support throughout the development of this project.
- I would like to thank the [Code Institute](https://codeinstitute.net) Tutor Team for their assistance with troubleshooting and debugging some project issues.
- I would like to thank the [Code Institute Slack community](https://code-institute-room.slack.com) for the moral support; it kept me going during periods of self doubt and impostor syndrome.
- I would like to thank my partner, for believing in me, and allowing me to make this transition into software development.
- I would like to thank my employer, for supporting me in my career development change towards becoming a software developer.


