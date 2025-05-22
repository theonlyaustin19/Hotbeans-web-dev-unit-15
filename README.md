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

