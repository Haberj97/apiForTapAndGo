STEPS TO START THE PROJECT : 

To start the project, you need to check if you are on the right versions of php and Laravel, which are php 7.4.27 and Laravel 8. 
When you pull the project, get in the api folder, and execute the following command : composer install. 
Next, you need to execute this one : cp .env.example .env, in order to set a .env for the project. 
Make sur  that you database has the same name as the one in the .env, which is called Laravel by default. You can either change it if needed, or create a new one with the same name. 
Then, all you need is to run the command : ./artisan serve to start your server ( if this command does not work later, do not worry, run ./artisan optimize before it to clear all you caches, and you should be all set to start it again. ) 
