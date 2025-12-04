# Spring-mvc-crud-operation
🎬 Spring MVC Movie Management System  A simple and elegant Movie CRUD Application built using Spring MVC, JSP, Servlet API, and Hibernate/JPA. The project allows users to Add, View, Edit, and Delete movie records with a clean, modern UI.

📌 Features
✔ Add Movie

Add a movie with:
Name
Image URL
Rating
Genre

Clean input form with polished UI.

✔ View Movies (List View)

Displays all movies in a modern card layout.
Each movie includes:
Poster preview
Title
Genre
Rating
ID

Responsive design for all devices.

CSS-only hover animations.

✔ Update Movie

Edit any movie details and save changes.

✔ Delete Movie

Remove a movie instantly

Success message displayed using CSS-only alert (no JavaScript required).

<img width="1911" height="959" alt="Screenshot 2025-12-04 193500" src="https://github.com/user-attachments/assets/5926dce5-6c03-4b0d-a555-79bc05aee0a0" />
<img width="1907" height="948" alt="Screenshot 2025-12-04 193517" src="https://github.com/user-attachments/assets/4fcbb3f9-e6c1-4007-ab69-993d8c904a95" />
<img width="1890" height="958" alt="Screenshot 2025-12-04 193539" src="https://github.com/user-attachments/assets/ad772b4f-9f09-44cd-9ebf-e162d839569b" />

🏠 Movie Management Dashboard

Clean dashboard with action buttons

Centered modern card UI
(Refer to the screenshot in the repo)

➕ Add Movie Page

Intuitive form layout

Smooth rounded UI

Validations supported

🎞 Movie List View

Stylish poster previews

Card-style listing

Edit & Delete options

Success message displayed after deletion

🛠 Technologies Used
Spring MVC
Spring Web MVC Dispatcher Servlet
Hibernate / JPA
JSP + JSTL
HTML5, CSS3 (Modern UI Design)
Tomcat Server
MySQL / H2 Database (your choice)


🔧 How It Works
1️⃣ Controller Layer
Handles all HTTP requests:
/ → Home dashboard
/addmovie → Add movie
/viewmovie → Show all movies
/edit → Edit movie
/delete → Delete movie

2️⃣ Service / DAO Layer
DatabaseLogin manages:
Save
Update
Delete
Fetch all movies
Fetch one movie
Using EntityManager + JPA Transactions

3️⃣ JSP Views
All pages contain clean, modern CSS without JavaScript dependencies.
