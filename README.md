# Courier Management System using PHP/MySQLi

## About
The **Courier Management System** is a simple PHP/MySQLi project designed to help courier companies or businesses manage customer parcel details efficiently. The system includes features to store branch information, track parcels, and monitor movement. It offers two user roles: **Admin user** and **Branch Staff user**. Admin users manage all data in the system, including branches and branch staff, while branch users can track parcels and manage parcels specific to their branch.

### Key Features

#### Admin Side
1. **Login Page**: Admin users submit their credentials to access the system.
2. **Home Page**: Displays a summary of system data after admin login.
3. **New Branch Page**: Allows admins to add new branches for the courier company.
4. **List of Branches Page**: Displays and manages all branches of the courier company.
5. **New Branch Staff Page**: Enables the creation of new users for specific branches.
6. **Branch Staff List Page**: Lists and manages all branch staff users across the system.

#### Both User Roles
1. **New Parcel Page**: Users submit parcel details, including sender and recipient information.
2. **Parcel List Page**: Displays and manages all parcels.
3. **Track Parcel Page**: Tracks the movement of client parcels.
4. **Report Page**: Generates printable transaction reports based on date and parcel status.

### Parcel Statuses
The system tracks parcels using the following statuses:
- Item Accepted by Courier
- Collected
- Shipped
- In-Transit
- Arrived at Destination
- Out for Delivery
- Ready to Pickup
- Delivered
- Picked-up
- Unsuccessful Delivery Attempt

These statuses ensure clear visibility of parcel movement.

### Development Stack
- **Front-end**: HTML, CSS, Bootstrap
- **Back-end**: PHP/MySQLi
- **Scripting**: JavaScript (jQuery/Ajax)

The source code is fully functional and easy to modify or enhance for customization.

---

## How to Run the Project
1. **Download** the source code and extract the ZIP file.
2. **Set up a Local Web Server**:
   - Install any local web server capable of running PHP scripts (e.g., XAMPP).
3. **Database Configuration**:
   - Open the web server database (e.g., phpMyAdmin).
   - Create a new database named `cms_db`.
   - Import the SQL file located in the `database` folder of the project.
4. **Deploy the Code**:
   - Copy and paste the source code to your web server’s project directory (e.g., `C:\xampp\htdocs` for XAMPP).
5. **Run the Project**:
   - Open a web browser and browse to `http://localhost/courier-management-system`.

### Default Admin Access
- **Username**: `admin@admin.com`
- **Password**: `admin123`

## Additional Information
Feel free to download and modify the source code for your needs. This project is perfect for learning purposes and can be customized to meet specific business requirements. 

Enjoy coding and explore more projects and tutorials on this website!
