**Course**

IST-303 Software Development (Claremont Graduate University)

**Team Name:** Quiz Masters

**Team Members:**

Annie Ho

Davinder Ghotra

Francis Asomaning

Olalekan David-Banjo  

Kasia Tuszynska

# Installation
## 1. Clone/Fork the git repo and create an environment

### Windows

git clone https://github.com/profdbanjo/QuizMasters.git
#### cd QuizMasters
python -m venv venv

### macOS/Linux

git clone https://github.com/profdbanjo/QuizMasters.git
### cd QuizMasters
python3 -m venv venv


##  2. Activate the environment

### Windows

venv\Scripts\activate

### macOS/Linux

. venv/bin/activate or source venv/bin/activate


##  3. Install the requirements

Applies for windows/macOS/Linux

cd QuizMasters
pip install -r requirements.txt
--
## 4. export flask app and run
$ set FLASK_APP=routes.py (For Windows)
$ export FLASK_APP=routes.py (For Mac)

$ flask run

##  5. Run Pytest

From CD QuizmMasters

pip install pytest

pytest tests.py



# Project Goal

Over time, there has been an increase in the number of students requesting course waivers at CISAT.

CISAT has mandated the course facilitators to produce a Quiz app to serve as an evaluation for the waiver. If the student passes the quiz, they are eligible for a waiver.

So, the experiment will begin with the IST303 course, and therefore, Professor Wallace has contracted this project to Quiz Masters to develop an app to suit this purpose.

In the stakeholder's deliberation, they realized the quiz app could also serve as an assessment for students enrolled in the IST303 class.

If this experiment succeeds, CISAT will replicate the quiz app for all other courses offered in CISAT.


# Stakeholders

**Course Facilitator**

Professor Wallace is the project sponsor, and he has contracted the IST303 quiz app development to Quiz Masters to fulfill one of CISAT’s requirements for assessing how much understanding the student have in software development. This app would serve as an evaluation for those seeking to waive the IST303 class and an assessment tool for enrolled students.

**Center for Information Systems and Technology (CISAT)**

Our client operates under the directives of CISAT, making CISAT the investor in the IST303 quiz development. Should the quiz app become successful, CISAT intends to replicate this development in other core courses offered in the department.

**Students (End Users)**

Students from the IST303 class and others considering a course waiver will be the end-users who will rely on the app as an assessment and evaluation tool. They will take and complete the quizzes and perform other tasks that Professor Wallace requires. In addition, IST 303 students can seek help from the quizmaster’s help desk when there are issues or confusion.

**Program Coordinator (Secondary Users)**

These stakeholders fall under secondary users as they will be interacting with the products created by the software. Quiz Masters will ensure the IST303 quiz app produces outputs that fit into the workflow of the secondary users. Secondary users could generate reports from the app.

**Team members**

The team members include the product owner, scrum master, and developers.

While it is essential to have a product owner take accountability for the project, so will the scrum master ensure that the agile methodology adheres through collaboration and transparency. Finally, the developers will write the codes and build app interfaces.


# USER STORIES


**Create wireframe for quiz app {Priority 10: 1 Day}**

As a developer, I want to visualize the quiz app architecture prior to development

So that I can reduce the risk of building unnecessary software.

As a course facilitator, I want to see the feasibility of the app prior to development

So that I can be rest assured that the initial requirements are captured in the design.


**Formulate 20 quiz questions {Priority 10: 2 Days}**

As a course facilitator, I want the questions to reflect all topics in the curriculum

So that student’s assessment can be thorough.

As a user, I want the quiz questions to be indicative of what has been learned

So that I can prepare adequately.


**Structure questions for data store {Priority 10: 1 Day}**

As a course facilitator, I want the questions to reside in a data store

So that I access the data easily.

As a developer, I want the questions to be in a dictionary format

So that my codes can work optimally without impacting the app performance.


**Create logic for asking quiz {Priority 10: 1 Day}**

As a course facilitator, I want the question progression to be seamless

So that the quiz is well coordinated without manual intervention.


**Create logic for answering quiz {Priority 10: 2 Days}**

As a course facilitator, I want the students when using the app respond to questions in a True or False format

So that the app can be fun and engaging.


**Translate quiz logic into model {Priority 20: 5 Days}**

As a user, I want the app to be interactive and responsive

So that I can have an itch-free experience when attempting the quiz.


**Test model usability {Priority 20: 2 Days}**

As a developer, I want the app to be evaluated as development progresses

So that I can inspect and adapt my codes to prevent technical debt.

As a course facilitator, I want to be sure that the app will be usable

So that I can keep abreast of its feasibility.


**Build Quiz User Interface {Priority 10: 5 Days}**

As a user, I want the quiz interface to be enticing

So that I can be motivated to practice more quizzes.

As a stakeholder, I want the quiz interface to be appealing

So that I can be motivated to present it to the department.


**Display student scores on screen {Priority 20: 1 Day}**

As a user, I want the scores to be displayed on the screen while the quiz is ongoing

So that I have firsthand information on how I am doing in the quiz.

As a course facilitator, I want the students to see their scores as they progress in the quiz

So that the app provides transparency and a mode for evaluation.


**Populate student's result {Priority 20: 2 Days}**

As a user, I want to know the quiz outcome

So that I know the areas in the IST303 course to improve upon.


**Insert result into Scores table {Priority 20: 2 Days}**

As a course facilitator, I want to keep records of individual student’s score

So that I run quarterly reports to determine how the students are performing.


**Send results to students' email {Priority 30: 2 Days}**

As a course facilitator, I want the quiz result to be sent as email to the student immediately after the quiz

So that the students have a copy of their results for reference.


**Run usability test {Priority 20: 2 Days}**

As a course facilitator, I want to be rest assured that we are moving in the right direction by consistently testing the quiz app

So that we can keep the investor interested in the project.


**Build registration form {Priority 10: 2 Days}**

As a course facilitator, I want students to register prior to taking a quiz

So that the department can monitor students’ operations concerning the quiz usage.


**Create database schema {Priority 10: 2 Day}**

As a developer, I want a maintained database of current users

So that we can constantly be aware of the app usage.


**Registration form validation code {Priority 20: 3 Days}**

As a developer, I want to ensure that students enter the right information when registering for the quiz

So that I can have a reliable database.


**Build User login screen {Priority 10: 2 Days}**

As a course facilitator, I want students to have access to their profiles

So that the students can update their information accordingly.


**Login screen validation code {Priority 20: 3 Days}**

As a developer, I want to ensure that adequate security checks are put in place prior to the student logging in

So that their profiles are secured.

# Velocity

Team Members: 5

Each team member has competing professional and educational responsibiliteis, therfore the velocity for this effort is mitigated by other responsibilities. 

Starting Velocity for the group: .25

 * Milestone 1, Iteration 1 (9/19 - 10/4, 17 days) - 8 tasks completed
 * Milestone 1, Iteration 2 (10/5 - 11/1, 26 days with Midterm) - 7 tasks completed
 * Milestone 2, Iteration 1 (11/2 -11/15, 13 days) - 6 tasks completed
 * Milestone 2, Iteration 2 (11/16 - 12/6, 20 days with Thanksgiving) - 6 tasks completed


# Burn Down Chart
Click [here](https://github.com/eclatealba/QuizMasters/blob/main/IST303_QuizMasters_Burndown_chart_4.xlsx) to see the burndown rate and chart.

# Meeting Record
 * Meetings in person - met on each Tuesday after class, occasionally met on Thursdays for coding sessions
 * Meetings on Zoom - met over zoom once or twice a week to discuss project plans 
 * Information exchange via email - used to exchange ideas and hold longer discussions
 * Information exchange via Whatsapp - used to communicate extensively 


# Project Part B 

https://user-images.githubusercontent.com/113940939/193473294-a7fd3be5-05e1-4629-9db2-c40a910b40ea.mp4


**Milestone 1, Iteration 1 - Setup Development Environment**
 * Calculate Velocity (Kasia, Annie)
 * Identify tasks, based on user stories (Kasia)
 * Define Milestones and Iterations (Kasia)
 * Setup & Maintain Burndown Chart
 * Setup Enviornment (David)
  - Install Virtual Environment
  - Install Python
  - Install Pytest
  - Install Flask
 * Create a "Hello" Page to test the environment (David)
 * Write usage instructions (David)
 Issues completed: 3, 4, 5, 6, 7, 8, 9,11
 
 # Project Part C
**Milestone1, Iteration 2 - Build Quiz Model**
 * Research and deploy the Database Option (Kasia)
 * Write Test question issues (Kasia): 2, 12 - wrote 5 questions to test the MVP
 * Define the Minimum Viable Product (David,Anne,Frances,Davinder,Kasia) - 1 day
 * Create CSS templates (David) - 3 days
 * Create HTML styles (David) - 4 days
 * Issues satisfied: 1, 15, 18, 19, 20, 26
 
**Milestone2, Iteration 1**
 * Work on Quiz Taking experience (Annie, Davinder, Francis) - 5 days 
 * Work on Registration experience (Annie, Davinder, Kasia) - 2 days
 * Work on Login experience (Annie, Davinder, Francis) - 2 days
 * Create quiz scores
 * Combine Quiz Engine  (Annie, Davinder, Francis, David) - 5 days
 * Star writing unit tests for elements in the three user experiences: Registration, Login, Test Taking (David, Frances, Anne, Davinder)

 * Issues satisfied: 2, 10, 12, 13, 14, 16

# Project Part D

**Mileston2, Iteration 2 Work on Quiz Taking experience**
 * Functionality expansion, add a timer 
 * Complete Writing unit tests for Registration, Login and Test Taking experience
 * Test and Validate the holistic, combined testing effort
 * Test the Flask routes 
 
 * Issues satisfied: 17,  21, 22, 27, 28, 30
 
 **Testing Experience**
We can test the code installing all the packages in python. You will need to pytest the tests.py file. 

The codes were tested at previous levels in order to test the functionality of this entire application. The main principal codes we tested for the application were the registration forms, login forms, and landing page forms. In the registration forms, we tested the codes to assess better how the user experience feels during the process. We implemented tests that let us test how a username was created and whether the username meets the unique characteristics. We created unit tests and functional tests to test our registration process better. We parameterized tests to pass and fail based on specific criteria. In addition, we wrote tests for login forms the same way. The login forms tests can include ensuring a student email is used for a username, not just special characters. The motive for these tests is to have the authenticity of the application and to detect bugs and inefficiencies in our codes and applications. It is essential testing is done at all stages to ensure the validity and marketability of our application. We will also require ID numbers for the future of the application, so it is essential that only one ID is associated with one student. The most important part of the testing is that we create an easy and accessible user-friendly experience upon registering, signing up, and opening the quiz. Lastly, the testing of the landing page was to ensure the students could not retake the tests, and we wanted to ensure that an error warning occurred if a student tried to retake the exam. The product is incomplete in that we must develop our application and code and continue to test bugs and inefficiencies. We leave a lot to desire out there, and the testing portion can provide many capabilities. 

<img width="1440" alt="Screenshot 2022-12-05 at 6 52 38 PM" src=https://user-images.githubusercontent.com/112905335/205816608-6daa34da-b058-4334-bb9b-52b1ed8c219d.png>

# Final Deliverable
* Completed 29 tasks
* Two tasks were not pursued: 29, 23
* Three user experiences including Registration, Login and Test taking session. Allowing a student to take 20 questions within the scope of the IST 303 class for the purse of determining the possibility of testing out of the class. 

**What We Learned**
Collaboration: Our team consisted of five folks with different strengths and backgrounds. We saw challenges and opportunities from different perspectives. At times we had to talk thorough an issue or a decision over a zoom call to understand where everybody  was comming from, but ultimatelly the conversation gave a better underderstanding to all of us. 

Code Interpretation: Writing code to create and reading code to understand how it works together are different skills. Generating a solution was a very creative process, full of possible avenues for the project to diverge. However,when we ran into errors or logic challenges we needed to step thorugh the code in the order of its execution to find the element that needed fixing.

Agile Methodology: We learned a lot about Agile Methodologies through reading but the project gave us an opportunity to experience the process of managing an effort with forethough and planning. The approach made a lot of difference in terms of assessing what the team could accomplish given the constraints. 

* Final Presentation: https://docs.google.com/presentation/d/1lJ95T4EmM6BZx7x_cFSQIgDcUpd0O90_Svj6hMv-6ws/edit?usp=sharing
