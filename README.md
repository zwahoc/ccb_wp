# CCB Assignment

This repository contains the source files for the **CCB Assignment** project. Follow the instructions below to set up the application locally.

## Repository

**GitHub:** [zwahoc/ccb_assignment](https://github.com/zwahoc/ccb_assignment)

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/zwahoc/ccb_assignment.git
   ```

2. **Download the SQL File**
   - Obtain the SQL dump file required to initialize the database (provided in the repository or externally as shared).

3. **Create the Database**
   - Create a new MySQL database named `rds_database`.

4. **Import the SQL File**
   - Use a tool like phpMyAdmin, MySQL Workbench, or the MySQL CLI to import the SQL file into the `rds_database`.

5. **Update Database Configuration**
   - Navigate to the cloned repository and locate the `wp_config.php` file.
   - Find the line that defines the database port and update it to `localhost` or the actual port your MySQL server is using.

6. **Access the Application**
   - Open a browser and visit:
     ```
     http://localhost/ccb_assignment/wp-admin
     ```

7. **Login as Administrator**
   - Use the following credentials to log in:
     - **Username:** `admin`
     - **Password:** `admin1234`

8. **You're All Set!**
   - The application is now ready for use.

---

For any issues or questions, please refer to the repository's [issues section](https://github.com/zwahoc/ccb_assignment/issues) or contact the project maintainers.
