# Meeting 10/24/2025

**Attendance:** Win, Will, Rhea, Jialuo, Luting, Ethan

## Conductor Tool (Overview/requirements) ([Link](https://tpowell.craft.me/xXuZoY59NY9R36))

A course management platform for software engineering classes. It helps professors, TAs, and students manage the course more efficiently.

**Users:** Professors, TAs, Tutors, Team Leaders, Students
- Will: users are mutually exclusive for each instance of a class (except TL & students)
- Rhea: Who manages user roles? How to handle changing user roles?
- Ethan: How much power do TAs have in managing user roles?

## What we need to build:

1. Login system - Google OAuth
2. Dashboard - Name, photo, contact info, ...
3. Class Directory
4. Role-based access - different views for different user types
5. Attendance System
6. Work Journal

## What we can start with:

1. Set up our repository
2. GitHub projects for tracking tasks and issues
   a. Create user stories
3. Communication on Slack
4. Team 7 meeting every Friday 10:30am
5. Daily standup EOD from everyone
6. Design doc

## Suggestions:

- Using TA user stories to set standard for our SWE approach
- Naming conventions:
  - Ethan: Create a linter (ESLint)
  - Branches: issuenumber-issuename
    - Kebab case
  - etc.

## Questions:

**What are each components of the flow diagram? (Dashboard Vs. User Manager)**
- Jialuo: What is the difference between the dashboard and user profile? What should the dashboard look like?
- Win: Is a dashboard something that connects everyone to the class?
  - Active one instance vs stored past instances of class?
- Rhea: Is there a separate dashboard for each type of user?
- Who has the power to make/change groups?
- Win/Jialuo: How to approach login/authentication, and should it be just for UCSD or in general?
  - Is it ok to start with Google authentication?
- What are the necessary features for the end product, and what are the nice-to-haves?
- Are there any other use cases/user stories?
- If we work with another team, do we share the same repository?

## To Do:

- Rhea/Wayne: Ask professor questions, ask other teams if they are open to collaborating
  - Rhea: Make and share design doc
- Ethan: Set up repository, linter
- User stories by End of 10/26: 2 people assigned to detailing each user story and coming up with questions for them
  - Prof: Braxton, Cole
  - TA: Emma, Gaurav
  - Tutor: Jialuo, Luting
  - Team Lead: Rhea, Wayne
  - Student: Sree, Will
  - Other/review user stories: Win, Yuri
- Daily standups starting tomorrow, 10/25. Updates due by EOD
