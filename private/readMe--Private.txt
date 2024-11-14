If you are using Git and do not want a subdirectory to sync to Git (and become public), then just add the subdirectory name to the file called "gitignore" in the SQAFFOLD root directory like this:

private/

Use a new line for each subdirectory you want Git to "ignore".
The Private subdirectory is currently not ignored by Git, so make sure to add this to the gitignore file if you want to keep your Private directory private :)