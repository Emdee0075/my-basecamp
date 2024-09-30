# Welcome to My Basecamp 1
***
This project is hosted here: https://basecampdan.onrender.com


## Task
The objective of this project is to build a project management tool inspired by Basecamp. The application allows users to create accounts, sign in, manage projects, and assign role-based permissions (admin/user).

Key Challenges:
-Implementing user authentication and session management.
-Designing a role-based permission system.
-Enabling full CRUD operations for managing projects.
-Ensuring a seamless user experience through intuitive UI/UX.

## Description
This application provides users with the ability to:

-Register and log in to the platform.
-Create, view, edit, and delete projects.
-Assign and remove admin privileges.

The project follows an MVC architecture with a Ruby on Rails backend and a basic frontend using HTML, CSS, and JavaScript.

How I solved the problem:
-User Management: Implemented using Rails' built-in authentication system (bcrypt for password hashing).

-Role Permissions: Created an admin role that allows privileged users to manage other users and projects.

-Project Management: CRUD operations for projects were built with RESTful routes.

-UI: Designed a clean and simple interface with forms for user input and project management.


## Installation
Clone the repository:
git clone https://git.us.qwasar.io/my_basecamp_1_169920_dcicbv/my_basecamp_1.git

Navigate into the project directory:
cd my_basecamp_1

Install the necessary dependencies: For Ruby on Rails:
bundle install

Set up the database:
rails db:migrate




## Usage
To start the Rails server:
rails server

### The Core Team
Maspara Dan

<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>
