# OneSchool
Web Application developed for the exam of computer engineering degree at Sapienza University: "LABORATORIO DI ARCHITETTURE SOFTWARE E SICUREZZA INFORMATICA". 
It's an electronic school register based on Ruby on Rails technology.
## Tecnologies adopted
- Ruby on Rails
- RSpec and Capybara for testing
- Sqllite for database
- Jitsi meet rest api
- Google oauth rest api
- Google calendar rest api
## User Roles in the Web Application

- **Unidentified User:** A user without privileges, only able to log in.
  
- **Admin:** Has access to the web application's information. The admin can log in either with their Google account or by registering with email and password. They can register a school, modify its data, create accounts for all School Staff members in a particular school, and modify their credentials.

- **School Staff:** Accounts for the school administration that functions as a local admin. This role creates and modifies accounts for Teachers, Parents, and Students within their school. They also handle sending notices to the entire school, creating classes with various students, and designing the class schedule.

- **Teacher:** User account for teachers who can log in with their Google account after the initial login to access their personal calendar and add events. They can participate in scheduled meetings with parents, input evaluations, notes, and absences for individual students in their class, assign tasks to the entire class, access the class agenda, and read communications. They can also request a meeting with a parent by sending an email. When the teacher logs into their school account using the application credentials (not Google), they cannot access their personal calendar.

- **Family:** Parent user who can choose their child (if they have more than one) to access information about the selected child. Information includes grades for individual subjects, view the class schedule, see and justify absences, view school notifications, and justify notes given to the student. They can also schedule meetings with the teacher.

- **Student:** Minor student user who can access information about their grades for individual subjects, access the agenda, submit assignments, view their own absences, notes, and communications. Adult student users, in addition to these functions, can participate in meetings with teachers and justify their absences and notes.
  
### Project Contributors
- De Vecchis Alessia
- Laganà Simone
- Manetti Francesco
- Tamarri Jacopo
