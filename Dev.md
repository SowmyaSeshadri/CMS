### Courier Management Services
### STAGE 1 : ANALYSIS


Functionalities - Customer UI:
- Pick up
- Track
- Location Finder
- Register/Login In
- View history

Functionalities - Admin
- Receive Pick Up
- Location Update
- Status Update
- Distribute data to specific location offices

Local-Admin
- Status Update
### 
STAGE 2 : UI/UX DESIGN

Home page 
- About
- Location Finder
- Register/Log In
    - Get details and store in USER DETAILS table
    - Log in page - check ID and Pwd and land to user home page.
- Footer(Contact Details)

User Home page
- Pick Up 
    - Collect details and store in PICKUP table.
- Track
    - Get details from STATUS TABLE(Updated by local admin) and Display.
- View history
    - Retrieve data from HISTORY table.

Admin Home page
- Login 
- Location Update
- Check Pick up updates and distribute to local admin.
- Check Status Update

Local Admin Home page
- Login
- Receive pick up orders
- UPDATE status.

STAGE 3: DEVELOPMENT 
Front End - HTML/CSS/Sass/JQuery/AJAX
Responsive Framework - Bootstrap
