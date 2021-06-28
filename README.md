# Jobverz

## Description

Jobverz is an online platform where the user can find the relevant skills to get recruited into his dream job within the time span. It also maps the user skill proficiency with demand. If the user is unclear about the path, then he can explore the trending job titles based on his skill set. The user authentication is carried out with the help of AWS amplify and Cognito. The user details are stored in AWS S3 with the help of Amplify.


## Sprint 1

### Create a react component for reset password page

* Understanding Design Language Systems.
* Creating the reset password page in React JS. Also held a discussion with team to design the UI of the reset password page.
* Validating the email using regex.
* Making the user interface better by prompting an alert when user enters incorrect email. This is interconnected with email validation regex
* Redesigning Landing page where users, government, and company has a seperate card allocated for them. Helping out in designing the UI of the Landing page.
* Integrating of Sign up, Sign in, landing page, Reset password was also done by me.

## Sprint 2

### Adding AWS authentication to the website

* Integrating all the individual CSS files into main CSS file to maintain consistancy
* Understanding AWS authentication and also going through predefined methods in AWS Amplify
* Creating AWS account and understanding AWS forget password code. Faced some minor issues during installation of AWS Amplify
* Successfully added AWS forget password to the Reset password page. The user now receives a code to reset his password in his email
* Creating a new page called Forget password. The user enters the code that is sent to his mail, along with his loging credentials to reset his password

## Sprint 3

### Extract skills, word experience and education qualification from the resume in pdf/doc format

* Get details from LinkedIn. Created a Developer app and got the access token. Successfully extract details such as First name, Last nane and photo
* Working on node libraries to convert the information in the pdf file into text format that can be proccessed. Found two libraries namely pdf parser and word parser
* Working with pdf reader where it directly converts the data in text file that is uploaded in the website. Pdf reader gave binary output for pdf and word files instead of text 
* Working with file reader. The information in the pdf file is being displayed in text format. File reader only works for pdf, yet to find libraries for word document

## Sprint 4

### Upload the resume in AWS S3

* Creating a bucket in AWS S3. Uploading resume to the AWS S3 bucket. Faced some minor issues with permissions that denied updating/writing objectes in the buckets
* Finished uploading any format resume/CV into the AWS S3 bucket
* Redesigning the UI of the Jobverz website in the Adobe XD. The goal is to change the website into red theme 
* According to client requirements we changed the website again into blue theme. Added background images and completely changed the UI design of the Sign in and Sign up pages

## Sprint 5

### Research on Digital credentials/ Interoperable learner records

* Researched on a form of Digital credentials i.e Digital badges. Found some valuable information on Open badges that is developed by Mozilla
* Understanding Digital credentials through a paper published by MIT on Digital credentials. 
* Got a nice understanding of the role of issuer, recepient and the advantages of Digital credentials
* Researched about Interoperable learner records. Gathered valuable information from a white paper on I.L.R published in September 2019 by American workforce. 
* Also gathered data about Learning and Employment Record from the T3 Innovation Hub

## Sprint 6

### Create a react component for the skill graph page

* Implemented draggable component and drop it into a table
* Fixing errors mainly one button falling into another and multiple buttonss of same skill
* Implenting search bar where the user can add skills after selecting from auto complete search
* Used npm Tyhpehead module to implement autocomplete search bar and also added funtionality of directly adding skill buttons when selected from dropdown

## Sprint 7

### Create a react component for the profile page

* Gathering crucial data about ILR's through Digitary website
* More research and consolidating information about ILR's and also preparing a presentation about Digitary for client meeting
* Uploading the image and also displaying basic information about the student in profile page and also redesigned the UI of profile page by taking reference from LinkedIn
* Displayed educational details, skills and work expereince from the previously collected data in the profile page

## Sprint 8

### Create a react component for the profile page

* Working on displaying stored data such as work experience, educational qualifications about the user in the profile page
* Preparing a final project report consisting of work done by engineering members on Jobverz
* Working on presentation and also demo part
* Working on the feedback given by mentors like adding duration of the job or education in the educational qualification page
