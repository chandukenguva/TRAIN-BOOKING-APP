Train Booking_APP IN C
--------------------------------

Description:
-------------
This project is a console-based Train Booking APP developed in C. 
It allows users to sign up, sign in, book tickets, cancel tickets, and view booking or train details. 
Admins can manage train information.

Features:
---------
1. User Sign Up and Sign In
2. Train Ticket Reservation
3. Ticket Cancellation
4. View Booking Information
5. View Train Details
6. Admin Login to Add/View Trains

Files:
------
- menu.c       : Main program logic with user/admin menu interfaces.
- header.h     : Function prototypes, macros, and data structure definitions.
- Other source files (not included here) are assumed to handle:
    * User registration/login
    * Train data synchronization
    * Ticket booking and cancellation
    * File handling (load/save)

How to Compile:
---------------
Use any standard C compiler (e.g., GCC):
$ gcc menu.c -o railway -lm

How to Run:
-----------
$ ./railway

Admin Access:
-------------
To access the Admin menu from the user interface:
1. Select option 6 in the User Menu ("add_train").
2. Enter the admin username: `admin`.

Note:
-----
- Make sure required header and source files (e.g., header.h, train.c, booking.c) are present in the same directory.
- This project uses dynamic memory and file handling for data persistence.

