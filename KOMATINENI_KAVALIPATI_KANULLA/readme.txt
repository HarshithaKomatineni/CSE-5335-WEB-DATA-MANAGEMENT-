The new Mercado system is made up of:

1. A newly created Laravel backend web application. the app exposes a restful API similar to the one previously done in plain php. The API utilizes MVC pattern as required in the quiz. It has CRUD (create read update and delete) operations on login, sign up service,  user management, clubs management, club membership, Post management, .
All the routes are compatible with the react application, even on offline mode.(this means that the offline version can access the hosted Laravel MVC app even on desktop) the copy of the Laravel API has been hosted at: https://hxk8082.uta.cloud/phase5

-A copy of the modified react UI client application has been hosted online on the link (https://hxk8082.uta.cloud/front5/ ) for convenience.
-The emailing feature has also been created to enable registering users to receive email notifications upon signing up. this is done through SMTP library of Laravel. to view this open Laravel application and navigate to system user controller file to see the codes.

installation/running late Laravel/react js application:
--------------+----------------------------------_----------------------------
The Laravel application can be run offline by:
installing php 7.4 
installing MySQL server application
adding php to environmental variables on your operating system
composer
use composer to install Laravel with the command on your terminal/windows CMD. "composer require Laravel/installer"
To run the Laravel project, open terminal or command line, navigate to the folder containing Laravel project with CD command and type: "php artisan serve"
open /run your frontend react application and start login/signup
