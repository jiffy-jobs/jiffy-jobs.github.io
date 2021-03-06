
# Project Links
<a href="https://jiffyjobs.meteorapp.com/">Jiffy Jobs</a>

<a href="https://github.com/jiffy-jobs/jiffy-jobs/milestone/1">Milestone 1</a>

<a href="https://github.com/jiffy-jobs/jiffy-jobs/milestone/2">Milestone 2</a>

<a href="https://github.com/jiffy-jobs/jiffy-jobs/milestone/3">Milestone 3</a>
# Table of contents

* [About Jiffy Jobs](#about-jiffy-jobs)
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [About Us](#about-us)
* [Goals](#goals)
* [Development History](#development-history)


# About Jiffy Jobs

   The UH Manoa students in engineering and computer science are experiencing a major lack of knowledge regarding the jobs or internships that are available and wanting to hire them in or out of college. The only places they can find jobs pertinent to their respective fields is by attending a career fair day or working in one of the limited STEM positions available on campus through the SECE website provided by UH Manoa. The main purpose is to help the engineering and computer science students have more direct line of communication with companies that want to hire them. The students submit their interests which helps match them to employers or vice-versa. The site is built for interactivity between the employers and students to create an engaging and professional environment.

*~Jobs in a jiffy!*

# User Guide

Before logging in, the landing page will prompt the user to either log in or sign up. 

![Logged out Landing](images/loggedouthome.png)


To log in, enter your email and password. If you don't have an account, sign up. 

![Login Page](images/login.PNG)

The sign up page will prompt you to enter your name, email, and password, and then asks you to choose a user type. Choose either whether you are a company or student. 

![Signing up](images/signup.png)

After logging in, you will be redirected to the landing page. It should now look like this: 

![User landing](images/userlanding.png)

Notice that there are new components on the navbar. From left to right, the first component allows you to view your profile, the second component allows you to view your dashboard, and the third allows you to view a dropdown menu with other features.


![navbar components](images/rightside.png)


Your profile shows your personal information. This includes name, description, interests, location (for companies) or graduation year (for students), interests, and contact information. For companies, it also displays a rating.


![profile information](images/profileinfo.png)

The dashboard shows different information depending on your user type. Students can view a collection of companies and companies can view a collection of students. From the dashboard, student and company users can click on the "View Profile" button to be redirected to a profile.


![dashboard](images/companydash.png)

Student users are able to rate companies either on their dashboard or on the company's profile page

![rating](images/rating.png)

Admin users can delete profiles and view profiles.

![admin dashboard](images/admindash.png)

The third component on the dashboard shows a dropdown menu. Currently, only the Edit Profile and sign out feature works. 

![dropdown menu](images/dropdown.png)

If you are a company you can edit your company name, location, phone number, website, image, description, and interests.  

![Edit profile](images/editprofile.png)

If you are a student, you can edit your name, graduation year, phone number, website, image, description, and interests. 
After editing your information, don't forget to submit!
 
On the far left of the navigation bar, you can click on our logo to return to the dashboard. 

![profile information](images/returnlanding.png)

When you are done, don't forget to sign out!

# Community Feedback

Many users found it easy to create an account, edit, and view profiles. Some users ran into bugs but they were able to go back if they encountered one. Users were also able to rate and they enjoyed the application. Some criticisms included having to put a URL to upload an image and not being able to contact companies. Overall, the consensus was good and they enjoyed the design of the site. 

   
# Developer Guide
First, [install Meteor](https://www.meteor.com/install).

Second, [download a copy of Jiffy Jobs](https://github.com/jiffy-jobs/jiffy-jobs/archive/master.zip), or clone it using git.
  
Third, cd into the app/ directory and install libraries with:

```
$ meteor npm install
```

Fourth, run the system with:

```
$ meteor npm run start
```

The application should appear at [http://localhost:3000](http://localhost:3000).  

# Goals
* Create a clean and modern landing page. Below is similar to what we had in mind for our landing page:

![Landing example](images/landing-example.jpg)
 
* Provide a profile page for companies that includes information about the company and possible job opportunities.

![Company profile example](images/companyprofile.jpg)

* Provide a profile page for students that includes general information about the student, customization options, and resume/website links.

![Student profile example](images/studentprofile.jpg)

* Create a dashboard page that lists all companies/students as cards that includes links to their profile pages & general information.

 ![Student homepage example](images/studentpage.jpg)
 
 ![Company homepage example](images/companypage.jpg)
 
* Create a search page that allows students to search for opportunities and find company profiles.
* Create an admin profile page to manage what companies appear and filter profiles.

![Admin page example](images/admin.jpg)
* Feed for company announcements and other important information.
* Implement a rating/point system: Students will have a point display in their profile. Students can earn points through accepting internships. Points are distributed by companies through their profiles. Students will have the option to leave starred reviews for a company.

# Development History
<h2> Milestone 1 </h2>
<h3> Landing page created </h3>

* Menu bar working
* Dropdown working

![Landing page](images/landing.PNG)

<h3> Login page functional </h3>

![Login page](images/login.PNG)

<h3> Signup page functional </h3>

![Signup page](images/register.PNG)

<h2> Milestone 2 </h2>

![Comapny Dashboard](images/CompanyDashBoard.PNG)

<h3> Company dashboard page functional </h3>

![Student Dashboard](images/StudentDashBoard.PNG)

<h3> Student dashboard page functional </h3>

![Example Student Profile](images/JJStudentProf.PNG)

<h3> A basic example of what a student profile will look like </h3>

![Example Company Profile](images/JJCompanyProf.PNG)

<h3> A basic example of what a company profile will look like </h3>

* In progress. Mockups have been created for pages and issues have been assigned.

<h2> Milestone 3 </h2>

![sign up page](images/signup.png)

<h3> Register page functional </h3>

![edit page](images/editprofile.png)

<h3>Edit page functional</h3>

![Admin profile](images/admindash.png)

<h3>Admin dashboard functional</h3>

![rating](images/ratingprof.png)

![rating](images/ratingdash.png)

<h3> Implemented rating systems that are shown on company profiles and company cards </h3>



# About Us
The team:

<h3> Cade Yamamoto </h3>

<img src="images/cyprofile.jpg" width="200" height="250" />

Hello! I am currently a sophomore majoring in computer science at the University of Hawaii at Manoa. Though I intend on pursing a career in cyber security, I enjoy designing aesthetically pleasing web pages. I have adequate knowledge of Semantic UI and React JS and I wish to further my web design skills. My main focus in this project is to implement a modern design with ease-of-use being the primary design aspect of the site. I hope you will enjoy our site!

<h3> Levy Matsuda </h3>

<img src="images/lmimage.jpg" width="200" height="200" />

I am currently a sophmore majoring in Computer Science at the University of Hawaii at Manoa. I am considering pursuing a career in web development or computer programming. I have not had prior coding experience. My goal is to become more familiar with React so that eventually, using React becomes more intuitive. I also aim to understand the process behind creating a website better instead of just memorizing code.

<h3> Alexander Wong </h3>

<img src="images/profile.jpg" width="200" height="200" />

I am currently a Junior majoring in computer science. I am not sure what field I want to go into yet but programming either a website or application sounds interesting to me. I like to design so hopefully through this project I am able to improve my skills in both layouts and coding. 

<h3> Joel Sikkink </h3> 

<img src="images/joel.jpg" width="200" height="200" />

I am an IT support specialist at ResNet for the Student Housing at Manoa. I bring moderate knowledge of databasing to the team however I am more familiar with SQL rather than MongoDB and I would prefer PHP over Simple Schema and React. This project will hopefully improve my understanding of good website and user based design as I will be creating apps for use by my department at work by next year but I will be using SQL and PHP over the solutions used in this class.  

