# Git-Bash

Within this task we were learning how to use Git and Bash commands in VSCode.

1. Natalia@MacBook-Pro bash_training % pwd
/Users/Natalia/Desktop/bash_training

2. Natalia@MacBook-Pro bash_training % mkdir test1

3. Natalia@MacBook-Pro bash_training % cd test1
Natalia@MacBook-Pro test1 % 

4. Natalia@MacBook-Pro test1 % touch file_1.txt file_2.txt file_3.txt

5. Natalia@MacBook-Pro test1 % ls
file_1.txt      file_2.txt      file_3.txt

6. Natalia@MacBook-Pro test1 % cd ..
Natalia@MacBook-Pro bash_training % 

Natalia@MacBook-Pro bash_training % mkdir test2

7. Natalia@MacBook-Pro bash_training % rmdir test2

8. Natalia@MacBook-Pro bash_training % cd test1
Natalia@MacBook-Pro test1 % rm -rf file_2.txt

9. Natalia@MacBook-Pro test1 % cd ..
Natalia@MacBook-Pro bash_training % mkdir test3
Natalia@MacBook-Pro bash_training % cd test3
Natalia@MacBook-Pro test3 % touch newfile.txt newfile2.txt

10. Natalia@MacBook-Pro test3 % cd ..
Natalia@MacBook-Pro bash_training % rm -rf test3

11. Natalia@MacBook-Pro bash_training % mkdir test4

12. Natalia@MacBook-Pro bash_training % mv test1/file_1.txt test4
Natalia@MacBook-Pro bash_training % mv test1/file_3.txt test4

13.Natalia@MacBook-Pro bash_training % cd test4
Natalia@MacBook-Pro test4 % echo line > file_1.txt 
Natalia@MacBook-Pro test4 % echo line >> file_1.txt
Natalia@MacBook-Pro test4 % echo line >> file_1.txt

14. Natalia@MacBook-Pro test4 % cat file_1.txt
line
line
line

15. Natalia@MacBook-Pro test4 % echo line > file_3.txt 
Natalia@MacBook-Pro test4 % echo line >> file_3.txt 
Natalia@MacBook-Pro test4 % echo line >> file_3.txt

16. Natalia@MacBook-Pro test4 % cat file_1.txt file_3.txt 
line
line
line
line
line
line

17. Natalia@MacBook-Pro test4 % nano file_1.txt
Natalia@MacBook-Pro test4 % cat file_1.txt
mine
mine
mine

