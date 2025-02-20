# Swift Banking App

## Team:

- ST10108388: Aiden Byrne ST10108388
- ST10150631: Michael Stewart Turner ST10150631
- ST10023767: Mikayle Devonique Coetzee ST10023767

## Video 
Youtube Video part 3 -  https://www.youtube.com/watch?v=axEJe63Yps4
Youtube Video -  https://www.youtube.com/watch?v=5kdcn55uN-U

## Project Overview:
This project involves developing a secure International Payments Portal for an international bank. The portal enables customers to register, log in, and make international payments, which are then verified and processed by employees in part 3.

## Please Note that there are files that would never be uploaded or publically shared in a real world scenerio however to allow lectureres to run the application these files are available and can be configured.

## Technologies Used
- Frontend: React (JavaScript)
- Backend: Node.js with Express
- Database: MongoDB

## Security Tools Used:
- Express Brute for brute-force protection
- SSL for securing communication
- Hashing and Salting for password security
- Input Whitelisting with RegEx patterns
- Helmet.js for setting express headers securely
- byCrypt for password hashing and encrypting
- xxs-clean For the prevention of Cross Site Scripting
- Express Rate limit to limit requests to the API and defend against DOS & DDOS
- Sonar Cube for security analysis

## Prerequisites:
- Node.js: Ensure you have Node.js installed.
- MongoDB: You need a running MongoDB instance. You can use a local setup or MongoDB Atlas.
- Visual Studio Code: Download Visual Studio Code for editing and managing the project.
- Google Chrome

## PLEASE NOTE IF USING CHROME

- Enter this link in your browser  chrome://flags/#allow-insecure-localhost
- You will then have the 'Allow invalid certificates for resources loaded from localhost.' to enabled
- This allows the browser to run the local certificates and ensure HTTPS
- Once deployed onto a server this issue will no longer persist.


## Installation Instructions
1. Clone the Repository
2. Install Backend Dependencies 
3. Install Frontend Dependencies 
4. Configure Environment Variables
5. Run MongoDB Locally (if needed)
6. Run the Application

The application should be running on:
- Frontend: http://localhost:3000
- Backend: http://localhost:3001

## Features

### Customer Portal
- Registration: Secure registration with full name, ID number, account number, and password.
- Login: Customer logs in with username, account number, and password.
### International Payment:
- Select amount, currency, and payment provider (e.g., SWIFT).
- Input payee's account information and SWIFT code.
- Finalize the payment.

## ADDITIONS

# Employee accounts that can securely manage transactions 

# Admin accounts that can add Employees 

# Mange Transactions Page 
- employees can view , filter and manage transactions from here.

## Accounts: 
# Admin 
-  NewAdmin1   password - Testing@123
-  MikeAdmin   password - Testing@123


# Employee 
-  Guy@Swift     Password- Testing@123
-  MikeEmployee     Password- Testing@123

## Security Features
- Password Hashing: Passwords are hashed and salted before being stored in the database.
- Express Brute: Protects against brute-force attacks during login.
- RegEx Input Whitelisting: Ensures inputs conform to specific patterns, reducing vulnerability to SQL injection and XSS attacks.
- SSL Encryption: All traffic is encrypted using SSL.
- Session Management: Protects against session hijacking.


