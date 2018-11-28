System includes:
Registration, Login, Dashboard, Email Password, Logout

Account Update, Edit User Profile

Browse Users, Public Profile Pages

Cookie Policy, Privacy Policy, T&C’s, FAQ

404 (Not Found)

The User Registration System is Fully Responsive out the box and you can Restrict Access to any page!

Tech Stack:
NodeJS
React
Server-side Rendered
Apollo Client
GraphQL
MongoDB
JSON Web Tokens
Webpack
SASS
Top Features:
Bcrypt password encryption/verification
CKEditor - WYSIWYG editor
File Upload – Profile Images
Nodemailer – Custom mail server used to send password reset emails
Custom ‘Password Reset’ Template (Built with MJML Framework)
Multiple Layouts – Create unlimited layouts for pages/routes
Toastr - Simple javascript toast notifications

Download & Install Dependencies on your machine
Clone the repo to your machine
git clone <CloneURL>
Within terminal or cmd ensure you have navigated inside the cloned directory and install the dependencies
cd <new-dir> 
yarn install OR npm install
Configure Webpack
Before we can build, run or deploy our app it is important to ensure that the 'webConfig.json' file is configured correctly for our environment.

{
    "siteURL": "http://localhost:3000",
    "environment": "development"
}
Please ensure that 'siteURL' is set to either localhost or your websites domain. You must update this before running a build or deploying your web app.

In the same way, set ‘environment’ to either ‘development’ or ‘production’. This will change the way webpack compiles your code.

Set-up MongoDB (Setting up your database)
This web app uses MongoDB to save, query and process data. Whilst you may have a preference of your service provider (AWS, Microsoft Azure etc…) we will be using ‘mlab’.

Please visit ‘mlab’ register/login to your account.

Link- https://mlab.com/

From your control panel select ‘Create new’
Choose any of the Cloud Provider’s
Select the appropriate ‘Plan Type’ for you. For now, let’s select the ‘Free’ plan
Click Continue
Select the ‘Region’ that’s closest to your location and click continue
Enter a new database name and click continue
Confirm your selections and click ‘Submit order’ (Free)
The database will now be created, and you will have been redirected back to your dashboard.

Adding a User to your database
Under ‘MongoDB Deployments’ click on the database you just created
Select ‘Users’
Select ‘Add database users’
Enter a Username and Password and click ‘Create’
Please remember this information as we will need it later.
