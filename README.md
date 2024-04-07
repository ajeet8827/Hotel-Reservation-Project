                                                                               Hotel-Reservation-System (JDBC WITH MYSQL + OOPS + EXCEPTION HANDLING)
                                                                        =================================================================================
This Java project is a simple Hotel Reservation System implemented using JDBC (Java Database Connectivity) for connecting to a MySQL database. Below is an explanation of the project structure and functionality:

### Project Structure:

- **HotelReservationSystem.java**: This is the main class that contains the entry point `main` method. It interacts with the user through the console and provides options to reserve a room, view reservations, get room numbers, update reservations, delete reservations, and exit the system.
  
### Functionality:

1. **Reserve a Room**: Allows the user to reserve a room by providing guest name, room number, and contact number. This information is stored in the MySQL database.

2. **View Reservations**: Displays a list of current reservations stored in the database, including reservation ID, guest name, room number, contact number, and reservation date.

3. **Get Room Number**: Allows the user to input a reservation ID and guest name to retrieve the corresponding room number.

4. **Update Reservations**: Enables the user to update an existing reservation by providing a reservation ID. They can modify the guest name, room number, and contact number.

5. **Delete Reservations**: Allows the user to delete a reservation by providing the reservation ID.

6. **Exit**: Exits the system with a countdown message.

### Database Connectivity:

- The project utilizes JDBC to connect to a MySQL database. The connection details such as URL, username, and password are stored as constants within the class.
- SQL queries are constructed to perform database operations like insertion, selection, updating, and deletion.

### Exception Handling:

- Exceptions such as `ClassNotFoundException` and `SQLException` are handled within try-catch blocks to provide error messages to the user and prevent application crashes.

### How to Use:

- Clone or download the project from GitHub.
- Set up a MySQL database with the name `hotel_db` and appropriate tables (`reservations` table in this case) as per the SQL queries used in the project.
- Modify the `url`, `username`, and `password` constants in `HotelReservationSystem.java` to match your database configuration.
- Compile and run `HotelReservationSystem.java`. You will be presented with a menu to perform various operations. Follow the prompts to interact with the system.

### Uploading to GitHub:

- To upload this project to GitHub, create a new repository on GitHub.
- Initialize a Git repository in your project directory (`git init`).
- Add the project files (`git add .`) and commit them (`git commit -m "Initial commit"`).
- Link your local repository to the remote GitHub repository (`git remote add origin <repository URL>`).
- Push your changes to GitHub (`git push -u origin master`).

This explanation should help users understand the project and its functionality, and guide them on how to upload it to GitHub.
