- [Doctors Evaluations](#doctors-evaluations)
      - [Sections:](#sections)
      - [Tools Used](#tools-used)
- [Dashbard](#dashbard)
  - [Home Page](#home-page)
  - [Content Pages](#content-pages)
  - [Add / Edit / Delete](#add--edit--delete)
  - [Evaluations](#evaluations)
  - [Archives](#archives)
- [Employee Form](#employee-form)
- [Evalution Questionare](#evalution-questionare)


# Doctors Evaluations
The goal of this project was to provide the University with statistical data about how students evaluated their doctors and whether the doctors were doing their job correctly or not. This evaluation was done by students who answered some questions about their doctors' ways of handling them and providing teaching/learning materials.

#### Sections:
- **Employee Form:** The employee enters the site URL and logs in as an employee with his account to open a `form` where he can configure the evaluation settings (like what class and doctor to evaluate) and then start the evaluation process where an `evaluation URL` is generated so that students can use it to open the questionare site and start their evaluation.

- **Admin Dashboard:** The admin logs in as an admin to open the administration dashboard where he can access and edit all data about available University Faculty `Departments, Courses, Doctors, Evaluations, Users, Archives, Logs, and Evaluations`. He then can access the statistics of the evaluations and `generate a pdf` of each evaluation to show it to the appropriate University personnel. An evaluation report can be generated for a Department, a Course, or a Doctor.

#### Tools Used
  - **Backend:** Laravel PHP Framework
  - **Frontend:** HTML & Laravel's Blade Templates
  - **Styling:** Bootstrap CSS Framework


# Dashbard
Here are some screenshots of some of the dashboard features

## Home Page
The home page shows how many items are there for each section in the dashboard and shows the latest evaluations done on the right side of the page.

![Home Page](Screenshots/home%20page%20after%20evaluation.png)

## Content Pages
The Dashboard is separated into the follwing content sections.

- Departments
  ![Departments](Screenshots/departments.png)
- Courses
  ![Courses grouped by Learning Year](Screenshots/courses.png)
- First Year Courses
  ![First Year Course](Screenshots/first%20year%20courses.png)
- Doctors
  ![Doctors grouped by Departments](Screenshots/doctors%20groupedd%20by%20departments.png)
- Users
  ![Users](Screenshots/users.png)
- Questions
  ![Questions grouped by Categories](Screenshots/evaluation%20questions%20grouped%20by%20category.png)
- Categories
  ![Categories](Screenshots/question%20categories.png)

## Add / Edit / Delete
Some of the features of some section.

- Add Course
  ![Add Course](Screenshots/add%20new%20course.png)
- Edit Course
  ![Edit Course](Screenshots/edit%20course.png)
- Edit Course's Dcotrors
  ![Edit Course's Dcotrors](Screenshots/edit%20course%20doctors.png)
- Add Doctor
  ![Add Doctor](Screenshots/add%20new%20doctor.png)
- Edit Doctor
  ![Edit Doctor](Screenshots/edit%20doctor.png)
- Edit Doctor's Courses
  ![Edit Doctor's Courses](Screenshots/edit%20doctor's%20courses.png)
- Edit/Delete Department's Courses & Doctors
  ![Edit/Delete Department's Courses & Doctors](Screenshots/department%20courses%20and%20doctors.png)
- Add Evaluation Question
  ![Add Evaluation Question](Screenshots/add%20evaluation%20question.png)

## Evaluations
Evaluation reports are generated for each Department, Course, & Dcotor. The report is generated with respect to the chosen university year (ex: 2017-2018, 2018-2019, ...). These reports can also be exported and downloaded as pdf.

- Evaluated Departments (also avaiable for Doctors & Courses)
  ![Evaluated Departments (same for soctors & Courses)](Screenshots/show%20evaluated%20department%20doctors.png)
- Department
  ![Department](Screenshots/department%20evaluation.png)
- Doctor (also available for Courses)
  ![Doctor (also available for Courses)](Screenshots/doctor's%20evaluation.png)
- Evaluation Logs
  ![Evaluation Logs](Screenshots/evaluations%20log.png)
- Doctors Evaluation Comments
  ![Doctors Evaluation Comments](Screenshots/doctor's%20evaluation%20comments.png)

## Archives
All deleted data is archived.

- Course's Doctors Archives (also available for Departments & Doctors)
  ![Course's Doctors Archives (also available for Departments & Doctors)](Screenshots/course%20archive%201.png)
  ![Course's Doctors Archives (also available for Departments & Doctors)](Screenshots/course%20archive%202.png)


# Employee Form
The Employee section.

- Evaluation Form
  ![Evaluation Form](Screenshots/employee%20evaluation%20form%202.png)
- Generated Evaluation Link & Progress
  ![Generated Evaluation Link & Progress](Screenshots/evaluation%20in%20progress%201.png)
- Evalaution Done
  ![Evalaution Done](Screenshots/evaluation%20done.png)


# Evalution Questionare
The Students section.

![Evalaution Done](Screenshots/evaluation%20questionare.png)