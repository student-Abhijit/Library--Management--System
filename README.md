# Library--Management--System
 A web-based library management system allowing users to register, log in, view books, return, and administrators to manage users and books efficiently.  -Languages Use: Python-Flask,-Frontend:html5,CSS,Javascript,Bootstrap,-Database:sqlite3

### Project Summary
1. User Registration:
   - Endpoint: /registration
   - Method: POST
   - Parameters:Name,username, password

2. User Login:
   - Endpoint: /login
   - Method: POST
   - Parameters: username, password

3. Home Page:
   - Endpoint: /
   - Method: GET
   - Access: Authenticated users only

4. View Books:
   - Endpoint: /view
   - Method: GET
   - Access: Authenticated users only



5. Admin Login:
   - Endpoint: /admin_login
   - Method: POST
   - Parameters: username, password

6. Admin Operations:
   - Admin Dashboard:/admin_dashboard
   - Logout:/logout
   - Add User,Books: /post_blog (POST)
   - Delete Books: /admin/delete_books (POST)
   - Edit Books: /admin/edit_books (POST)
   - Delete User,Books: /blog_delete (POST)
   - Edit Username,Books: /profile_update (POST)
   - View More: /view_more (GET)


Admin Login Credentials:
   - Username: "admin@gmail.com"
   - Password: "admin"

### Requared Technologys 
1. Python-3
2. Flask

