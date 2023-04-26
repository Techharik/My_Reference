#Authentication Using Passport js creating sessions:

<h5>Step1:</h5>
Installing the packages:

<img src='./img/img-1.png' alt='packages needed'>

<h5>Step2:</h5>
Setting up  the packages for express server:
<img src='./img/img-2.png' alt='packages needed'>

Now the order of setting up the passportjs is important we need to follow the same exact order:

No-1:
setup session, passport initization and passort handle session
<img src='./img/img-3.png' alt='packages needed'>

No-2:
Connecting to the Database:
Creating Scehema:
plugin  schema with passport-local-mongoose
<img src='./img/img-4.png' alt='packages needed'>

No-4:
creating Model:
passport.createStrategy();
serilize and deserialize the user models;

<img src='./img/img-5.png' alt='packages needed'>




