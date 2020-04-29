# Mike Magee - Code Institute Milestone1

My imaginary client is a two person Drone company - "Aerial Shots" (AS) from Salem Ma.  AS was an early drone technology adopter, flying over 4,000 commercial flights since 2012.  AS established a great word-of-mouth reputation but is losing work to unscrupulous illegal operators trying to steal their business by using cheap unregistered drones and race-to-the-bottom rates.  

AS needs a website that will help set them apart from their new uncredentialed competitors and persuade them to weigh results, experience and reliabilty over price.

AS is strictly a B2B company. 

The business goals of the website:
- Establish brand awareness.
- Establish credibility, reliability and experience.
- Demonstrate quality work.
<br>
<br>
***
## UX
A typical B2B client will approach the site looking for in (decreasing order of importance) the following information:
- Quality visual work
- Referrals
- Experience
- Accreditations
- Safety and insurance record
- Technical details

Client Stories - Ultimately the client will want to:
- Navigate intuitively between various topic related page.  The goal is to move intuitively. 
- Easily locate and review the information described above.  The goal is to quickly obtain satisfaction that AS is credible, experienced, accredited, etc.   
- Browse galleries galleries and images.  The goal is to be sure that the content types, quality and variety will fit their requirements, 
- Submit a request for contact and get a free teaser document in the process.  The goal is to establish a relationship in a timely fashion and move their evaluation closer to enough satisfaction about conducting business.  

***
This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

![Wireframe1](projectrelated/wireframe1.png)

<br>
<br>

***
## Features
My mentor suggested a simple feature focusing on the Milestone submission deadline. 
*   <span style="color:green">GREEN</span> are features that I definitely want to include in the MS1 submission. 
*   <span style="color:orange">ORANGE</span> are stretch goals that I would like to include in the MS1 submission. 
*   <span style="color:INDIANRED">RED</span> are features that I will not include in the MS1 submission, but would like to record them for the future. 

### Page specific features

#### <span style="color:green">Homepage </span>
* <span style="color:green">(must)Jumbotron welcome section - Catch the visual attention of the user, demonstrate quality and provide intro and marketing text</span>
* <span style="color:green">(must)Section - OVERVIEW of credentials, certifications, experience </span>
* <span style="color:green">(must)Section - OVERVIEW of Safety and operational issues</span>
* <span style="color:orange">(stretch)Embedded video introduction - A 30 second video of Client attempting to establish initial trust   This will eventually move to About and be slightly more comprehensive  </span>
* <span style="color:orange">(stretch)Referrals - Scrollable list of a dozen or so </span>
* <span style="color:orange">(stretch)Make page scrollable up to reveal more content </span>

#### <span style="color:green">Gallery </span>
* <span style="color:green">(must)Hero Image</span>
* <span style="color:green">(must)Introductory text</span>
* <span style="color:green">(must)Mixed gallery of various shots/media</span>

#### <span style="color:green">Contact</span>
* <span style="color:green">(must)Hero Image</span>
* <span style="color:green">(must)Introductory text</span>
* <span style="color:green">(must)Basic 4 field information collection</span>
* <span style="color:green">(must)Checkbox to request promotional material</span>
* <span style="color:INDIANRED">(later)Calendar date selection</span>
* <span style="color:INDIANRED">(later)Map location selection</span>

#### <span style="color:INDIANRED">(later)About Page</span>  (Detailed credentials, certifications, experience, bio & photos ETC.. )
#### <span style="color:INDIANRED">(later)Classic Blog Page</span>
#### <span style="color:INDIANRED">(later)Commercial related Page</span> 
#### <span style="color:INDIANRED">(later)Pricing Page</span> 


### Global features
#### <span style="color:green">Header </span>
* <span style="color:green">(must)Horizontal menu links to any live pages </span>
* <span style="color:orange">(stretch)Mobile hamburger menu </span>

 #### <span style="color:green">Footer </span>
* <span style="color:green">(must)Social links </span>
* <span style="color:green">(must)Copyright</span>
 
<br>

***
## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.
- HTML Validation by freeformatter
    - https://www.freeformatter.com/html-validator.html
- CSS Validation by W3C
    - https://jigsaw.w3.org/css-validator/
- Development framework Visual Studio Code (mac) by Microsoft v1.44.1

******
## <span style="color:RED">Testing - TBD </span>

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

* <span style="color:orange">If this section grows too long, you may want to split it off into a separate file and link to it from here.</span>

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

- Pages location is:  https://michaelmagee.github.io/magee-MS1/

In addition, if it is not obvious, you should also describe how to run your code locally.

### Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: *Make Public*,

Another blue button should appear to click: *Open Browser*.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: *Make Public*,

Another blue button should appear to click: *Open Browser*.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the backend lessons.


## Credits
- Example MD content ideas reviewed from AJGreaves 
- Organizational and planning support from Mentor Brian M.  
- Fixed Sticky header and footer from getbootstrap doc 
- Attempted color inspiration from color.adobe.con

### Environment 
- Code Institute student template for Gitpod was used
- Locally, Visual Studio Code, periodically pushing to Githib/Gitpod

### Content
- All text and images are mine.

### Media
- Drone Fav Icon info from https://icons8.com/icon/pack/photo-video/small

*Any general project related support documents are in /projectrelated*


### Acknowledgements

- I received inspiration for this project from examples from Code Institute that I played with as I was learning.  
- I took several classes in parallel on Lynda to get different approaches