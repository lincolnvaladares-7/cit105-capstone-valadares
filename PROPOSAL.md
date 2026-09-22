# Capstone Proposal

## Project Name
StudyTrack – Study Planner and Assignment Tracker

## 1. Problem Statement

As a college student, I have assignments from several courses with different due dates, priorities, and requirements. It can be difficult to keep track of what needs to be completed first and how much work remains.

StudyTrack will provide one place where I can record assignments, organize them by course and due date, track their completion status, and receive AI-generated study suggestions.

## 2. Intended Users

The primary user is a college student who needs a simple way to organize coursework and assignments.

The user only needs basic computer skills. The application will provide simple forms, buttons, and lists, so the user does not need programming or database knowledge.

## 3. User Stories

1. As a student, I can add an assignment so that I can remember what work I need to complete.

2. As a student, I can view all of my assignments so that I can see my current workload.

3. As a student, I can filter assignments by course or status so that I can focus on specific work.

4. As a student, I can mark an assignment as completed so that I can track my progress.

5. As a student, I can edit or delete an assignment so that I can correct information or remove work I no longer need.

6. As a student, I can request an AI-generated study suggestion so that I can decide how to organize my study time.

## 4. Data

The application will store assignment information.

### Assignment Fields

- assignment_id – required, unique identifier
- title – required, assignment name
- course – required, course name or code
- description – optional, additional assignment information
- due_date – required, assignment deadline
- priority – required, Low, Medium, or High
- status – required, Not Started, In Progress, or Completed
- estimated_hours – optional, estimated amount of work
- notes – optional, personal notes
- created_at – required, date and time the record was created

These fields can later be converted into a database table during Module 7.

## 5. AI Feature

StudyTrack will include an AI Study Assistant.

The user can select an assignment and ask the AI for a short study plan. The application will send information such as the assignment title, description, due date, priority, and estimated study time to the generative AI model.

The AI will return a short suggested plan that breaks the work into manageable steps.

If the AI service fails, times out, or returns an unusable response, the application will not delete or modify any assignment information. Instead, it will display a message explaining that a study suggestion could not be generated and allow the user to try again.

AI suggestions will be treated as optional recommendations rather than automatically changing stored data.

## 6. Framework Choice

I will use Streamlit.

Streamlit is appropriate because StudyTrack is a small interactive web application centered around forms, tables, filters, and displaying data. It will allow me to build and test the interface quickly while continuing to use Python throughout the project.

Streamlit also makes it practical to demonstrate the entire application in a browser during the final presentation.

## 7. Out of Scope

To keep the project realistic for the five-week development period, the following features will not be included:

1. Multiple user accounts or authentication.
2. Integration with Canvas, Blackboard, Moodle, or other school systems.
3. Email, SMS, or push notifications.
4. Automatic submission of assignments.
5. A mobile application.

These features could be considered for future versions, but they are not necessary to demonstrate the main purpose of StudyTrack.
