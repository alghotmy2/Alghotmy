# Alghotmy assignmnet 3 for mobile web dev 

Create a new Angular project called yourLoginNameA3 
•  Create a header component and a footer component 
•	Format both header and footer components (tags to be used; ex. h1 and h3) to the same formatting in regard to background and text colour plus any other formatting of your choice; You can format each .css for header and footer .
•  Create a file called yourLoginName.ts in the app folder. In this file, create a class called YourLoginName that includes the following definition with your choice of label and type (see student.ts file in our in-class example as a reference): 
•	Your student number, your name, your login name, your campus, and assignment title
•	In both the header and footer component .ts files, import and create a variable to fill in the class data with your information.
Note: For this assignment, you will duplicate the data in the header and footer components; we will learn later how to set it once and use in multiple components
•	In the header component html file, use string interpolation from your personal class data to display assignment title / your name in an HTML header tag (not hard-coded).
•	In the footer component html file, use string interpolation from your personal class data to display your name / your student number / your login name / your campus in an HTML header tag (not hard-coded)
•	Note: You may need to stop the node server and start up again after creating a class. Use Ctrl+C to terminate batch job then "ng serve" again after class file is created.
•  Be sure to update your app.component.html with the components you want to display 
•  Create another .ts (example: bookInfo.ts) file in your app folder to hold another class for books that will include the following definition (your choice of file name and class name): 
•	book name / author / book genre (ex. Biography, Mystery, etc.) / year published / picture
•	Create a data file (hard-coded) called myBooks.ts. Create data for 4 of your favourite books with the data from the class created (use myClasses.ts in our in-class exercise for reference)
•	Note: Pictures will need to be included in the images folder created for the default setup. The picture itself can be anything you want.
•  Create a component called YourLoginName (this will be your actual login name). Create a structure using a grid-area for Landscape Mode to include a navigation section under the header that goes across the screen then 2 areas (one on the left and one on the right) under the navigation section. One side will hold a picture and the other will hold the book details (your choice of how details are displayed). 
•  Be sure to import your book data into the yourloginname.component.ts and setup a variable to hold the data (see class-list.component.ts in our in-class project for reference) 
•  In the yourloginname.component.html, setup a directive (*ngFor) to create 4 buttons in the nav section; be sure to include an index so you can capture which is selected so you can display detail data and the picture from the data file based on the button clicked; also be sure to include a (click) event to call a function to find correct book data. Be sure one of your books is displayed as a default on start-up. 
•  Note: You can use *ngFor not only with list items (as we did in our in-class exercise) but also with buttons or any other HTML tag. 
•  Hint: Create an ID area inside both output areas; use document.getElementById to find the output area then update the .innerHTML with the correct book output; 
________________________________________
________________________________________
What to submit...
•	You will be submitting your cPanel URL to your published site and a ZIP of your project's src folder ONLY in the SLATE dropbox
•	You will also submit your gitHub URL in the comment section
•	Remember: You have 3 days past the due date with 10% off per day to submit
•	For help with publishing/deploying, see the AngularDeployment presentation under Module05 and cPanel setup under References Module

•	Each assignment must be done individually.
    I will be checking for copying especially if the assignments look similar and will file an academic integrity breach if necessary

•	This is not an assignment that should be started the day it is due.
    Since you have 2 weeks to complete the assignment, NO EXTENSIONS to the due date will be given.
________________________________________
Grading Rubric...
Header and Footer Components / Setup plus formatting	1
Class creation with your personal data and inclusion in the header and footer components	1.5
Book class creation plus data file	1.5
Detail Grid Layout and formatting plus on start-up display of one of the books	2
Detail Data including working buttons	4
5 points will automatically be deducted if assignment is not published in cPanel AND GitHub
5 points will automatically be deducted if correct ZIP (src folder only) is not included in submission

