# Movie-ticket-booking-
The Movie Ticket Booking website is a dynamic, user-friendly platform developed using PHP for the backend logic and MySQL for the database management. This website enables users to browse and book tickets for their favorite movies conveniently online.

**Introduction:**
“Online Movie Ticket Booking System” project is a project where one can view movies and book online tickets for the movies. The main purpose of the project is to provide an online system for booking movie ticket and provide an online system to replace the existing manual booking system.This system is implemented to provide a smooth system for booking movie ticket. We have implemented the system in such a way that any user can easily book a movie ticket easily, no prior knowledge of any language is needed to use the system. Every organization or cinema hall whether it is big or small need an online system to replace the existing manual booking system, so that the users can book ticket themselves without visiting the theatre. This reduces the queues on booking counters.

**Software used:**
We have used following basics software for the project –
1. Visual Studio Code 
2. Web browser (Google Chrome)
3. Xammp local server

**Language used:**
Frontend languages -
1. HTML
2. CSS
3. Bootstrap

Backend languages –
1. PHP
2. JavaScript
3. jQuery
4. SQL

**About the project:**
In the project “Online Movie Ticket Booking System” we have implemented the basic activities of an online movie ticket booking system like booking online movie ticket, cancel movie ticket, view movie, add a movie, add show timing, delete user, update user profile etc.In this project a user can view movies and book online ticket by selecting movie and show time. Before booking a ticket, user must be registered if he/she is registered he/she can login to the system and book movie ticket. If he/she is not registered, he must be registered.

In this project we have provide two panel –
1. User panel
2. Admin panel

**User panel –**
To access user panel, a user has to registered, if he/she is registered if may login to the system and access the user panel or user dashboard. In the user 
dashboard a user can do activities like –
1. View/Update profile
2. Change password
3. Book movie ticket
4. View booked tickets
5. Cancel booked ticket
6. Logout

User login details –
Email id – test@gmail.com
Password – test@123
You may also register a new user and login to access the user panel.

**Admin panel –**
To access admin panel, one has to login using admin’s login details. Once 
logged in as an admin, admin can do some basic activities like –
1. Add a movie
2. Add a show
3. View user
4. Delete user
5. Logout

Admin login details –
Email id – admin@gmail.com
Password – admin@123


**Database details –**
To store the related data, we have created a database named “movie_db”. In 
this database we have created many tables to store the data like user’s data, 
movie data, show timing, bookings, movie details etc.
Schemas –
1. User Schema –
users (id, name, email, password, mobile);
2. Movie Schema –
movies (id, name, description, link, logo);
3. Shows Schema –
shows (id, show_time);
4. Booking Schema –
booking (booking_id, booked_seats, user_id, movie_name, show_time, 
booking_time, is_cancel);
5. Admin Schema –
admins (id, name, email, password);
