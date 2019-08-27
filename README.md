# qa_adminlte2
Quickadmin AdminLTEv2

Installation instructions

1. Extract the archive and put it in the folder you want

2. Prepare your .env file there with database connection and other settings

3. Run composer install command

4. Run php artisan migrate --seed command.
Notice: seed is important, because it will create the first admin user for you.

5. Run php artisan key:generate command.

6. Run php artisan storage:link command.

And that's it, go to your domain and login:

Username: 	admin@admin.com
Password: 	password

P.S. If you want to use this admin panel for existing project, here's an article with instructions
