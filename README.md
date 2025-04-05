Getting Started
Prerequisites
Node.js for running server-side JavaScript. You can find instructions on how to download and install Node.js for your computer here.

MongoDB (Community Edition preferrably) to store data. Instructions on downloading and installing MongoDB on your computer can be found here.

Installing
Once you have Node.js and MongoDB installed on your computer,

Clone or download this repository.
git clone https://github.com/rohithyv/Airline-Booking-Management-System.git
Change the folder and Install dependencies.
cd avian
npm install
Create a .env file and add the following:
seshSECRET = <session secret>
dbSECRET = <database secret>
Run the project.
npm start
Open your web browser and visit the address localhost:3000 and voila!

Features
Authentication:

User login with email and password.
For new user, there is a sign-up option.
Authorization:

User can only book and cancel ticktets after logging in.
User cannot cancel flight tickets without being authenticated.
Ticket booking functionalities:

Search for tickets with necessary parameters.
Filter search by price, duration or alphatical order.
Contact feature for any queries.

Flash messages responding to users' interaction with the app.

Responsive web design.


Built with
Front-end
ejs
bootstrap
jQuery
Back-end
node.js
express
mongoDB
mongoose
async
helmet
passport
express-session
connect-flash
Platforms
git
heroku
github
