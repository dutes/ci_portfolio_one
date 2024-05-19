## Chef-O-Mat

Ever found yourself staring at a random assortment of ingredients and a few pantry staples, wondering, "What can I make with these?" Then this website is here to answer that question for you. 
Whether you are a practiced home cook or someone who couldn't boil an egg - this site has your back. Simply input five of your ingredients and any particular cuisine style, and the Chef-O-Mat will give you some simple, delicious, and creative meal recipes.
Turn the last meal time before the week's grocery shop into a fun culinary playground!

![Chef-O-Mat](assets/images/chef0mat.webp)

## Wire Frame

Here is the wirefame which formed the foundation of the website's design. It specifies the desired layout and helped to guide understanding of the CSS styling.

![Wire Frame](assets/readme_images/wire_frame.png)


## Features (Delivered as part of Project 1)
**LO1: Design an interactive Front-End web application using HTML and CSS based on the principles of user experience design, accessibility and responsivity.

I designed and built a multi-page, responsive and mobile first website using HTML and CSS. The design is derived from research as well as my own preferences for the UX of a site. Accessibility was considered from the begining of the project and largely meets ARIA requirements. The site is also fully responsive adapting on the fly to resolutions from 250px to at least 3440px ensuring a consistent user experience.

![Responsive Mockup](assets/readme_images/amiresponsive.png)

**LO2: Test a front-end web application through the development, implementation and deployment stages.

Throughout the development process, I have maintained a rigourous design, build, test, itterate cycle ensuring both smooth functionality as well as a pleasing, consistent user experience across a wide array of browsers, operating systems and device types. 

**LO3: Deploy a Front-End web application to a Cloud platform

The Chef-O-Mat site has successfully been deployed to the web via GitHub Pages. The deployment not only assures the site is reachable on the general web, but it was also key to being able to test the design and eliminate bugs. The deployed site was continously updated from the commits on the main project's GitHub repository.

**LO04: Maximise future maintainability through documentation, code structure and organisation.

Maintainability was built in from the intial project stages with clear naming conventions, modularised CSS and code practices. The Readme document provides detail on the project from setup and installation to current status, testing performed and future development goals.

**LO5: Demonstrate and document the development process through a version control system such as GitHub.

The entire development of the project has been managed using GitHub as its version control and development environment. Changes have been commited regularly with clear commit messaging allowing a full over view of the progress and milestones of the project's process from concept to submission. 


## Features (envisioned)

The envisioned features of this project aim to transform the basic, static site  into a dynamic and interactive web application. The primary functionality will be an ingredient input form where users can enter up to five ingredients and select a preferred cuisine style. These inputs will be sent via an API to Chat-GPT, which will generate five recipes based on the user's input. The generated recipes will be returned and displayed in a uniformly styled card format that includes the recipe name, an image, the ingredients list, and preparation instructions. Additional future functionality will enable users to create accounts, save their preferred recipes, and share them on social media. These enhancements will significantly improve user engagement and provide a richer, more immersive user experience.

## Site Map
Here is a visual site map of the Chef-O-Mat site:

![Site Map](assets/readme_images/site_map.webp)

**Main Page
This is the initial landing page for users arriving at the site. The page is designed to give the user a welcoming sensation with a prominent Chef-O-Mat hero image and a simple layout. The text is short and punchy, drawing the user's eyes to it. The navigation element in the header catches the eye and entices the user to click the text links.

**Web App page
This is the second page in the navigation element. It is the heart of the website as it will contain the key functionality for the site. The form is written in standard HTML and is currently not validating input since the underlying functionality is not yet present. Clicking submit on this form, even while empty, will bring the user to a non-navigation linked page called 'Not There'.

**Email
This page is displayed to the user in lieu of the Chat-GPT generated recipes. The Chef-O-Mat hero image is replaced with a sad version to indicate sadness at not being able to carry out its duties. The user is instead offered the chance to enter their email address to be notified when the Chef-O-Mat is ready to use. Email address entry is validated on this form. This page will be removed from the site once the web app is functional, as the user's email address will be captured at the account creation stage.


**Thanks
On the Thanks page, Chef-O-Mat indicates its pleasure that the user has entered an email address. This is a positive feedback instance for the user, as the cute robot shows genuine happiness at being entrusted with the user's address. This page will also be removed once the web app functionality is included, with the happy asset reused at the end of a successful account creation process.

**Seasonal 
The Seasonal page currently contains some sample recipes showcasing the index card style the generated recipes will follow. This page will evolve into a page displaying the most shared recipes generated in the past period of time. There is potential for sponsored content to be included in the sample recipes listed here in the future.
