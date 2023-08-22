# GuestBook_Flask_app
Simple web application built using the Flask framework.
The app allows users to leave messages in a virtual guestbook, which are then stored in a SQLite database.

Key Features:

    app.py: This Python file contains the core logic of the Guestbook Flask App. It sets up a Flask web server, defines routes, and interacts with the SQLite database. 
    The app has two main routes: the index route ("/") displays all messages stored in the database, and the "add_message" route ("/add_message") allows users to submit
    new messages.

    index.html: This HTML template file is used to render the main page of the guestbook app. It displays all stored messages in a user-friendly format.

    guestbook.db: This SQLite database file is used to store the messages submitted by users.
    The database table "messages" includes columns for the message's unique ID and its content.
