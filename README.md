# Travel-Planning-Application

<strong>**DO NOT DISTRIBUTE OR PUBLICLY POST SOLUTIONS TO THESE LABS. MAKE ALL FORKS OF THIS REPOSITORY WITH SOLUTION CODE PRIVATE. PLEASE REFER TO THE STUDENT CODE OF CONDUCT AND ETHICAL EXPECTATIONS FOR COLLEGE OF INFORMATION TECHNOLOGY STUDENTS FOR SPECIFICS. **</strong>

# WESTERN GOVERNORS UNIVERSITY 
## D424 – SOFTWARE ENGINEERING CAPSTONE
Welcome to Software Engineering Capstone! This is an opportunity for students to develop full stack software engineering documentation and applications. They will execute documentation, unit testing, revision of software applications, and deploy software applications with scripts and containers on a cloud platform.

FOR SPECIFIC TASK INSTRUCTIONS AND REQUIREMENTS FOR THIS ASSESSMENT, PLEASE REFER TO THE COURSE PAGE.
BASIC INSTRUCTIONS
For this assessment, you will deploy your developed full stack software product to a web service of your choice.


## SUPPLEMENTAL RESOURCES  
1.	How to clone a project to IntelliJ using Git?

> Ensure that you have Git installed on your system and that IntelliJ is installed using [Toolbox](https://www.jetbrains.com/toolbox-app/). Make sure that you are using version 2022.3.2. Once this has been confirmed, click the clone button and use the 'IntelliJ IDEA (HTTPS)' button. This will open IntelliJ with a prompt to clone the proejct. Save it in a safe location for the directory and press clone. IntelliJ will prompt you for your credentials. Enter in your WGU Credentials and the project will be cloned onto your local machine.  

2. How to create a branch and start Development?

- GitLab method
> Press the '+' button located near your branch name. In the dropdown list, press the 'New branch' button. This will allow you to create a name for your branch. Once the branch has been named, you can select 'Create Branch' to push the branch to your repository.

- IntelliJ method
> In IntelliJ, Go to the 'Git' button on the top toolbar. Select the new branch option and create a name for the branch. Make sure checkout branch is selected and press create. You can now add a commit message and push the new branch to the local repo.

## SUPPORT
If you need additional support, please navigate to the course page and reach out to your course instructor.

## FUTURE USE
Take this opportunity to create or add to a simple resume portfolio to highlight and showcase your work for future use in career search, experience, and education!


### Task 3 Checklist

Section B
~~-code including inheritance, polymorphism, and encapsulation~~
~~-search functionality with multiple row results and displays~~
~~-a database component with the functionality to securely add, modify, and delete data~~
~~-ability to generate reports with multiple columns, multiple rows, date-time stamps, and title~~
~~-validation functionality~~
~~-industry-appropriate security features~~
~~-design elements that make the application scalable~~
~~-a user-friendly, functional GUI~~

### TODO List

-add search functionality on vacation list page, user can search for destination, accommodation title or by dates
        ---filter output by which parameter was searched??
        ---Creating reports with searchable parameters is common.
-build a way to produce internal reports with any amount of data, at least two parameters
-security features, possibly build a log in page that will use security features with the password
-double check for polymorphism and encapsulation


## notes

Title and Purpose of the Application
--Vacation Tracking Application
The purpose of this application is to allow users to build a list of vacations, including the details of each vacation such as title and accommodation as
well as the start and end date of the vacation. The application also allows the user to add and update some
associated excursions for each vacation.

Directions of how to operate the application
--
1. To start the application the user will click the enter button at the bottom of the 'Vacations' title screen. This will enter the application
   and bring the user to the vacation list page. This vacation list will continually be updated as users continue with the application through
   the use of Room Framework as stated in requirement B1.
2. After the user has reached the vacation list they can click the action button in the bottom right corner of the screen, which will take them to the vacation details screen.
   Here the user can add a title, the accommodation and the start and end date of their vacation. This meets the requirement for B2.
3. For requirement B3-a the user can click each specific vacation title on the vacation list screen.
   This will bring up the vacation details for that specific vacation and allow for updates to be made and saved.
4. For the requirements of B3-b, B3-c, and B3-d, the user can edit vacation information by clicking ona specific vacation.
   The vacation details page will allow the user to edit or delete vacations. Using the date pickers on the vacation details screen will trigger validation logic that will not allow the
   user to pick dates that are formatted correctly and validate that the end date is always after the start date. The user will see a toast message that shows their error if such an error occurs.
5. If the user stays on the vacation details screen they can expand the menu in the top right corner of the screen to access alert functions and sharing functions that meet the requirements
   for section B3-e and B3-f. The alert function allows the user to set an alert for either the vacation starting, ending or a set full to have alerts for both the start and end date. The share
   vacation option will allow the user to send emails, sms, or other communications that will auto-populate with the vacation details.
6. For section B3-g and B3-h the user can use the application to add excursions to each vacation. When on the vacation details screen the user can click the plus button to access the excursions page.
   On this page the user can add the title of their excursions as well as the date of the excursion. The button at the top right of the screen expands a menu that will allow the user to
   save or delete the excursion. From the vacation details page the user can see all of the excursions associated with the vacation displayed here. Clicking on an excursion will bring up
   the page for that excursion which will allow a user to update previously created excursions.
7. For requirement B4, the user can just observe the vacation details page where each of the excursions will be displayed along with the start date that was chosen by the user.
8. If the user clicks an excursion it will open the add excursions screen. Here the user can see the details of the excursion and update or even delete the excursion. The date picker at the bottom
   of the screen includes validation that will not allow the user to set the excursion date outside of the dates specified for the start and end of the vacation. Using the menu drop down at the top right
   of the screen the user can set an alert that will notify them when the exursion is happening that day. These actions will cover the requirements for B5 a-e.
9. The entirety of the application includes the proper elements, screens, and information that is required by task C. The openening screen is the homescreen that then allows access to the
   vacation list screen. For here the user can access the vacation details screen which also shows the detailed list of excursions. Clicking any excursion brings up the details page for an excursion.


Android Version for APK
-- Android 16, API version 36
