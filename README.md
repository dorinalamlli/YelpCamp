YelpCamp is a website where users can create and review campgrounds. You must have an account, in order to review or create a campground. This project was part of Colt Steele's web dev course on udemy.

This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.

Features

 -Users can create, edit, and remove campgrounds
 
 -Users can review campgrounds once, and edit or remove their review
 
 -User profiles include more information on the user (full name, email, phone, join date), their campgrounds, and the option to edit their profile or delete their account
 
 -Search campground by name or location
 
 -Sort campgrounds by highest rating, most reviewed, lowest price, or highest price

Run it locally

 1.Install mongodb
 
 2.Create a cloudinary account to get an API key and secret code
 
 3.git clone https://github.com/dorinalamlli/YelpCamp.git
 
 4.cd YelpCamp
 
 5.npm install
 
 6.Create a .env file (or just export manually in the terminal) in the root of the project and add the following:
 

	DATABASEURL='<url>'
 
	API_KEY=''<key>
 
	API_SECRET='<secret>'
 
 
 7.Run mongod in another terminal and node app.js in the terminal with the project.
 
8. Go to localhost:3000.
