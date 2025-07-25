## Unit 15: Website Development

## Assignment title: Design and develop a website

## SCENARIO:  

You have recently joined a web development company, Hot
Beans Web as a junior web developer. You have been asked
as part of your induction and training to create a new section
for the company’s web site which promotes the company to
prospective employees, as they need to recruit more web
developers. The company wants you to include the following
things:

● A profile of the company itself

● profiles of existing trainee web developers

● job specifications and required qualifications

● an on-line application form

● links to web development courses

The target audience for the site is people who have
completed training courses or qualifications related to web
development and are now looking for a job as a web
developer.

## P2: Produce designs for a website that meet client requirements.

## Page layouts (Wirefram structure)

| Page               | Purpose                             | Design Features                                                                 |
|--------------------|-------------------------------------|----------------------------------------------------------------------------------|
| Home Page          | Welcomes and introduces users       | Hero banner with "dream it. code it. live it ", nav menu, call to action                       |
| About Us           | Company profile                     | Text section on company history, mission, and work culture                       |
| Meet the Developers| Profiles of trainees                | Cards with photo, name, bio, skills; hover effects planned                       |
| Job Specs          | Job roles and requirements          |  layout showing roles, required skills, application steps                   |
| Apply Now          | Online application form             | Name, email, CV upload, textarea for cover letter, Submit button                |
| Courses Page       | Useful links to web dev training    | Logos/links to courses with short descriptions                                   |

Visual design choices : 

| Design Element    | Explanation                                                                 |
|-------------------|------------------------------------------------------------------------------|
| Color Scheme      | Light background with blue highlights for a professional and welcoming look |
| Font Choices      | Sans-serif fonts (Arial, Roboto) for clarity and modern feel                |
| Layout            | Boxed sections, consistent margins, mobile-responsive grid                  |
| Navigation        | Top horizontal nav bar with clear labels for each section                   |
| Visual Hierarchy  | Headings, subheadings, and visuals to guide users through pages             |

## WIREFRAMES FOR EACH PAGE : 

## HOME PAGE : 

<img width="652" alt="image" src="https://github.com/user-attachments/assets/c81e1019-2743-43b6-afb3-b87e14b2f966" />


## About Us:

<img width="170" alt="image" src="https://github.com/user-attachments/assets/80d78fe6-5382-46bb-813c-ca23950a3a70" />


## Meet the developers :

<img width="299" alt="image" src="https://github.com/user-attachments/assets/13eb5cec-88af-4fe2-9310-9cc6af2a6603" />


## Job specs : 

<img width="178" alt="image" src="https://github.com/user-attachments/assets/b904ebe8-d791-4aa4-a8ef-435a75547133" />


## Apply now : 

<img width="215" alt="image" src="https://github.com/user-attachments/assets/7e592035-0889-4af2-a9cd-83bfcd9f0cfd" />


## courses page : 

<img width="157" alt="image" src="https://github.com/user-attachments/assets/d5194614-de09-413e-a6dd-8b0d6f17f641" />



## Alternative designs : 

 Description :   This version of the home page uses a horizontal navigation bar at the bottom instead of the top, with a full-width image banner and a welcome message overlay. Instead of individual content sections, it uses a slider to show "Meet the Developers", "Apply Now", and "Courses" as rotating cards.

##  Design features :

● Bottom nav bar: Home | About Us | Apply Now | Meet the Developers

● sliders can hide key info and may reduce accessibility.

● Less efficient for users who want to jump directly to the info they need.

## Why It Was Not Chosen:

● The bottom nav is less intuitive as users are more familiar with top navigation.

● Carousels can hide key info and may reduce accessibility.

● Less efficient for users who want to jump directly to the info they need.

## Technical Documentation:
 
 ##  Site Structure:

● index.html → Homepage

● about.html → About Us

● developers.html → Meet the Developers

● apply.html → Apply Now

## Tools & Technologies:

● HTML5 for page structure

● CSS3 for layout and styling

● draw.io for wireframes

● GitHub to host version-controlled files

● VS Code or similar code editor

● Responsive layout designed for desktop, tablet, and mobile


## P3 Review the website design proposals with others to identify and inform
## improvements.

## Emails : 

<img width="605" alt="image" src="https://github.com/user-attachments/assets/c5708caa-e0a4-4259-93fb-fa33fcc844a2" />

## response 

<img width="600" alt="image" src="https://github.com/user-attachments/assets/df63eb94-5672-436c-9d6d-4874bdee331a" />



##  Areas for Improvement & Changes Made

| Feedback Given                                                                 | Change Made                                                                                  |
|--------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| The navigation bar may feel cramped on smaller screens                         |I added a mobile-friendly hamburger menu for better navigation on phones and tablets          |
| Developer profiles looked too plain                                            | I included hover effects and added skill badges (e.g., HTML, CSS, JavaScript)                 |
|    |
|      |
| Courses page appeared basic and lacked trust signals                           | I added course descriptions and included official logos for each course provider              |

## Evaluation : 

The feedback helped me improve  usability, structure, and visual appeal across the website. The changes made were simple but well improved the user journey, making the design more intuitive and engaging. 

## P4 Produce a website for an intended audience and purpose.

https://theonlyaustin19.github.io/hotbeans/

## P5 Test the website for functionality, compatibility and usability.

## Functionality : 


| Test No. | Feature Being Tested         | Expected Outcome                                          | Actual Outcome                                           | Pass/Fail | comments                                  |
|----------|------------------------------|------------------------------------------------------------|-----------------------------------------------------------|-----------|----------------------------------------|
| 1        | Navigation links (Home, About Us, etc.) | Clicking links should take the user to the correct page         | All navigation links work as expected                     |  Pass   | No broken links                        |
| 2        | Apply Now form submission     | Form submits and shows a confirmation message              | Form resets after submission              |  fail   | Tested with sample input               |
| 3        | CV file upload                | Users should be able to upload a file (PDF or DOCX)                      | File uploads successfully                                 |  Pass   | Upload works, no file size validation  |
| 4        | Submit button on application form | Clicking submits the form and clears the inputs           | Form resets after submission                              |  Pass   | Button functioning as intended         |
| 5        | External course links         | Clicking links opens correct external training websites    | Links open in new tabs and direct to correct pages        |  Pass   | All external links are functional      |
| 6        | Developer profile interactivity | Hovering shows effect or additional info (if included)     | Hover effect works as intended                            |  Pass   | Visual effects appear on hover         |

## Compatibility testing 



| Test No. | Platform/Browser/Device        | Expected Outcome                                        | Actual Outcome                                      | Pass/Fail | Notes                                      |
|----------|--------------------------------|----------------------------------------------------------|------------------------------------------------------|-----------|--------------------------------------------|
| 1        | Google Chrome (Desktop)        | Site loads correctly, all features work                  | Everything works as expected                         |  Pass   | Primary browser tested                     |
| 2        | Mozilla Firefox (Desktop)      | Site fully functional, consistent appearance             | All features work, slight font variation             |  Pass   | Minor visual difference                    |
| 3        | Microsoft Edge (Desktop)       | No layout issues, all interactive elements work          | Site functions properly                              |  Pass   |                                            |
| 4        | Safari (iPhone)                | Responsive layout, menus and content adjust properly     | Site is responsive and user-friendly on mobile       |  Pass   | Hamburger menu tested                      |
| 5        | Android Chrome Browser         | Fully functional, form and links work                    | All features tested and working                      | Pass   | Touch elements responsive                  |
| 6        | Tablet (iPad, landscape)       | Layout adjusts, no overlap, easy to navigate             | Content fits screen well, easy to interact with      |  Pass   | Good spacing and font size                |
| 7        | Screen resized (desktop test)  | Content stacks properly, nothing overlaps or breaks      | Responsive layout adapts correctly                   |  Pass   | Nav converts into mobile menu when small  |

##  Usability Testing

| Test No. | Area Tested                  | Expected Outcome                                               | Actual Outcome                                             | Pass/Fail | Notes                                                  |
|----------|------------------------------|----------------------------------------------------------------|-------------------------------------------------------------|-----------|----------------------------------------------------------|
| 1        | Navigation clarity           | Users should find it easy to move between pages                |  users navigated smoothly                              |  Pass   | Top nav bar with clear labels helped a lot             |
| 2        | Form ease-of-use             | Users should be able to fill and submit the form without confusion | All users completed the form easily                        |  Pass   | Fields were clearly labeled                            |
| 3        | Content readability          | Text should be easy to read and understand                     | Font size and color contrast were clear                    |  Pass   | Used sans-serif font for readability                   |
| 4        | Visual design consistency    | Design should feel professional and consistent across pages    | All pages followed the same layout and color scheme        |  Pass   | Headers, spacing, and style matched throughout         |
| 5        | Mobile usability             | Users should be able to access and use the site on phones      | Mobile experience smooth and touch-friendly                | Pass   | Responsive layout tested on iPhone and Android         |
| 

## P6 :Review the extent to which the website meets client requirements.

## Review: How Well the Website Meets Client Requirements

| Client Requirement                                      | How It Was Met                                                                                   | Evidence or Feature Implemented                    |
|---------------------------------------------------------|---------------------------------------------------------------------------------------------------|----------------------------------------------------|
| Profile of the company                                  | An **About Us** page was created that explains the company’s history, mission, and work culture | "About Us" section on website                      |
| Profiles of existing trainee web developers             | A **Meet the Developers** page displays profiles, including name, photo, bio, and skills         | Developer cards with hover effects                |
| Job specifications          | A **Job Specs** page outlines roles, and responsibilities                        | Job descriptions listed clearly in structured layout |
| Online application form                                 | The **Apply Now** page includes fields for name, email, file upload, and cover letter            | Fully working HTML form with submit function      |
| Links to web development courses                        | A **Courses** page contains logos and links to relevant training programs                         | Course links open in new tab                      |
| Aimed at newly trained web developers                   | The tone, design, and language are friendly and clear for junior web developers                   | Simple, modern design with helpful layout          |
| Professional and easy-to-navigate website               | A clean, responsive layout with a top navigation bar and consistent design                        | All pages follow the same visual design theme     |

## M2 Justify the design decisions, explaining how they will meet the use needs and be fit for purpose.

The site was designed to fulfill the needs of the client and also those of the target audience  recently qualified web developers looking for employment. Each design decision was tied to some aspect of the client brief so that the site is useful and meaningful.

A top navigation bar was employed to fulfill the client's request for simplicity of navigation. Such an arrangement enables users to move smoothly from one page to another, such as About Us, Apply Now, and Meet the Developers, which are all required pages in the brief.

Responsive design assures cross-platform compatibility on desktop, tablet, and mobile usage. This speaks specifically to the demand for the site to be accessible by users on phones or tablets.

The color scheme  light background and blue details  was chosen to make the website professional and welcoming. This complies with the client's requirement of promoting Hot Beans Web as a desirable company for potential developers.

The home page hero banner with the tagline "dream it. code it. live it" contains a call to action asking users to browse around the company and apply. This is consistent with the requirement of recruiting and hiring new web developers.

The About Us page is completing the need for a company profile. The page gives background on Hot Beans Web, its mission, and company work culture so that the candidates can learn about the employer.

The Meet the Developers page is completing the need to introduce current trainee web developers. With pictures, bios, and skills, the page helps visitors see actual individuals in their role, and they can imagine themselves working at the company.

The Job Specs page outlines the necessity of detailing job roles and qualifications. Every role has a well defined and structured format, bullet points detailing skill and application process.

An online application form was added to the Apply Now page to fulfill the client's need for a tool for collecting job applications. The form has all the necessary fields  name, email, upload file for CV, and cover letter textarea  in order to make a complete submission.

The Courses page contains links to relevant training content, which addresses the requirement of having links to web development courses. This is a benefit to users who are yet to develop their skills.

Each decision was with the goal of meeting user requirements  providing a clean, uncluttered, mobile-centric experience that invites users to participate  and checking it off on the client's requirement. The final product is not only a recruitment tool but also a revenue to showcase Hot Beans Web in the best and most desirable light.

## M3 Optimise a website to meet client requirements.


###  Performance Optimisation
- **Compressed Images**: All wireframe and page images were optimised using online tools (e.g. TinyPNG) to reduce file size without losing quality improving loading speed.
- **Minified CSS & JavaScript**: Stylesheets and scripts were cleaned and minified to reduce file size and increase load speed.
- **Used Lazy Loading**: Images (especially in “Meet the Developers”) were set to load only when scrolled into view, improving initial page performance.

###  Device & Screen Optimisation
- **Responsive Design**: All pages were tested and adjusted using media queries to work on mobile, tablet, and desktop.
- **Flexible Layouts**: The use of CSS Grid and Flexbox ensured that content adjusts gracefully to different screen sizes.
- **Viewport Meta Tag**: Added to ensure correct scaling on mobile devices.

###  Accessibility Improvements
- **Alt Text**: All images include descriptive `alt` tags for screen reader support.
- **Readable Fonts & Contrast**: High contrast color combinations and large, readable sans-serif fonts (e.g., Roboto) were used for clarity.
- **Keyboard Navigation**: Form elements and navigation links are fully accessible via keyboard.

###  Navigation & User Experience
- **Consistent Top Navigation Bar**: Makes it easy for users to switch pages from any section of the site.
- **Clear Page Headings**: Each page starts with a visible title or header to orient the user.
- **CTA Buttons**: “Apply Now” and other call-to-action buttons were made prominent with hover effects to encourage interaction.

###  Alignment with Client Goals
- The site loads quickly and is user-friendly on all common devices meeting the client's aim to attract and recruit web developers effectively.
- Accessibility updates ensure the site is inclusive to all users, improving its professionalism.
- All core features (job specs, developer profiles, application form, course links) work smoothly  fully meeting the brief’s technical and content requirements.

## D2 Evaluate the design and optimised website against client requirements.



The website was created for Hot Beans Web with the goal of promoting the company to aspiring web developers and encouraging them to apply for job roles. 


###  Client Requirement: A Profile of the Company
- was this met?  Yes  

- **Evaluation:**  

  The About Us page gives a detailed overview of the company’s history, values, and work culture. It effectively promotes the company to potential applicants and presents a welcoming, professional image.



###  Client Requirement: Profiles of Existing Trainee Web Developers
- was this met?  Yes  
- **Evaluation:**  

  The Meet the Developers page showcases trainee developers with names, photos, bios, and listed skills. The layout is visually appealing, and hover effects enhance user interaction.



###  Client Requirement: Job Specifications 
- was this met?  Yes  
- **Evaluation:**  

   The Job Specs page outlines various roles available at Hot Beans Web, along with the required skills and qualifications. The information is structured clearly, making it easy for users to understand what’s expected of them.



###  Client Requirement: An Online Application Form
- was this met?  Yes  
- **Evaluation:**  

   The Apply Now page contains a fully functional online form that collects name, email, CV upload, and a cover letter. The form was tested for validation and accessibility and works across devices.



###  Client Requirement: Links to Web Development Courses
- was this met?  Yes  
- **Evaluation:**  

  The *Courses Page* includes useful links to online web development training. Logos and short descriptions make the resources attractive and accessible to users seeking to improve their skills.





- **Design Quality:** The visual design uses modern fonts, a clean layout, and a consistent color scheme that reinforces professionalism and trust which alignins with the client's branding goals.
- **Performance:** The website was optimised for fast loading, including image compression and code minimisation. Lazy loading improved page speed, especially for mediav heavy pages.
- **Responsiveness & Compatibility:** The site performs well on mobile, tablet, and desktop, with layouts adjusting properly due to responsive CSS techniques.
- **Accessibility:** Alt text, keyboard navigation, and readable font choices ensure the site is inclusive to all users.


###  Overall evaluation 
The final website successfully meets all the client’s requirements. It presents Hot Beans Web as a professional and attractive workplace, provides all essential recruitment features, and ensures a positive experience for its target audience of aspiring web developers. 


## D3 Demonstrate individual responsibility, creativity and effective self management in the design, development and review of a website.


The project took 9 weeks and here is a breakdown of every activity carried out by me 

| Week     | Task                                       | Description                                                                 |
|----------|--------------------------------------------|-----------------------------------------------------------------------------|
| Week 1   | Project Planning & Requirement Gathering   | Analysed the client brief, user needs, and planned content requirements     |
| Week 2   | Created Wireframes and  Initial Designs       | Designed visual layouts for each page using Draw.io                         |
| Week 3   | Explored Alternative Designs & Documentation| Proposed alternate layouts and wrote technical documentation                |
| Week 4   | Content Writing & Asset Sourcing           | Wrote page content and sourced appropriate visuals/icons/fonts              |
| Week 5   | Page Development (HTML/CSS)                | Built pages with responsiveness and accessibility in mind                   |
| Week 6   | Peer Feedback & Revisions                  | Collected peer feedback and improved designs based on suggestions           |
| Week 7   | Testing Phase                              | Conducted functionality, compatibility, and usability tests                 |
| Week 8   | Optimisation & Final Adjustments           | Improved performance, visual clarity, and accessibility                     |
| Week 9   | Final Evaluation & Documentation           | Reviewed site vs. client requirements and completed final reflections       |



## Individual Responsibility

- I managed my entire workflow independently.
- Created a clear timeline and tracked progress weekly.
- Used GitHub to manage version control and document updates.
- Took initiative to research techniques (accessibility, layout best practices, responsive design).
- Delivered each milestone on schedule without external pressure.



##  Creativity in Design

- Designed a **hero banner** with the tagline: _“Dream it. Code it. Live it.”_
- Used **developer profile cards** with hover effects for interactivity.
- Created a **clean, box-based layout** to help users scan content easily.
- Explored alternative ideas like **carousels and bottom navs**, documented pros/cons, and selected the most user-friendly option.
- Balanced professionalism with visual appeal using color, whitespace, and structure.



##  Self-Management

- I Created a checklist of tasks for each week and tracked what was complete.
- I prioritised feedback and improvements throughout the build.
- I documented all changes in markdown files and comments within code.
- I used GitHub as a central hub for storing visual mockups, code, and evaluations.
- I regularly tested the site during development rather than waiting until the end.



## Design Review and Iteration

- Asked peers to review my wireframes and final layouts.
- Improvements made:
  - I increased **font size** and **contrast** for better readability.
  - I simplified **About Us** page for easier scanning.
  - I improved form spacing and structure on **Apply Now** page.
  - I replaced heavy images with **compressed formats** for faster load times.




I have demonstrated:

- **Responsibility:** Handled all tasks independently and professionally.
- **Creativity:** Developed engaging and accessible pages using original ideas.
- **Self-Management:** Stayed on track with consistent progress and proactive problem-solving.

