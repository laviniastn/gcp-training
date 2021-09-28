Permissions are access rights for files and directory. Each file/ directory has acces rights for the owner, group and others. 
Rigths: read(r), write(w) and execute (x). For each file/ directory we can have rwxrwxrwx, which means owner (first three characters) can read, write, execute ; group ( next three characters ) can read, write, execute; others (last three characters) can read, write, execute
A directory is identified by the first character d, and the file by first character - 
For example the acces rigth expresses by the octal value 0754 means: 7- (in binary 111) for owner:rwx; 5- (in bunary 101) for group:r-x; 4-(in binary 100) for others:r--
chmod 0754 file_name - command used to set the specific rigth to a file (same for directory)
