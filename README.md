My Finance
========================

Install composer in your system. Please have a look on the link https://getcomposer.org/doc/00-intro.md
for installation help. Checkout the project in your web directory. Now from command line change the current
directory to the project web directory. Now run the following command- composer install
The command will download and install all dependencies of the project. You have to install mysql prior to run the project.
Check the file app/config/parameters.yml for database configuration.

From the command line in project directory type- php app/console server:run
This will start the server. Now in browser go to location http://localhost:8000 to view the project.