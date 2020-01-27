# OSPOS
repositorio de OSPOS 
For this version an upgrade is required:

Update from 3.3.0 to 3.3.1
WARNING: Always a good idea to do a backup previous to an upgrade. This is not an exception.

Backup your database.
Backup your ospos files (normally at web server place)
Backup your ospos/application/config/database.php and ospos/application/config/config.php files
Remove all your ospos files (do not remove nor modify database data!!!)
Extract the files for version 3.3.1
Move the files to your web server place
Copy application/config/database.php.tmpl to application/config/database.php
Restore the content of your ospos/application/config/database.php and ospos/application/config/config.php files in the new files
Move the content of old uploads dir to public/uploads
Make sure your webroot points to public/ directory as index.php is now contained there
Log into OSPOS and wait for the automatic migration to complete (the login only takes longer the first time)
Now you are good to go and use your new version of OSPOS
